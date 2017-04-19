# npmtest-express-generator

#### basic test coverage for  [express-generator (v4.15.0)](https://github.com/expressjs/generator#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-express-generator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-generator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-generator.svg)](https://travis-ci.org/npmtest/node-npmtest-express-generator)

#### Express' application generator

[![NPM](https://nodei.co/npm/express-generator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-generator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-generator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-generator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-generator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-generator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-generator/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-generator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-generator/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-generator/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-generator/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-generator/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-generator/build/test-report.html](https://npmtest.github.io/node-npmtest-express-generator/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-generator/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-generator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-generator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-generator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-generator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-generator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk"
    },
    "bin": {
        "express": "./bin/express-cli.js"
    },
    "bugs": {
        "url": "https://github.com/expressjs/generator/issues"
    },
    "contributors": [
        {
            "name": "Aaron Heckmann"
        },
        {
            "name": "Ciaran Jessup"
        },
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Guillermo Rauch"
        },
        {
            "name": "Jonathan Ong"
        },
        {
            "name": "Roman Shtylman"
        }
    ],
    "dependencies": {
        "commander": "2.9.0",
        "ejs": "2.5.6",
        "mkdirp": "0.5.1",
        "sorted-object": "2.0.1"
    },
    "description": "Express' application generator",
    "devDependencies": {
        "eslint": "3.18.0",
        "eslint-config-standard": "7.1.0",
        "eslint-plugin-promise": "3.5.0",
        "eslint-plugin-standard": "2.1.1",
        "mocha": "2.5.3",
        "rimraf": "2.5.4",
        "supertest": "1.2.0",
        "validate-npm-package-name": "2.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "81ba5ca8db9ceeaee281a08f5ad5c3f472430006",
        "tarball": "https://registry.npmjs.org/express-generator/-/express-generator-4.15.0.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "files": [
        "LICENSE",
        "bin/",
        "templates/"
    ],
    "gitHead": "298832e6daaba3b1759e83f4b9969a80a8ca7a0b",
    "homepage": "https://github.com/expressjs/generator#readme",
    "keywords": [
        "express",
        "framework",
        "sinatra",
        "web",
        "rest",
        "restful",
        "router",
        "app",
        "api"
    ],
    "license": "MIT",
    "main": "bin/express-cli.js",
    "maintainers": [
        {
            "name": "dougwilson"
        }
    ],
    "name": "express-generator",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/generator.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-ci": "mocha --reporter spec --check-leaks test/"
    },
    "version": "4.15.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
