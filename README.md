# test coverage for  [ms (v1.0.0)](https://github.com/zeit/ms#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ms.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ms) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ms.svg)](https://travis-ci.org/npmtest/node-npmtest-ms)
#### Tiny milisecond conversion utility

[![NPM](https://nodei.co/npm/ms.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ms)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ms/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ms/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ms/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ms/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ms/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ms/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ms/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ms/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ms/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ms/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ms/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ms/build/test-report.html](https://npmtest.github.io/node-npmtest-ms/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ms/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ms/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ms/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ms/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ms/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ms/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ms/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ms/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/zeit/ms/issues"
    },
    "dependencies": {},
    "description": "Tiny milisecond conversion utility",
    "devDependencies": {
        "eslint": "3.18.0",
        "expect.js": "0.3.1",
        "husky": "0.13.2",
        "lint-staged": "3.4.0",
        "mocha": "3.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "59adcd22edc543f7b5381862d31387b1f4bc9473",
        "tarball": "https://registry.npmjs.org/ms/-/ms-1.0.0.tgz"
    },
    "eslintConfig": {
        "extends": "eslint:recommended",
        "env": {
            "node": true,
            "es6": true
        }
    },
    "files": [
        "index.js"
    ],
    "gitHead": "7daf984a9011e720cc3c165ed82c4506f3471b37",
    "homepage": "https://github.com/zeit/ms#readme",
    "license": "MIT",
    "lint-staged": {
        "*.js": [
            "npm run lint",
            "prettier --single-quote --write",
            "git add"
        ]
    },
    "main": "./index",
    "maintainers": [
        {
            "name": "leo"
        },
        {
            "name": "rauchg"
        }
    ],
    "name": "ms",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zeit/ms.git"
    },
    "scripts": {
        "lint": "eslint lib/* bin/*",
        "precommit": "lint-staged",
        "test": "mocha tests.js"
    },
    "version": "1.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
