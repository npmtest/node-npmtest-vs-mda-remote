# npmtest-vs-mda-remote

#### basic test coverage for  [vs-mda-remote (v0.2.13)](http://msdn.microsoft.com/en-us/vstudio/dn722381)  [![npm package](https://img.shields.io/npm/v/npmtest-vs-mda-remote.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vs-mda-remote) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vs-mda-remote.svg)](https://travis-ci.org/npmtest/node-npmtest-vs-mda-remote)

#### OSX agent to remotely build, run, and debug iOS apps created using Visual Studio Tools for Apache Cordova.

[![NPM](https://nodei.co/npm/vs-mda-remote.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vs-mda-remote)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vs-mda-remote/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vs-mda-remote/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vs-mda-remote/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vs-mda-remote/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vs-mda-remote/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vs-mda-remote/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vs-mda-remote/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vs-mda-remote/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vs-mda-remote/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vs-mda-remote/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vs-mda-remote/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vs-mda-remote/build/test-report.html](https://npmtest.github.io/node-npmtest-vs-mda-remote/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vs-mda-remote/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vs-mda-remote/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vs-mda-remote/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vs-mda-remote/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vs-mda-remote/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vs-mda-remote/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vs-mda-remote/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vs-mda-remote/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "vs-mda-remote",
    "description": "OSX agent to remotely build, run, and debug iOS apps created using Visual Studio Tools for Apache Cordova.",
    "version": "0.2.13",
    "author": {
        "name": "Microsoft Corporation"
    },
    "homepage": "http://msdn.microsoft.com/en-us/vstudio/dn722381",
    "main": "./lib/server.js",
    "bin": {
        "vs-mda-remote": "./bin/vs-mda-remote"
    },
    "os": [
        "darwin"
    ],
    "preferGlobal": true,
    "dependencies": {
        "express": "3.4.8",
        "request": "2.36.0",
        "tar": "0.1.20",
        "fstream": "0.1.28",
        "zip-stream": "0.2.3",
        "nconf": "0.6.9",
        "q": "1.0.1",
        "elementtree": "0.1.6",
        "semver": "2.3.1",
        "optimist": "0.6.1",
        "rimraf": "2.2.6",
        "mkdirp": "0.3.5",
        "ncp": "0.5.1",
        "plist-with-patches": "0.5.1",
        "ios-sim": "2.0.1",
        "readline-sync": "0.4.9",
        "unorm": "1.3.3"
    },
    "devDependencies": {
        "mocha": "2.0.1"
    },
    "scripts": {
        "test": "mocha test",
        "preinstall": "echo \"Enabling Developer mode on Mac. Enter an administrator password if prompted.\" && (DevToolsSecurity -enable || true)"
    },
    "directories": {
        "lib": "lib",
        "doc": ".",
        "test": "test",
        "example": "examples"
    },
    "readmeFilename": "README.md"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
