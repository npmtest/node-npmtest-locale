# npmtest-locale

#### basic test coverage for  [locale (v0.1.0)](https://github.com/florrain/locale)  [![npm package](https://img.shields.io/npm/v/npmtest-locale.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-locale) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-locale.svg)](https://travis-ci.org/npmtest/node-npmtest-locale)

#### Browser locale negotiation for node.js

[![NPM](https://nodei.co/npm/locale.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/locale)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-locale/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-locale/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-locale/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-locale/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-locale/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-locale/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-locale/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-locale/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-locale/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-locale/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-locale/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-locale/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-locale/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-locale/build/test-report.html](https://npmtest.github.io/node-npmtest-locale/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-locale/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-locale/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-locale/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-locale/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-locale/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-locale/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-locale/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-locale/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Florian Lorrain"
    },
    "bugs": {
        "url": "https://github.com/florrain/locale/issues"
    },
    "contributors": [
        {
            "name": "Jed Smith",
            "url": "https://github.com/jed"
        },
        {
            "name": "D. Stuart Freeman",
            "url": "https://github.com/stuartf"
        }
    ],
    "dependencies": {},
    "description": "Browser locale negotiation for node.js",
    "devDependencies": {
        "coffee-script": "~1.6.0",
        "express": "~3.0.0",
        "mocha": "~1.13.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3b5bf70614fdab48ac3e3fbc648147cb65443bde",
        "tarball": "https://registry.npmjs.org/locale/-/locale-0.1.0.tgz"
    },
    "engines": {
        "node": ">0.8.x"
    },
    "gitHead": "860f5a1be620955f19f1cd303884c1c2d9cecd75",
    "homepage": "https://github.com/florrain/locale",
    "main": "./lib",
    "maintainers": [
        {
            "name": "florrain"
        },
        {
            "name": "jed"
        },
        {
            "name": "stuartf"
        }
    ],
    "name": "locale",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/florrain/locale.git"
    },
    "scripts": {
        "prepublish": "coffee -o lib/ -c src/",
        "test": "mocha ./src/test.coffee"
    },
    "version": "0.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
