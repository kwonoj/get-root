[![Build Status](https://travis-ci.org/kwonoj/get-root.svg?branch=master)](https://travis-ci.org/kwonoj/get-root)
[![Build status](https://ci.appveyor.com/api/projects/status/mvpjn9ob40cubbuf?svg=true)](https://ci.appveyor.com/project/kwonoj/get-root)
[![codecov](https://codecov.io/gh/kwonoj/get-root/branch/master/graph/badge.svg)](https://codecov.io/gh/kwonoj/get-root)
[![npm](https://img.shields.io/npm/v/get-root.svg)](https://www.npmjs.com/package/get-root)
[![node](https://img.shields.io/badge/node-=>4.0-blue.svg?style=flat)](https://www.npmjs.com/package/get-root)

# get-root

`get-root` is simple utility wraps access to global object.

# Install

```sh
npm install get-root
```

# Usage


```js
import { root } from 'get-root';

//root is either `window` or `global` based on running environment.
```

# Building / Testing

Few npm scripts are supported for build / test code.

- `build`: Transpiles code to ES5 commonjs to `dist`.
- `test`: Run unit test
- `lint`: Run lint over all codebases
- `lint:staged`: Run lint only for staged changes. This'll be executed automatically with precommit hook.
- `commit`: Commit wizard to write commit message

# License

[MIT](https://github.com/kwonoj/get-root/blob/master/LICENSE)