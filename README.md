## Requirements

You must have Node and Yarn installed on your computer [with the same versions than in our Check it with:

```bash
node -v
yarn -v
```

## Installation

First clone this repository to your laptop:

```bash
git clone git@github.com:hafid-Qa/webpack-boilerplate.git your-project-name
cd your-project-name
rm -rf .git
git init
code . # Open this folder in your text editor
```

install JS packages

```bash
yarn install
# or
npm install
```

Run the server:

```bash
yarn run dev
# or
npm run dev
```

## Once the server is running:

you can view your app in:

localhost:8080

to view an interactive treemap visualization of the contents of all your bundles.

localhost:8888

to stop this page from opening perform below change.

```bash
# comment below line in webpack.config.js
 new BundleAnalyzerPlugin(),
```
