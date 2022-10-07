# @wyze/prettier-tailwind-trivago-compat &middot; [![Build Status][actions-image]][actions-url] [![npm][npm-image]][npm-url]

> A [Prettier](https://prettier.io) configuration to handle compatability between [tailwindcss](https://github.com/tailwindlabs/prettier-plugin-tailwindcss) and [@trivago/sort-imports](https://github.com/trivago/prettier-plugin-sort-imports) plugins. See this [issue](https://github.com/tailwindlabs/prettier-plugin-tailwindcss/issues/31).

## Installation

```sh
$ yarn add --dev @wyze/prettier-tailwind-trivago-compat
```

## Usage

#### `.prettierrc.js` or `prettier.config.js`

```js
module.exports = {
  ...require('@wyze/prettier-tailwind-trivago-compat'),
  // Existing configuration here
}
```

#### `package.json`

```json
{
  "prettier": "@wyze/prettier-tailwind-trivago-compat"
}
```

#### `prettierrc.json`

```json
"@wyze/prettier-tailwind-trivago-compat"
```

## License

MIT © [Neil Kistner](https://neilkistner.com)

[actions-image]: https://img.shields.io/github/workflow/status/wyze/prettier-tailwind-trivago-compat/CI?style=flat-square
[actions-url]: https://github.com/wyze/prettier-tailwind-trivago-compat/actions?query=workflow%3ACI

[npm-image]: https://img.shields.io/npm/v/@wyze/prettier-tailwind-trivago-compat.svg?style=flat-square
[npm-url]: https://npmjs.com/package/@wyze/prettier-tailwind-trivago-compat
