# Build a Realtime Web Chat and deploy to AWS - TypeScript, Node, React & TailwindCSS - Backend

This repository has been created as a part of the YouTube video:
[Build a Realtime Web Chat and deploy to AWS - TypeScript, Node, React & TailwindCSS](https://youtu.be/82Geq2Jq0pg)

It is a backend part of a simple web chat application using API Gateway Webosockets with Serverless Framework Infrastructure as a Code
to easily deploy it to AWS.

## Prerequisites

- AWS CLI installed and configured
- [`serverless-framework`](https://github.com/serverless/serverless)
- [`node.js`](https://nodejs.org)

## Installation

Run:

```bash
npm install
```

or

```
yarn install
```

## Deployment

Run:

```bash
serverless deploy
```

## Licence

MIT.

## Steps

1. Download Aws cli, Node.js, VSCode, Serverless framework, Websocat
2. Check if aws cli is installed correctly ```aws --version```
3. Configure Aws cli with the command ```aws configure``` you can refer to this video: [Youtube](https://youtu.be/CjKhQoYeR4Q?si=Z271kwREnTyMNWU_)
4. Run command ```serverless deploy```
5. Now the cli should give you the endpoint for connection to the websocket example ```wss://xyz.amazon.aws.com/dev``` Note this endpoint we will require this to connect the frontend with backend.
