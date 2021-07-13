# Welcome to eslint-config-productsway 👋

[![Version](https://img.shields.io/npm/v/eslint-config-productsway.svg)](https://www.npmjs.com/package/eslint-config-productsway)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](#)
[![Twitter: jellydn](https://img.shields.io/twitter/follow/jellydn.svg?style=social)](https://twitter.com/jellydn)

> Airbnb's ESLint config with TypeScript and Prettier support

## Install

```sh
yarn add -D eslint-config-productsway
```

## Usage

Create a .eslintrc.js file in the root of your project's directory

```sh
module.exports = {
  extends: ['airbnb-typescript-prettier'],
};
```

## Configure the ESLint TypeScript parser

```sh
module.exports = {
  extends: ['airbnb-typescript-prettier'],
   parserOptions: {
   project: './tsconfig.json',
 }
};
```

## Run ESLint

Open a terminal to the root of your project, and run the following command:

```sh
npx eslint . --ext .js,.jsx,.ts,.tsx
```

## Author

👤 **Huynh Duc Dung**

- Website: https://productsway.com/
- Twitter: [@jellydn](https://twitter.com/jellydn)
- Github: [@jellydn](https://github.com/jellydn)

## Show your support

Give a ⭐️ if this project helped you!

---

_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
