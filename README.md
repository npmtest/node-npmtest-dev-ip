# npmtest-dev-ip

#### basic test coverage for  [dev-ip (v1.0.1)](https://github.com/shakyshane/dev-ip)  [![npm package](https://img.shields.io/npm/v/npmtest-dev-ip.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-dev-ip) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-dev-ip.svg)](https://travis-ci.org/npmtest/node-npmtest-dev-ip)

#### Find a suitable IP host to view local websites on.

[![NPM](https://nodei.co/npm/dev-ip.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dev-ip)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-dev-ip/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-dev-ip/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-dev-ip/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-dev-ip/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-dev-ip/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-dev-ip/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-dev-ip/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-dev-ip/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-dev-ip/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-dev-ip/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-dev-ip/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-dev-ip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-dev-ip/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-dev-ip/build/test-report.html](https://npmtest.github.io/node-npmtest-dev-ip/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-dev-ip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-dev-ip/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-dev-ip/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dev-ip/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dev-ip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dev-ip/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-dev-ip/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-dev-ip/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Shane Osbourne"
    },
    "bin": {
        "dev-ip": "lib/dev-ip.js"
    },
    "bugs": {
        "url": "https://github.com/shakyshane/dev-ip/issues"
    },
    "dependencies": {},
    "description": "Find a suitable IP host to view local websites on.",
    "devDependencies": {
        "chai": "^1.10.0",
        "jshint": "^2.5.11",
        "mocha": "^2.1.0",
        "sinon": "^1.12.2"
    },
    "directories": {},
    "dist": {
        "shasum": "a76a3ed1855be7a012bb8ac16cb80f3c00dc28f0",
        "tarball": "https://registry.npmjs.org/dev-ip/-/dev-ip-1.0.1.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "faa2af88e4bb69eaa01148c3203aea1d82b45682",
    "homepage": "https://github.com/shakyshane/dev-ip",
    "keywords": [],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/shakyshane/dev-ip/blob/master/LICENSE-MIT"
        }
    ],
    "main": "lib/dev-ip",
    "maintainers": [
        {
            "name": "shakyshane"
        }
    ],
    "name": "dev-ip",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/shakyshane/dev-ip.git"
    },
    "scripts": {
        "lint": "jshint lib/*.js test/*.js",
        "test": "npm run lint && npm run unit",
        "unit": "mocha"
    },
    "version": "1.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
