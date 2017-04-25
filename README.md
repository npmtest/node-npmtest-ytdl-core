# npmtest-ytdl-core

#### basic test coverage for  [ytdl-core (v0.13.1)](https://github.com/fent/node-ytdl-core#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ytdl-core.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ytdl-core) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ytdl-core.svg)](https://travis-ci.org/npmtest/node-npmtest-ytdl-core)

#### Youtube video downloader in pure javascript.

[![NPM](https://nodei.co/npm/ytdl-core.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ytdl-core)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ytdl-core/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ytdl-core/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ytdl-core/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ytdl-core/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ytdl-core/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ytdl-core/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ytdl-core/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ytdl-core/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ytdl-core/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ytdl-core/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ytdl-core/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ytdl-core/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ytdl-core/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ytdl-core/build/test-report.html](https://npmtest.github.io/node-npmtest-ytdl-core/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ytdl-core/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ytdl-core/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ytdl-core/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ytdl-core/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ytdl-core/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ytdl-core/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ytdl-core/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ytdl-core/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Roly Fentanes",
        "url": "https://github.com/fent"
    },
    "bugs": {
        "url": "https://github.com/fent/node-ytdl-core/issues"
    },
    "contributors": [
        {
            "name": "Tobias Kutscha",
            "url": "https://github.com/TimeForANinja"
        },
        {
            "name": "Andrew Kelley",
            "url": "https://github.com/andrewrk"
        },
        {
            "name": "Mauricio Allende",
            "url": "https://github.com/mallendeo"
        },
        {
            "name": "Rodrigo Altamirano",
            "url": "https://github.com/raltamirano"
        },
        {
            "name": "Jim Buck",
            "url": "https://github.com/JimmyBoh"
        }
    ],
    "dependencies": {
        "html-entities": "^1.1.3",
        "m3u8stream": "^0.1.0",
        "miniget": "^1.0.0",
        "sax": "^1.1.3"
    },
    "description": "Youtube video downloader in pure javascript.",
    "devDependencies": {
        "@types/node": "^7.0.12",
        "assert-diff": "^1.0.1",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0",
        "muk-prop": "^1.0.0",
        "nock": "*",
        "sinon": "^2.0.0",
        "stream-equal": "~1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "213349566c832c298619ac72d3711394cc0fc335",
        "tarball": "https://registry.npmjs.org/ytdl-core/-/ytdl-core-0.13.1.tgz"
    },
    "engines": {
        "node": ">=0.12"
    },
    "files": [
        "lib",
        "typings"
    ],
    "gitHead": "dc012240b0bf2532b0365cb936e399c7d157adcd",
    "homepage": "https://github.com/fent/node-ytdl-core#readme",
    "keywords": [
        "youtube",
        "video",
        "download"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "fent"
        }
    ],
    "name": "ytdl-core",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/fent/node-ytdl-core.git"
    },
    "scripts": {
        "test": "istanbul cover node_modules/.bin/_mocha -- -t 16000 test/*-test.js"
    },
    "types": "./typings/index.d.ts",
    "version": "0.13.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
