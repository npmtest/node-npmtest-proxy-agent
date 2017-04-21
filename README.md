# npmtest-proxy-agent

#### basic test coverage for  [proxy-agent (v2.0.0)](https://github.com/TooTallNate/node-proxy-agent)  [![npm package](https://img.shields.io/npm/v/npmtest-proxy-agent.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-proxy-agent) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-proxy-agent.svg)](https://travis-ci.org/npmtest/node-npmtest-proxy-agent)

#### Maps proxy protocols to `http.Agent` implementations

[![NPM](https://nodei.co/npm/proxy-agent.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/proxy-agent)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-proxy-agent/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-proxy-agent/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-proxy-agent/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-proxy-agent/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-proxy-agent/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-proxy-agent/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-proxy-agent/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-proxy-agent/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-proxy-agent/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-proxy-agent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-proxy-agent/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-proxy-agent/build/test-report.html](https://npmtest.github.io/node-npmtest-proxy-agent/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-proxy-agent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-proxy-agent/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-proxy-agent/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-proxy-agent/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-proxy-agent/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-proxy-agent/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-proxy-agent/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-proxy-agent/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "proxy-agent",
    "version": "2.0.0",
    "description": "Maps proxy protocols to 'http.Agent' implementations",
    "main": "index.js",
    "scripts": {
        "test": "mocha --reporter spec"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/TooTallNate/node-proxy-agent.git"
    },
    "keywords": [
        "http",
        "https",
        "socks",
        "agent",
        "mapping",
        "proxy",
        "cache"
    ],
    "author": "Nathan Rajlich <nathan@tootallnate.net> (http://n8.io/)",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/TooTallNate/node-proxy-agent/issues"
    },
    "homepage": "https://github.com/TooTallNate/node-proxy-agent",
    "dependencies": {
        "agent-base": "2",
        "debug": "2",
        "extend": "3",
        "http-proxy-agent": "1",
        "https-proxy-agent": "1",
        "lru-cache": "~2.6.5",
        "pac-proxy-agent": "1",
        "socks-proxy-agent": "2"
    },
    "devDependencies": {
        "mocha": "2",
        "proxy": "0.2.3",
        "socksv5": "0.0.6",
        "stream-to-buffer": "0.1.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
