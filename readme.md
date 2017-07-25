# castarray

> Ensure a value is an array and wrap it if it is not an array

This is a fork of [`cast-array`](https://github.com/bendrucker/cast-array) 
by [Ben Drucker](https://github.com/bendrucker)
without support for IE8.

## Install

```
$ npm install --save castarray
```

## Usage

```js
var castArray = require('castarray')

castArray('input')
//=> ['input']

castArray(['input'])
//=> ['input']
```

## API

#### `castArray(value)` -> `array`

##### value

*Required*  
Type: `array` / `any`

A value to wrap in an array (unless it's already an array).

## License

MIT © Sam Gluck
