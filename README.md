# NPM Config Stylelint

Basic stylelint setting for optimizing styles.

![npm](https://img.shields.io/npm/v/@m2collective/npm-config-stylelint?style=for-the-badge)
![npm](https://img.shields.io/npm/dt/@m2collective/npm-config-stylelint?style=for-the-badge)
___

## Installation

This package can be deployed automatically using NPM:

```
npm i @m2collective/npm-config-stylelint
```

## Usage

Add the following commands to the `package.json`

```json
{
    "scripts": {
        "lint:style": "stylelint \"**/*.{scss,pcss}\"",
        "lint:style:fix": "stylelint \"**/*.{scss,pcss}\" --fix"
    }
}
```

Create a file `stylelint.config.js` with the following contents.

```js
import defaultConfig from '@m2collective/npm-config-stylelint'

export default defaultConfig
```

## License

The MIT License (MIT). Please see the [License file](LICENSE.txt) for more information.
