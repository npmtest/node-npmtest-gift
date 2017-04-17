# test coverage for  [gift (v0.10.0)](https://github.com/notatestuser/gift)  [![npm package](https://img.shields.io/npm/v/npmtest-gift.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gift) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gift.svg)](https://travis-ci.org/npmtest/node-npmtest-gift)
#### a Git wrapper library

[![NPM](https://nodei.co/npm/gift.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gift)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gift/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gift/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gift/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gift/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gift/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gift/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gift/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gift/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gift/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gift/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gift/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gift/build/test-report.html](https://npmtest.github.io/node-npmtest-gift/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gift/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gift/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gift/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gift/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gift/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gift/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gift/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gift/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "sentientwaffle",
        "url": "http://sentientwaffle.github.com/"
    },
    "bugs": {
        "url": "https://github.com/notatestuser/gift/issues"
    },
    "dependencies": {
        "underscore": "1.x.x"
    },
    "description": "a Git wrapper library",
    "devDependencies": {
        "coffee-script": "^1.10.0",
        "fs-extra": "^0.18.4",
        "mocha": "^2.3.3",
        "should": "~7.1.0",
        "sinon": "^1.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "4235e3edd9d375abb517a41e692d605100849d56",
        "tarball": "https://registry.npmjs.org/gift/-/gift-0.10.0.tgz"
    },
    "engines": {
        "node": "> 0.4.1"
    },
    "gitHead": "87988b8efbea251afe1f1bfa6ea2078581a04d76",
    "homepage": "https://github.com/notatestuser/gift",
    "keywords": [
        "git",
        "cli",
        "wrapper"
    ],
    "license": "MIT",
    "main": "./lib/index",
    "maintainers": [
        {
            "name": "sentientwaffle"
        },
        {
            "name": "notatestuser"
        }
    ],
    "name": "gift",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/notatestuser/gift.git"
    },
    "scripts": {
        "prepublish": "coffee -o lib -c src",
        "test": "mocha --compilers coffee:\"./node_modules/coffee-script/lib/coffee-script/register\""
    },
    "version": "0.10.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
