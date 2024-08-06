---
title: Genezio
description: 'Deploy your Nuxt Application to Genezio infrastructure.'
logoSrc: '/assets/integrations/genezio.svg'
category: Hosting
nitroPreset: 'genezio'
website: 'https://www.genezio.com/'
---

Nuxt supports deploying on [Genezio](https://genezio.com/) with minimal configuration.

# Project Setup

## 1. Install genezio CLI globally

```bash
npm install genezio -g
```

## Build and deploy

Run the following command in your terminal to deploy your Nuxt project:

```bash
genezio deploy
```

When deploying, Genezio automatically detects the used framework and builds accordingly.\
Building the project will automatically create a default `genezio.yaml` configuration file, if it doesn't already exist.

By default, the name will be the one specified in the `package-lock.json` file, and the region will be set to `us-east-1`.

To further customize the file to your needs, you can consult the
[official documentation](https://genezio.com/docs/project-structure/genezio-configuration-file/).

For projects that set environment backends, you can check the following tutorial: [Genezio - Environment Variables](https://genezio.com/docs/project-structure/backend-environment-variables).

## 3. Monitor your project
You can monitor and manage your application through the [Genezio App Dashboard](https://app.genez.io/dashboard). The dashboard URL, also provided after deployment, allows you to access comprehensive views of your project's status and logs.

::read-more{to="https://nitro.unjs.io/deploy/providers/genezio" target="_blank"}
Head over **Nitro documentation** to learn more about the Genezio deployment preset.
::
