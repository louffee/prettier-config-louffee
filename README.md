# Louffee Prettier Configuration

*A great way to style.*

> **Note**: The configuration is based on the [Prettier](https://prettier.io) plugin for the IDE or code editor of your choice, and is compatible with the ESLint ecosystem present in the [NPM Package of same name](https://npmjs.com/package/prettier).

[![Downloads](https://img.shields.io/npm/dm/eslint-config-louffee.svg)](https://www.npmjs.com/package/prettier-config-louffee)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/louffee/prettier-config-louffee?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

## Installation

Install the package, follow the instructions according to the package manager of your choice, we ranked the top three most popular ones:

With **NPM**

```bash
npm install --dev prettier-config-louffee
```

With **Yarn**

```bash
yarn add -D prettier-config-louffee
```

With **PNPM**

```bash
pnpm install --dev prettier-config-louffee
```

## Usage 📖

To use the Louffee’s configuration, create a new file named `.prettierrc.js` in the root of your project, and add the following content:

```js
module.exports = require('prettier-config-louffee');
```

(Optional) Also create a `.prettierignore` file in the root of your project, then add the following line:

```plain
node_modules
```
