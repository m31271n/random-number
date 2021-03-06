# random-number

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![Dependency Status](https://img.shields.io/david/m31271n/random-number.svg)](#)
[![DevDependency Status](https://img.shields.io/david/m31271n/random-number.svg)](#)
[![Travis Build Status](https://img.shields.io/travis/m31271n/random-number.svg)](#)
[![NPM Downloads](https://img.shields.io/npm/dm/@m31271n/random-number.svg)](#)

> Get a number randomly.

## Install

```
$ npm install @m31271n/random-number
```

## Usage

```js
import randomNumber from '@m31271n/random-number'

randomNumber({
  min: 1
  max: 1000,
  float: true,
  includeMax: true
})
```

## API

### randomNumber(options)

| property     | type    | description                 |
| ------------ | ------- | --------------------------- |
| `min`        | Number  | minimum value               |
| `max`        | Number  | maximum value               |
| `float`      | Boolean | float or integer            |
| `includeMax` | Boolean | include maxmum value or not |

## License

[MIT](https://stack.m31271n.com/licenses/MIT.txt) © [m31271n](https://stack.m31271n.com)
