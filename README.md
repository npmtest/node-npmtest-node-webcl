# npmtest-node-webcl

#### basic test coverage for  node-webcl (v0.9.2)  [![npm package](https://img.shields.io/npm/v/npmtest-node-webcl.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-webcl) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-webcl.svg)](https://travis-ci.org/npmtest/node-npmtest-node-webcl)

#### A WebCL implementation for desktops with NodeJS

[![NPM](https://nodei.co/npm/node-webcl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-webcl)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-webcl/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-webcl/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-webcl/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-webcl/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-webcl/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-webcl/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-webcl/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-webcl/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-webcl/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-webcl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-webcl/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-webcl/build/test-report.html](https://npmtest.github.io/node-npmtest-node-webcl/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-webcl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-webcl/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-webcl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-webcl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-webcl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-webcl/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-webcl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-webcl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-webcl",
    "version": "0.9.2",
    "description": "A WebCL implementation for desktops with NodeJS",
    "main": "webcl.js",
    "author": "Mikael Bourges-Sevenier <mikeseven@gmail.com>",
    "keywords": [
        "webcl",
        "opencl"
    ],
    "maintainers": [
        {
            "name": "Mikael Bourges-Sevenier"
        }
    ],
    "licenses": [
        {
            "type": "BSD",
            "url": "https://github.com/mikeseven/node-webcl/blob/master/LICENSES"
        }
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/mikeseven/node-webcl"
    },
    "directories": {
        "src": "src",
        "lib": "lib",
        "docs": "docs",
        "examples": "examples",
        "test": "test"
    },
    "scripts": {
        "install": "node-gyp rebuild --msvs_version=2013"
    },
    "dependencies": {
        "node-webgl": ">=0.4.2",
        "node-image": ">=0.7.1",
        "nan": "~1.2.0"
    },
    "devDependencies": {
        "chai": "*",
        "mocha": "*"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
