This is a [Docusaurus 2](https://docusaurus.io/) project, a modern static website generator.

## Usage

Install:

```
$ yarn
```

Develop:

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

Build:

```
$ yarn build
```

## Deploy on Wasmer Edge

The easiest way to deploy your Docusaurus app is to use the [Wasmer Edge](https://wasmer.io/products/edge).

Live example: http://wasmer-edge-docusaurus-sample.wasmer.app/

First, you'll need to run `yarn build`, and then, to deploy to Wasmer Edge:

```bash
wasmer deploy
```

> [!NOTE]
> You will need to have Wasmer installed (check out [the docs to install the Wasmer CLI](https://docs.wasmer.io/install)!). 
> You will also need to change the namespace in `wasmer.toml` to your own namespace and app name in `app.yaml` to your own app name.
