# npmtest-imap-simple

#### basic test coverage for  [imap-simple (v3.1.0)](https://github.com/chadxz/imap-simple#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-imap-simple.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-imap-simple) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-imap-simple.svg)](https://travis-ci.org/npmtest/node-npmtest-imap-simple)

#### Wrapper over node-imap, providing a simpler api for common use cases

[![NPM](https://nodei.co/npm/imap-simple.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/imap-simple)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-imap-simple/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-imap-simple/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-imap-simple/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-imap-simple/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-imap-simple/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-imap-simple/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-imap-simple/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-imap-simple/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-imap-simple/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-imap-simple/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-imap-simple/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-imap-simple/build/test-report.html](https://npmtest.github.io/node-npmtest-imap-simple/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-imap-simple/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-imap-simple/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-imap-simple/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-imap-simple/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-imap-simple/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-imap-simple/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-imap-simple/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-imap-simple/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/chadxz/imap-simple/issues"
    },
    "contributors": [
        {
            "name": "Chad McElligott"
        },
        {
            "name": "Erik Bernhardsson"
        },
        {
            "name": "Nate Watson"
        },
        {
            "name": "Robert Vulpe"
        },
        {
            "name": "Julian Bilcke"
        },
        {
            "name": "Bruce V. Schwartz"
        },
        {
            "name": "Tuomas Tanner"
        },
        {
            "name": "John Kawakami"
        },
        {
            "name": "Dominik Beste"
        }
    ],
    "dependencies": {
        "es6-promise": "^4.0.3",
        "iconv-lite": "~0.4.13",
        "imap": "^0.8.18",
        "nodeify": "^1.0.0",
        "quoted-printable": "^1.0.0",
        "utf8": "^2.1.1"
    },
    "description": "Wrapper over node-imap, providing a simpler api for common use cases",
    "devDependencies": {
        "chai": "^3.5.0",
        "istanbul": "^0.4.5",
        "jscs": "^3.0.7",
        "jshint": "^2.9.3",
        "mocha": "^3.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8b34a49adcb9c419dcd476f9552778e3f94cbade",
        "tarball": "https://registry.npmjs.org/imap-simple/-/imap-simple-3.1.0.tgz"
    },
    "gitHead": "3c0929986f6166bcb93b2cb4a58e0ae33bf4a792",
    "homepage": "https://github.com/chadxz/imap-simple#readme",
    "keywords": [
        "imap",
        "node-imap"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "chadxz"
        }
    ],
    "name": "imap-simple",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/chadxz/imap-simple.git"
    },
    "scripts": {
        "cover": "istanbul cover --report html _mocha",
        "lint": "jscs . && jshint .",
        "test": "mocha"
    },
    "version": "3.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
