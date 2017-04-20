# npmtest-api-mock

#### basic test coverage for  api-mock (v0.3.2)  [![npm package](https://img.shields.io/npm/v/npmtest-api-mock.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-api-mock) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-api-mock.svg)](https://travis-ci.org/npmtest/node-npmtest-api-mock)

#### A mock server generated from your API Blueprint.

[![NPM](https://nodei.co/npm/api-mock.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/api-mock)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-api-mock/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-api-mock/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-api-mock/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-api-mock/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-api-mock/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-api-mock/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-api-mock/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-api-mock/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-api-mock/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-api-mock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-api-mock/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-api-mock/build/test-report.html](https://npmtest.github.io/node-npmtest-api-mock/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-api-mock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-api-mock/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-api-mock/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-api-mock/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-api-mock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-api-mock/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-api-mock/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-api-mock/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "api-mock",
    "version": "0.3.2",
    "description": "A mock server generated from your API Blueprint.",
    "author": "Evan Cordell <cordell.evan@gmail.com>",
    "main": "lib/api-mock.js",
    "bin": {
        "api-mock": "bin/api-mock"
    },
    "scripts": {
        "test": "scripts/test",
        "build": "scripts/build",
        "prepublish": "scripts/prepublish"
    },
    "dependencies": {
        "protagonist": "~1.2.5",
        "optimist": "~0.6.0",
        "express": "~3.4.7",
        "uri-template": "~1.0.0",
        "winston": "~2.1.1"
    },
    "devDependencies": {
        "coffee-script": "1.6.3",
        "coffee-errors": "~0.8.4",
        "mocha": "1.17.0",
        "chai": "~1.9.0",
        "coffee-coverage": "0.4.1",
        "jscoverage": "0.3.8",
        "coveralls": "~2.8.0",
        "mocha-lcov-reporter": "0.0.1",
        "codo": "2.0.3",
        "sinon": "~1.9.0",
        "nock": "~0.27.1",
        "proxyquire": "~1.0.1",
        "supertest": "~0.13.0"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/localmed/api-mock"
    },
    "keywords": [
        "api",
        "test",
        "testing",
        "documenation",
        "integration",
        "acceptance",
        "server",
        "stub"
    ],
    "license": "MIT",
    "engine": "node >= 4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
