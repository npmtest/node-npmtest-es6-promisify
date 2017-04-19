# npmtest-es6-promisify

#### test coverage for  [es6-promisify (v5.0.0)](https://github.com/digitaldesignlabs/es6-promisify#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-es6-promisify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-es6-promisify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-es6-promisify.svg)](https://travis-ci.org/npmtest/node-npmtest-es6-promisify)

#### Converts callback-based functions to ES6 Promises

[![NPM](https://nodei.co/npm/es6-promisify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/es6-promisify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-es6-promisify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-es6-promisify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-es6-promisify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-es6-promisify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-es6-promisify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-es6-promisify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-es6-promisify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-es6-promisify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-es6-promisify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-es6-promisify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-es6-promisify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-es6-promisify/build/test-report.html](https://npmtest.github.io/node-npmtest-es6-promisify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-es6-promisify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-es6-promisify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-es6-promisify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-es6-promisify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-es6-promisify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-es6-promisify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-es6-promisify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-es6-promisify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mike Hall"
    },
    "bugs": {
        "url": "http://github.com/digitaldesignlabs/es6-promisify/issues"
    },
    "dependencies": {
        "es6-promise": "^4.0.3"
    },
    "description": "Converts callback-based functions to ES6 Promises",
    "devDependencies": {
        "babel-preset-es2015": "^6.9.0",
        "eslint": "^2.13.1",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "nodeunit": "^0.10.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5109d62f3e56ea967c4b63505aef08291c8a5203",
        "tarball": "https://registry.npmjs.org/es6-promisify/-/es6-promisify-5.0.0.tgz"
    },
    "files": [
        "dist/promisify.js",
        "dist/promise.js"
    ],
    "gitHead": "7eb2f5e9ae858742d495978efebafaee6719da97",
    "greenkeeper": {
        "ignore": [
            "eslint"
        ]
    },
    "homepage": "https://github.com/digitaldesignlabs/es6-promisify#readme",
    "keywords": [
        "promises",
        "es6",
        "promisify"
    ],
    "license": "MIT",
    "main": "dist/promisify.js",
    "maintainers": [
        {
            "name": "digitaldesignlabs"
        },
        {
            "name": "mikehall314"
        }
    ],
    "name": "es6-promisify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/digitaldesignlabs/es6-promisify.git"
    },
    "scripts": {
        "pretest": "./node_modules/eslint/bin/eslint.js ./lib/*.js ./tests/*.js",
        "test": "gulp && nodeunit tests"
    },
    "version": "5.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
