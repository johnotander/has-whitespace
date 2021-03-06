# has-whitespace [![Build Status](https://secure.travis-ci.org/johnotander/has-whitespace.png?branch=master)](https://travis-ci.org/johnotander/has-whitespace) [![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

Check whether a string contains whitespace.

## Installation

```bash
npm install --save has-whitespace
```

## Usage

```javascript
var hasWhitespace = require('has-whitespace')

hasWhitespace('foo')  // false
hasWhitespace('bar')  // false

hasWhitespace(' foo ')  // true
hasWhitespace('bar\r')  // true
```

## License

MIT

## Acknowledgements

* [is-whitespace](https://github.com/jonschlinkert/is-whitespace)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Crafted with <3 by [John Otander](http://johnotander.com) ([@4lpine](https://twitter.com/4lpine)).

***

> This package was initially generated with [yeoman](http://yeoman.io) and the [p generator](https://github.com/johnotander/generator-p.git).
