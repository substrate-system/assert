# assert
![tests](https://github.com/substrate-system/assert/actions/workflows/nodejs.yml/badge.svg)
[![types](https://img.shields.io/npm/types/@substrate-system/assert?style=flat-square)](README.md)
[![module](https://img.shields.io/badge/module-ESM%2FCJS-blue?style=flat-square)](README.md)
[![semantic versioning](https://img.shields.io/badge/semver-2.0.0-blue?logo=semver&style=flat-square)](https://semver.org/)
[![Common Changelog](https://nichoth.github.io/badge/common-changelog.svg)](./CHANGELOG.md)
[![install size](https://flat.badgen.net/packagephobia/install/@substrate-system/assert)](https://packagephobia.com/result?p=@nichoth/session-cookie)
[![dependencies](https://img.shields.io/badge/dependencies-zero-brightgreen.svg?style=flat-square)](package.json)
[![license](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE)

The [`assert`](https://nodejs.org/api/assert.html) module from Node.js, for the browser.

The goal is to provide an API that is as functionally identical to the [Node.js `assert` API](https://nodejs.org/api/assert.html) as possible. Read the [official docs](https://nodejs.org/api/assert.html) for API documentation.

## Install

```sh
npm i -S assert
```

## Inconsistencies with Node.js `assert`

Due to differences between browsers, some error properties such as `message` and `stack` will be inconsistent. However the assertion behaviour is as close as possible to Node.js and the same error `code` will always be used.

## test

### `npm run test`
Build the source files into the `dist` dir and then run the tests against the built project.

## License

MIT © Joyent, Inc. and other Node contributors
