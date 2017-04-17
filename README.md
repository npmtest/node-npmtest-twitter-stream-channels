# test coverage for  [twitter-stream-channels (v1.0.0)](http://labs.topheman.com/twitter-stream-channels/)  [![npm package](https://img.shields.io/npm/v/npmtest-twitter-stream-channels.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-twitter-stream-channels) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-twitter-stream-channels.svg)](https://travis-ci.org/npmtest/node-npmtest-twitter-stream-channels)
#### Manage multiple filters on the same Twitter stream

[![NPM](https://nodei.co/npm/twitter-stream-channels.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/twitter-stream-channels)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-twitter-stream-channels/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-twitter-stream-channels/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-twitter-stream-channels/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-twitter-stream-channels/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-twitter-stream-channels/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-twitter-stream-channels/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-twitter-stream-channels/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-twitter-stream-channels/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-twitter-stream-channels/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-twitter-stream-channels/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-twitter-stream-channels/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-twitter-stream-channels/build/test-report.html](https://npmtest.github.io/node-npmtest-twitter-stream-channels/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-twitter-stream-channels/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-twitter-stream-channels/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-twitter-stream-channels/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-twitter-stream-channels/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-twitter-stream-channels/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-twitter-stream-channels/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-twitter-stream-channels/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-twitter-stream-channels/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Christophe Rosset"
    },
    "bugs": {
        "url": "https://github.com/topheman/twitter-stream-channels/issues"
    },
    "dependencies": {
        "twit": "^2.1.0"
    },
    "description": "Manage multiple filters on the same Twitter stream",
    "devDependencies": {
        "jasmine-node": "^1.14.5",
        "yuidocjs": "^0.9.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e5e9388aec9bf72254e2fe86930c301f7f0d74eb",
        "tarball": "https://registry.npmjs.org/twitter-stream-channels/-/twitter-stream-channels-1.0.0.tgz"
    },
    "gitHead": "4f740aeddd6ca2cc2492f9783addd3ad771bce46",
    "homepage": "http://labs.topheman.com/twitter-stream-channels/",
    "keywords": [
        "twitter",
        "api",
        "stream",
        "filter"
    ],
    "license": "MIT",
    "main": "./lib/TwitterStreamChannels",
    "maintainers": [
        {
            "name": "topheman"
        }
    ],
    "name": "twitter-stream-channels",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/topheman/twitter-stream-channels.git"
    },
    "scripts": {
        "test": "jasmine-node spec/offline --verbose --config highSpeed true",
        "test-online": "jasmine-node spec/online --verbose",
        "test-watch": "jasmine-node spec/offline --autotest --config highSpeed true --watch .",
        "yuidoc": "yuidoc"
    },
    "version": "1.0.0",
    "yuidoc": {
        "options": {
            "linkNatives": "true",
            "attributesEmit": "false",
            "selleck": "false",
            "paths": [
                "./lib",
                "./mocks"
            ],
            "outdir": "./yuidoc",
            "themedir": "./extras/yuidoc-theme-topheman"
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
