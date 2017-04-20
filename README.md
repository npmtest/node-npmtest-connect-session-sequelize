# npmtest-connect-session-sequelize

#### basic test coverage for  [connect-session-sequelize (v4.1.0)](https://github.com/mweibel/connect-session-sequelize)  [![npm package](https://img.shields.io/npm/v/npmtest-connect-session-sequelize.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-connect-session-sequelize) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-connect-session-sequelize.svg)](https://travis-ci.org/npmtest/node-npmtest-connect-session-sequelize)

#### Session store for connect-session using sequelize

[![NPM](https://nodei.co/npm/connect-session-sequelize.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/connect-session-sequelize)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-connect-session-sequelize/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-connect-session-sequelize/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-connect-session-sequelize/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-connect-session-sequelize/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-connect-session-sequelize/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-connect-session-sequelize/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-connect-session-sequelize/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-connect-session-sequelize/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-connect-session-sequelize/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-connect-session-sequelize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-connect-session-sequelize/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-connect-session-sequelize/build/test-report.html](https://npmtest.github.io/node-npmtest-connect-session-sequelize/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-connect-session-sequelize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-connect-session-sequelize/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-connect-session-sequelize/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-connect-session-sequelize/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-connect-session-sequelize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-connect-session-sequelize/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-connect-session-sequelize/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-connect-session-sequelize/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "connect-session-sequelize",
    "version": "4.1.0",
    "description": "Session store for connect-session using sequelize",
    "homepage": "https://github.com/mweibel/connect-session-sequelize",
    "bugs": "https://github.com/mweibel/connect-session-sequelize/issues",
    "main": "index.js",
    "scripts": {
        "test": "mocha ./test",
        "lint": "standard"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/mweibel/connect-session-sequelize.git"
    },
    "dependencies": {
        "debug": "^2.1.1",
        "deep-equal": "^1.0.1"
    },
    "devDependencies": {
        "express-session": "^1.10.3",
        "mocha": "^3.0.0",
        "sequelize": ">=3.24.5",
        "sqlite3": "^3.1.4",
        "standard": "^8.2.0"
    },
    "peerDependencies": {
        "sequelize": ">= 3.24.5"
    },
    "engines": {
        "node": "*"
    },
    "keywords": [
        "connect-session",
        "connect",
        "sequelize",
        "postgres",
        "mysql",
        "sqlite"
    ],
    "author": "Michael Weibel <michael.weibel@gmail.com> (https://github.com/mweibel)",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
