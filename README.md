# preact-default-boilerplate

[![XO code style](https://img.shields.io/badge/code_style-XO-5ed9c7.svg)](https://github.com/xojs/xo)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
[![lighthouse](https://img.shields.io/badge/lighthouse-100%2F100-brightgreen.svg)](https://github.com/GoogleChrome/lighthouse)
[![tested with jest](https://img.shields.io/badge/tested_with-jest-99424f.svg)](https://github.com/facebook/jest)

## Documentation
- This is a fork of the default template for [preact-cli](https://github.com/developit/preact-cli).
- [For Preact](https://preactjs.com/): General information about how to work with Preact, not specific to this template
- [XO](https://github.com/xojs/xo) & [Prettier](https://prettier.io/) for code style/linting


## Usage

``` bash
$ npm install -g preact-cli
$ preact create fwilkerson/default my-project
$ cd my-project
$ npm install
$ npm run dev
```

Development server runs on port `8080`. If the default port is already in use on your machine it will start the development server on a random port.

## Commands

- `npm run start`: Runs `serve` or `dev`, depending on `NODE_ENV` value. Defaults to `dev server`

- `npm run dev`: Run a development, HMR server

- `npm run serve`: Run a production-like server

- `npm run build`: Production-ready build

- `npm run lint`: Pass JavaScript files using XO

- `npm run test`: Run Jest and [`preact-render-spy`](https://github.com/mzgoddard/preact-render-spy) for your tests

### How to Test

The `default` template provides a basic test setup with Jest and [`preact-render-spy`](https://github.com/mzgoddard/preact-render-spy). You are free to change preact-render-spy with any other assertion library. The advantage of it is that it supports a similiar terminology and feature set as the Enzyme library for testing React applications.

You can run all additional Jest CLI commands with the `npm run test` command as described in the [Jest docs](https://facebook.github.io/jest/docs/en/cli.html#using-with-npm-scripts). For example, running jest in watch mode would be :

- `npm run test -- --watch` instead of  `jest --watch `