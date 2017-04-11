# test coverage for  [source-map-support (v0.4.14)](https://github.com/evanw/node-source-map-support#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-source-map-support.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-source-map-support) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-source-map-support.svg)](https://travis-ci.org/npmtest/node-npmtest-source-map-support)
#### Fixes stack traces for files with source maps

[![NPM](https://nodei.co/npm/source-map-support.png?downloads=true)](https://www.npmjs.com/package/source-map-support)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-source-map-support/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-source-map-support/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-source-map-support/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-source-map-support/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-source-map-support/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-source-map-support/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-source-map-support/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-source-map-support/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-source-map-support/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-source-map-support/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-source-map-support%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-source-map-support/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-source-map-support/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-source-map-support%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-source-map-support/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-source-map-support/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-source-map-support/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/evanw/node-source-map-support/issues"
    },
    "dependencies": {
        "source-map": "^0.5.6"
    },
    "description": "Fixes stack traces for files with source maps",
    "devDependencies": {
        "browserify": "3.44.2",
        "coffee-script": "1.7.1",
        "http-server": "^0.8.5",
        "mocha": "1.18.2",
        "webpack": "^1.13.3"
    },
    "directories": {},
    "dist": {
        "shasum": "9d4463772598b86271b4f523f6c1f4e02a7d6aef",
        "tarball": "https://registry.npmjs.org/source-map-support/-/source-map-support-0.4.14.tgz"
    },
    "gitHead": "8db1d646dbe9c05f824001477637b62dbcb49f0c",
    "homepage": "https://github.com/evanw/node-source-map-support#readme",
    "license": "MIT",
    "main": "./source-map-support.js",
    "maintainers": [
        {
            "name": "evanw",
            "email": "evan.exe@gmail.com"
        },
        {
            "name": "julien-f",
            "email": "julien.fontanet@isonoe.net"
        },
        {
            "name": "linusu",
            "email": "linus@folkdatorn.se"
        }
    ],
    "name": "source-map-support",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/evanw/node-source-map-support.git"
    },
    "scripts": {
        "build": "node build.js",
        "prepublish": "npm run build",
        "serve-tests": "http-server -p 1336",
        "test": "mocha"
    },
    "version": "0.4.14"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
