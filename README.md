# npmtest-csscomb

#### test coverage for  [csscomb (v4.0.1)](http://csscomb.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-csscomb.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-csscomb) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-csscomb.svg)](https://travis-ci.org/npmtest/node-npmtest-csscomb)

#### CSS coding style formatter

[![NPM](https://nodei.co/npm/csscomb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/csscomb)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-csscomb/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-csscomb/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-csscomb/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-csscomb/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-csscomb/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-csscomb/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-csscomb/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-csscomb/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-csscomb/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-csscomb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-csscomb/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-csscomb/build/test-report.html](https://npmtest.github.io/node-npmtest-csscomb/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-csscomb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-csscomb/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-csscomb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-csscomb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-csscomb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-csscomb/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-csscomb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-csscomb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mikhail Troshev"
    },
    "bin": {
        "csscomb": "./bin/csscomb"
    },
    "bugs": {
        "url": "https://github.com/csscomb/csscomb.js/issues"
    },
    "dependencies": {
        "babel-polyfill": "6.23.0",
        "glob": "latest",
        "gonzales-pe": "^3.4.7",
        "minimatch": "3.0.2",
        "minimist": "1.1.x",
        "vow": "0.4.4",
        "vow-fs": "0.3.2"
    },
    "description": "CSS coding style formatter",
    "devDependencies": {
        "babel-cli": "^6.11.4",
        "babel-plugin-transform-es2015-destructuring": "^6.9.0",
        "babel-plugin-transform-strict-mode": "^6.11.3",
        "jscs": "2.1.0",
        "jshint": "2.8.0",
        "mocha": "1.20.1"
    },
    "directories": {},
    "dist": {
        "shasum": "a4b0139d7cf6223d635b6652ad31af0ee3e32331",
        "tarball": "https://registry.npmjs.org/csscomb/-/csscomb-4.0.1.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "files": [
        "bin",
        "config",
        "lib"
    ],
    "gitHead": "4bbdac36231d93199687004e2890e760412dc9fd",
    "homepage": "http://csscomb.com/",
    "license": "MIT",
    "main": "./lib/csscomb.js",
    "maintainers": [
        {
            "name": "tonyganch"
        }
    ],
    "name": "csscomb",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/csscomb/csscomb.js.git"
    },
    "scripts": {
        "build": "./scripts/build.sh",
        "coverage": "./scripts/coverage.sh",
        "prepublish": "./scripts/build.sh",
        "test": "./scripts/build.sh && ./scripts/test.sh",
        "watch": "./scripts/watch.sh"
    },
    "version": "4.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
