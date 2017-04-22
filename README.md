# npmdoc-jdbc

#### api documentation for  [jdbc (v0.5.0)](https://github.com/CraZySacX/node-jdbc#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-jdbc.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jdbc) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jdbc.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jdbc)

#### Node Module JDBC wrapper

[![NPM](https://nodei.co/npm/jdbc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jdbc)

- [https://npmdoc.github.io/node-npmdoc-jdbc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jdbc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jdbc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jdbc/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jdbc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jdbc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jason Ozias"
    },
    "bugs": {
        "url": "https://github.com/CraZySacX/node-jdbc/issues"
    },
    "dependencies": {
        "async": "~2.2.0",
        "java": "^0.8.0",
        "lodash": "~4.17",
        "uuid": "^3.0.1",
        "winston": "^2.3.1"
    },
    "description": "Node Module JDBC wrapper",
    "devDependencies": {
        "jshint": "~2.9",
        "lolex": "^1.6.0",
        "nodeunit": "~0.11",
        "q": "^1.5.0"
    },
    "directories": {
        "doc": ".",
        "lib": "lib"
    },
    "dist": {
        "shasum": "7b918c3d3c5a01e3e82e589ba15f6948a0089b69",
        "tarball": "https://registry.npmjs.org/jdbc/-/jdbc-0.5.0.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "9b262691a17fd457a4e12d374a5518534c9d5077",
    "homepage": "https://github.com/CraZySacX/node-jdbc#readme",
    "keywords": [
        "node",
        "jdbc",
        "wrapper"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jozias"
        }
    ],
    "name": "jdbc",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/CraZySacX/node-jdbc.git"
    },
    "scripts": {
        "lint": "jshint lib/**.js test/**.js",
        "posttest": "bash bin/stopdbs",
        "pretest": "bash bin/startdbs",
        "test": "nodeunit test"
    },
    "version": "0.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
