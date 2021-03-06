## About

Simple test of few RAML Go parsers. Tests simply try to parse a set of examples and report if parser returned an error.

A fine collection of RAML files can be composed each containing one/few RAML features to test those in isolation.

Uses [raml-tck](https://github.com/raml-org/raml-tck/tree/master/tests/raml-1.0) as a source of tests.

NOTE: If file name contains "invalid" parsing of it is expected to fail.

## Install & run

```sh
git clone git@github.com:postatum/raml-parsers-test-js.git
cd raml-parsers-test-js
npm install
node src/index.js --parser PARSER_NAME
```

## Options

Parser (defaults to `jumpscale`):
```sh
node src/index.js --parser ramlfications/raml1parser
```

Verbose output (prints errors) (defaults to `false`):

```sh
node src/index.js --verbose
```
