# npmtest-pmx

#### basic test coverage for  pmx (v1.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-pmx.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pmx) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pmx.svg)](https://travis-ci.org/npmtest/node-npmtest-pmx)

#### PM2/Keymetrics advanced API

[![NPM](https://nodei.co/npm/pmx.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pmx)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pmx/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pmx/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pmx/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pmx/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pmx/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pmx/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pmx/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pmx/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pmx/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pmx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pmx/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pmx/build/test-report.html](https://npmtest.github.io/node-npmtest-pmx/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pmx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pmx/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pmx/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pmx/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pmx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pmx/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pmx/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pmx/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pmx",
    "version": "1.1.0",
    "description": "PM2/Keymetrics advanced API",
    "main": "index.js",
    "dependencies": {
        "debug": "^2.6",
        "json-stringify-safe": "^5.0",
        "vxx": "^1.1.1"
    },
    "devDependencies": {
        "express": "*",
        "request": "*",
        "should": "*",
        "mocha": "*",
        "shelljs": "*",
        "pm2": "Unitech/pm2#development",
        "pm2-axon": "*",
        "nssocket": "*",
        "mongoose": "*"
    },
    "scripts": {
        "test": "DEBUG='axm:*' mocha test/*.mocha.js"
    },
    "keywords": [
        "cli",
        "fault tolerant",
        "sysadmin",
        "tools",
        "pm2",
        "logs",
        "log",
        "json",
        "express",
        "hapi",
        "kraken",
        "reload",
        "microservice",
        "programmatic",
        "harmony",
        "node-pm2",
        "production",
        "keymetrics",
        "node.js monitoring",
        "strong-pm",
        "deploy",
        "deployment",
        "daemon",
        "supervisor",
        "nodemon",
        "pm2.io",
        "ghost",
        "ghost production",
        "monitoring",
        "process manager",
        "forever",
        "profiling",
        "probes",
        "process-metrics",
        "process metrics",
        "metrics",
        "custom actions",
        "forever-monitor",
        "keep process alive",
        "process configuration",
        "clustering",
        "cluster cli",
        "cluster",
        "cron",
        "devops",
        "dev ops"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/keymetrics/pmx.git"
    },
    "author": "Keymetrics I/O",
    "license": "MIT",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
