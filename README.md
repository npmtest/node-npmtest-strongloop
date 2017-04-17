# test coverage for  [strongloop (v6.0.3)](http://www.strongloop.com)  [![npm package](https://img.shields.io/npm/v/npmtest-strongloop.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-strongloop) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-strongloop.svg)](https://travis-ci.org/npmtest/node-npmtest-strongloop)
#### StrongLoop Command Line Tools

[![NPM](https://nodei.co/npm/strongloop.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/strongloop)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-strongloop/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-strongloop/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-strongloop/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-strongloop/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-strongloop/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-strongloop/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-strongloop/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-strongloop/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-strongloop/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-strongloop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-strongloop/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-strongloop/build/test-report.html](https://npmtest.github.io/node-npmtest-strongloop/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-strongloop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-strongloop/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-strongloop/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-strongloop/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-strongloop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-strongloop/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-strongloop/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-strongloop/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "engineering@strongloop.com"
    },
    "bin": {
        "slc": "./bin/slc.js",
        "lb-ng": "./node_modules/loopback-sdk-angular-cli/bin/lb-ng.js"
    },
    "bugs": {
        "url": "https://github.com/strongloop/strongloop/issues"
    },
    "dependencies": {
        "JSONStream": "^1.0.3",
        "async": "^0.9.0",
        "bufferutil": "^1.2.1",
        "core-util-is": "^1.0.1",
        "d3": "^3.5.6",
        "debug": "^2.1.0",
        "generator-loopback": "1.x",
        "heapdump": "^0.3.7",
        "inherits": "^2.0.1",
        "less": "~1.4.0",
        "lodash": "^3.10.1",
        "loopback": "^2.17.0",
        "loopback-datasource-juggler": "^2.41.0",
        "loopback-sdk-angular-cli": "^2.1.0",
        "mime-db": "^1.19.0",
        "modern-syslog": "^1.1.2",
        "moment": "^2.10.0",
        "node-inspector": "~0.7.0",
        "nodefly-register": "~0.3.2",
        "nopt": "~3.0.1",
        "optimist": "^0.6.1",
        "read": "~1.0.5",
        "readable-stream": "^2.0.3",
        "spawn-sync": "^1.0.13",
        "sqlite3": "3.1.4",
        "strong-agent": "^2.0.0",
        "strong-arc": "^1.2.0",
        "strong-build": "^2.0.0",
        "strong-debugger": "^1.0.0",
        "strong-deploy": "^3.x",
        "strong-mesh-models": "^8.0.0",
        "strong-pm": "^5.0.0",
        "strong-registry": "^1.0.0",
        "strong-remoting": "^2.0.0",
        "strong-start": "^1.1.0",
        "strong-supervisor": "^3.0.0",
        "strong-swagger-ui": "^21.0.1",
        "swagger-ui": "^2.1.3",
        "utf-8-validate": "^1.2.1",
        "which": "^1.1.1",
        "wrappy": "1.0.1",
        "ws": "^0.8.0"
    },
    "description": "StrongLoop Command Line Tools",
    "devDependencies": {
        "eslint": "^1.1.0",
        "jscs": "^1.11.3",
        "tap": "^1.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "d2aa15eb430850ef3267a511575e13b677d0cd8e",
        "tarball": "https://registry.npmjs.org/strongloop/-/strongloop-6.0.3.tgz"
    },
    "gitHead": "1f8de8496e004487d12a2faf273cc1779c37f5b4",
    "homepage": "http://www.strongloop.com",
    "keywords": [
        "Backend",
        "LoopBack",
        "Mobile",
        "Platform",
        "StrongLoop",
        "alerts",
        "analytics",
        "agent",
        "apm",
        "build",
        "bundle",
        "cluster",
        "config",
        "dependencies",
        "deploy",
        "devops",
        "event loop",
        "forever",
        "git",
        "heap",
        "heroku",
        "logging",
        "mBaaS",
        "manager",
        "master",
        "memory",
        "metrics",
        "monitoring",
        "nodeops",
        "npm",
        "npmrc",
        "openshift",
        "ops",
        "performance",
        "pm",
        "process",
        "profiler",
        "profiling",
        "registry",
        "response",
        "runner",
        "service",
        "slc",
        "slowest functions",
        "streams",
        "strong-agent",
        "strong-cli",
        "strong-cluster-control",
        "strong-pm",
        "strong-supervisor",
        "strongloop",
        "strongops",
        "supervisor",
        "switch",
        "time",
        "upstart"
    ],
    "license": "Artistic-2.0",
    "maintainers": [
        {
            "name": "bajtos"
        },
        {
            "name": "chandadharap"
        },
        {
            "name": "ibmcloud-admin"
        },
        {
            "name": "kraman"
        },
        {
            "name": "octet"
        },
        {
            "name": "rfeng"
        },
        {
            "name": "ritch"
        },
        {
            "name": "rmg"
        },
        {
            "name": "setogit"
        },
        {
            "name": "strongloop"
        },
        {
            "name": "superkhau"
        }
    ],
    "name": "strongloop",
    "optionalDependencies": {
        "JSONStream": "^1.0.3",
        "bufferutil": "^1.2.1",
        "core-util-is": "^1.0.1",
        "d3": "^3.5.6",
        "heapdump": "^0.3.7",
        "inherits": "^2.0.1",
        "less": "~1.4.0",
        "lodash": "^3.10.1",
        "loopback": "^2.17.0",
        "loopback-datasource-juggler": "^2.41.0",
        "mime-db": "^1.19.0",
        "modern-syslog": "^1.1.2",
        "moment": "^2.10.0",
        "readable-stream": "^2.0.3",
        "spawn-sync": "^1.0.13",
        "sqlite3": "3.1.4",
        "strong-debugger": "^1.0.0",
        "strong-remoting": "^2.0.0",
        "strong-swagger-ui": "^21.0.1",
        "swagger-ui": "^2.1.3",
        "utf-8-validate": "^1.2.1",
        "wrappy": "1.0.1",
        "ws": "^0.8.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/strongloop/strongloop.git"
    },
    "scripts": {
        "pretest": "eslint --ignore-path .gitignore . && jscs .",
        "test": "tap --bail test/test-*.*"
    },
    "version": "6.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
