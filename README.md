👋

# prettier-config

Standard [Prettier configuration](https://prettier.io/docs/en/configuration.html) for Tilt/Shift projects.

## Installation

```bash
yarn add --dev @tiltshift/prettier-config
```

## Usage

In your `package.json`

```json
{
  "prettier": "@tiltshift/prettier-config"
}
```

If you wish you _extend_ these settings then in your `.prettierrc.js`

```js
module.exports = {
  ...require('@tiltshift/prettier-config'),
  semi: false,
}
```
