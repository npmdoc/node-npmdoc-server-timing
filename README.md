# npmdoc-server-timing

#### api documentation for  [server-timing (v1.1.0)](https://github.com/yosuke-furukawa/server-timing#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-server-timing.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-server-timing) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-server-timing.svg)](https://travis-ci.org/npmdoc/node-npmdoc-server-timing)

#### This module can add `ServerTiming` Header to http response, and be able to use express middleware

[![NPM](https://nodei.co/npm/server-timing.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/server-timing)

- [https://npmdoc.github.io/node-npmdoc-server-timing/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-server-timing/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-server-timing/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-server-timing/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-server-timing/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-server-timing/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "server-timing",
    "version": "1.1.0",
    "description": "This module can add 'ServerTiming' Header to http response, and be able to use express middleware",
    "main": "index.js",
    "scripts": {
        "test": "eater --require .loader.js",
        "lint": "standard",
        "cov": "nyc npm test",
        "coveralls": "npm run cov && nyc report --reporter=text-lcov | coveralls"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/yosuke-furukawa/server-timing.git"
    },
    "keywords": [
        "server-timing",
        "express",
        "middleware",
        "performance"
    ],
    "author": "yosuke-furukawa",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/yosuke-furukawa/server-timing/issues"
    },
    "homepage": "https://github.com/yosuke-furukawa/server-timing#readme",
    "dependencies": {
        "on-headers": "^1.0.1"
    },
    "devDependencies": {
        "assert-stream": "^1.1.1",
        "coveralls": "^2.11.16",
        "eater": "^3.2.0",
        "espower-loader": "^1.2.0",
        "express": "^4.14.1",
        "must-call": "^1.0.0",
        "nyc": "^10.1.2",
        "power-assert": "^1.4.2",
        "standard": "^8.6.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
