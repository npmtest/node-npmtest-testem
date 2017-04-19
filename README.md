# npmtest-testem

#### basic test coverage for  [testem (v1.16.0)](https://github.com/testem/testem#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-testem.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-testem) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-testem.svg)](https://travis-ci.org/npmtest/node-npmtest-testem)

#### Test'em 'scripts! Javascript Unit testing made easy.

[![NPM](https://nodei.co/npm/testem.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/testem)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-testem/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-testem/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-testem/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-testem/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-testem/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-testem/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-testem/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-testem/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-testem/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-testem/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-testem/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-testem/build/test-report.html](https://npmtest.github.io/node-npmtest-testem/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-testem/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-testem/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-testem/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-testem/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-testem/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-testem/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-testem/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-testem/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Toby Ho"
    },
    "bin": {
        "testem": "./testem.js"
    },
    "bugs": {
        "url": "http://github.com/testem/testem/issues"
    },
    "dependencies": {
        "backbone": "^1.1.2",
        "bluebird": "^3.4.6",
        "charm": "^1.0.0",
        "commander": "^2.6.0",
        "consolidate": "^0.14.0",
        "cross-spawn": "^5.1.0",
        "express": "^4.10.7",
        "fireworm": "^0.7.0",
        "glob": "^7.0.4",
        "http-proxy": "^1.13.1",
        "js-yaml": "^3.2.5",
        "lodash.assignin": "^4.1.0",
        "lodash.clonedeep": "^4.4.1",
        "lodash.find": "^4.5.1",
        "lodash.uniqby": "^4.7.0",
        "mkdirp": "^0.5.1",
        "mustache": "^2.2.1",
        "node-notifier": "^5.0.1",
        "npmlog": "^4.0.0",
        "printf": "^0.2.3",
        "rimraf": "^2.4.4",
        "socket.io": "1.6.0",
        "spawn-args": "^0.2.0",
        "styled_string": "0.0.1",
        "tap-parser": "^5.1.0",
        "xmldom": "^0.1.19"
    },
    "description": "Test'em 'scripts! Javascript Unit testing made easy.",
    "devDependencies": {
        "bluebird-retry": "^0.9.0",
        "browserify": "^13.0.0",
        "chai": "^3.0.0",
        "chai-files": "^1.2.0",
        "chai-shallow-deep-equal": "^1.4.4",
        "cheerio": "^0.22.0",
        "dirty-chai": "^1.2.2",
        "eslint": "^3.2.2",
        "eslint-plugin-chai-expect": "^1.1.1",
        "eslint-plugin-mocha": "^4.3.0",
        "mocha": "^3.0.0",
        "request": "^2.51.0",
        "saucie": "^3.0.1",
        "shelljs": "^0.7.0",
        "sinon": "^1.17.2",
        "sinon-chai": "^2.8.0",
        "tape": "^4.0.0",
        "tmp": "0.0.31"
    },
    "directories": {},
    "dist": {
        "shasum": "3933040b5d5b5fbdb6a2b1e7032e511b54a05867",
        "tarball": "https://registry.npmjs.org/testem/-/testem-1.16.0.tgz"
    },
    "engines": [
        "node >= 0.8.0"
    ],
    "files": [
        "lib",
        "public",
        "README.md",
        "testem.js",
        "assets",
        "package.json",
        "views"
    ],
    "gitHead": "b3bc9896a3f68fe8b25c495881f5ef3807624b6e",
    "homepage": "https://github.com/testem/testem#readme",
    "keywords": [
        "javascript",
        "testing",
        "unittest",
        "browser"
    ],
    "license": "MIT",
    "main": "./lib/api.js",
    "maintainers": [
        {
            "name": "airportyh"
        },
        {
            "name": "johanneswuerbach"
        }
    ],
    "name": "testem",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/testem/testem.git"
    },
    "scripts": {
        "browser-tests": "cd examples/saucelabs/ && ../../testem.js ci -d",
        "cover": "cover run ./node_modules/.bin/_mocha tests/*_tests.js tests/**/*_tests.js; cover report html; open cover_html/index.html",
        "install:all": "npm install && npm install phantomjs-prebuilt",
        "integration": "node ./bin/run-integration.js",
        "lint": "eslint .",
        "test": "./bin/run-tests.js",
        "testem-tests": "mocha --opts tests/mocha.opts tests/*_tests.js tests/**/*_tests.js"
    },
    "version": "1.16.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
