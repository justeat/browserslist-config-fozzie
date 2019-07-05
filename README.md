# browserslist-config-fozzie
[![npm version](https://badge.fury.io/js/%40justeat%2Fbrowserslist-config-fozzie.svg)](https://badge.fury.io/js/%40justeat%2Fbrowserslist-config-fozzie)
[![Build Status](https://travis-ci.org/justeat/browserslist-config-fozzie.svg?branch=master)](https://travis-ci.org/justeat/browserslist-config-fozzie)

This package provides Just Eat's base JS .eslintrc as an extensible shared config.

It extends the [eslint-config-airbnb-base](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb-base) ruleset with our own set of JS linting rules.

Many thanks to the work that the Airbnb team have put in on creating their template for extension rules – we have liberally borrowed from their structure and documentation in creating this ruleset.

## Usage

### browserslist-config-fozzie

The default export contains a browserlist array.  Full information on browsrlist shareable configs [can be found in their README](https://github.com/browserslist/browserslist#shareable-configs).


To use this config, add the following to your package.json once you have installed the `@justeat/browserslist-config-fozzie` package.

```json
"browserslist": [
  "extends @justeat/browserslist-config-fozzie"
]
```
