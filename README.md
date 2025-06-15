# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

## Installation

```bash
npx create-docusaurus@latest exin-docusaurus classic
```
from the termianl execute the command above, thi will create a folder called exin-docusaurus and initialize it with the docusaurus files.

## Local Development

```bash
npm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```bash
npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Repository: 

```bash
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/nand0l/cognito-docusaurus.git
git push -u origin main
```

[https://github.com/nand0l/exin-docusaurus](https://github.com/nand0l/cognito-docusaurus)

## Deployment

The app will be deployed to [AWS Amplify](https://aws.amazon.com/amplify/) in the region `eu-central-1` using the cli profile `nlu-sks`.

<https://946997026676.eu-central-1.console.aws.amazon.com/amplify/apps/d51sxtw2jxfum/overview/>
<https://main.d51sxtw2jxfum.amplifyapp.com/>