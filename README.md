# npmtest-electron-workers

#### basic test coverage for  [electron-workers (v1.10.1)](https://github.com/bjrmatos/electron-workers)  [![npm package](https://img.shields.io/npm/v/npmtest-electron-workers.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-electron-workers) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-electron-workers.svg)](https://travis-ci.org/npmtest/node-npmtest-electron-workers)

#### Run electron scripts in managed workers

[![NPM](https://nodei.co/npm/electron-workers.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-workers)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-electron-workers/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-workers/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-electron-workers/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-electron-workers/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-electron-workers/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-electron-workers/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-electron-workers/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-electron-workers/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-electron-workers/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron-workers/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-electron-workers/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-electron-workers/build/test-report.html](https://npmtest.github.io/node-npmtest-electron-workers/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-electron-workers/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-electron-workers/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-electron-workers/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-workers/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-workers/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-workers/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-electron-workers/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-electron-workers/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "electron-workers",
    "version": "1.10.1",
    "description": "Run electron scripts in managed workers",
    "main": "lib/index.js",
    "scripts": {
        "clean": "rimraf lib",
        "build": "babel src --out-dir lib",
        "lint": "eslint src test",
        "test": "mocha --timeout 9000",
        "prepublish": "in-publish && npm-run-all lint clean build || not-in-publish"
    },
    "author": {
        "name": "BJR Matos"
    },
    "license": "MIT",
    "keywords": [
        "electron",
        "headless",
        "workers",
        "electron spawn"
    ],
    "homepage": "https://github.com/bjrmatos/electron-workers",
    "repository": {
        "type": "git",
        "url": "git@github.com:bjrmatos/electron-workers.git"
    },
    "dependencies": {
        "debug": "2.3.3",
        "lodash.findindex": "4.6.0",
        "net-cluster": "0.0.2",
        "portscanner": "1.2.0",
        "uuid": "3.0.1",
        "which": "1.2.12"
    },
    "devDependencies": {
        "babel": "5.8.38",
        "electron": "1.4.12",
        "eslint": "2.13.1",
        "eslint-config-airbnb-base": "3.0.1",
        "eslint-plugin-import": "1.16.0",
        "in-publish": "2.0.0",
        "mocha": "2.5.3",
        "npm-run-all": "2.3.0",
        "rimraf": "2.5.4",
        "should": "9.0.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
