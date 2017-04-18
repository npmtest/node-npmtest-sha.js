# npmtest-sha.js

#### test coverage for  [sha.js (v2.4.8)](https://github.com/crypto-browserify/sha.js)  [![npm package](https://img.shields.io/npm/v/npmtest-sha.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sha.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sha.js.svg)](https://travis-ci.org/npmtest/node-npmtest-sha.js)

#### Streamable SHA hashes in pure javascript

[![NPM](https://nodei.co/npm/sha.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sha.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sha.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sha.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sha.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sha.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sha.js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sha.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sha.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sha.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sha.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sha.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sha.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sha.js/build/test-report.html](https://npmtest.github.io/node-npmtest-sha.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sha.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sha.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sha.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sha.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sha.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sha.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sha.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sha.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dominic Tarr",
        "url": "dominictarr.com"
    },
    "bin": {
        "sha.js": "./bin.js"
    },
    "bugs": {
        "url": "https://github.com/crypto-browserify/sha.js/issues"
    },
    "dependencies": {
        "inherits": "^2.0.1"
    },
    "description": "Streamable SHA hashes in pure javascript",
    "devDependencies": {
        "buffer": "~2.3.2",
        "hash-test-vectors": "^1.3.1",
        "standard": "^4.0.0",
        "tape": "~2.3.2",
        "typedarray": "0.0.6"
    },
    "directories": {},
    "dist": {
        "shasum": "37068c2c476b6baf402d14a49c67f597921f634f",
        "tarball": "https://registry.npmjs.org/sha.js/-/sha.js-2.4.8.tgz"
    },
    "gitHead": "c233442bbd5695863d03155511d61bc8dcc63652",
    "homepage": "https://github.com/crypto-browserify/sha.js",
    "license": "MIT",
    "maintainers": [
        {
            "name": "dominictarr"
        },
        {
            "name": "dcousens"
        }
    ],
    "name": "sha.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/crypto-browserify/sha.js.git"
    },
    "scripts": {
        "lint": "standard",
        "prepublish": "npm ls && npm run unit",
        "test": "npm run lint && npm run unit",
        "unit": "set -e; for t in test/*.js; do node $t; done;"
    },
    "version": "2.4.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
