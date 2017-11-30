# stylelint-config-uclaradio

How UCLA Radio writes CSS and Sass. We use this on
[our website](https://github.com/uclaradio/uclaradio)!

You can add it to your project by installing
[`stylelint`](https://www.npmjs.com/package/stylelint) first, then
[`stylelint-config-uclaradio`](https://www.npmjs.com/package/stylelint-config-uclaradio),
then adding it to your `.stylelintrc` file.

## Installation

What you put in your terminal:

```shell
# We prefer yarn, but npm also works
yarn add --dev stylelint
yarn add --dev stylelint-config-uclaradio
```

Then configure your `.stylelintrc.json` (or alternative) as follows:

```json
{
  "extends": "stylelint-config-uclaradio"
}
```
