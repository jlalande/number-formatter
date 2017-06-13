# Number Formatter

[![Build Status](https://travis-ci.org/jlalande/number-formatter.svg?branch=master)](https://travis-ci.org/jlalande/number-formatter)

A small library that adds commas to numbers

See https://medium.com/@jdaudier/how-to-create-and-publish-your-first-node-js-module-444e7585b738

## Installation

  `npm install @jlalande/number-formatter`

## Usage

```
var numFormatter = require('@jdaudier/number-formatter');

var formattedNum = numFormatter(35666);
```

  Output should be `35,666`

## Tests

  `npm test`

## Contributing

In lieu of a formal style guide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code.