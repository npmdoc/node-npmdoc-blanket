# api documentation for  [blanket (v1.2.3)](https://github.com/alex-seville/blanket)  [![npm package](https://img.shields.io/npm/v/npmdoc-blanket.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-blanket) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-blanket.svg)](https://travis-ci.org/npmdoc/node-npmdoc-blanket)
#### seamless js code coverage

[![NPM](https://nodei.co/npm/blanket.png?downloads=true)](https://www.npmjs.com/package/blanket)

[![apidoc](https://npmdoc.github.io/node-npmdoc-blanket/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-blanket_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-blanket/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-blanket/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-blanket/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alex-Seville",
        "email": "hi@alexanderseville.com",
        "url": "http://blanketjs.org"
    },
    "bugs": {
        "url": "https://github.com/alex-seville/blanket/issues"
    },
    "config": {
        "blanket": {
            "pattern": "test",
            "data-cover-flags": {
                "debug": false
            },
            "loader": "./node-loaders/coffee-script",
            "data-cover-reporter-options": {
                "shortnames": true
            }
        },
        "travis-cov": {
            "threshold": 70,
            "removeKey": "branchFcn"
        }
    },
    "dependencies": {
        "acorn": "^1.0.3",
        "falafel": "~1.2.0",
        "foreach": "^2.0.5",
        "isarray": "0.0.1",
        "object-keys": "^1.0.6",
        "xtend": "~4.0.0"
    },
    "description": "seamless js code coverage",
    "devDependencies": {
        "async": "~1.4.0",
        "coffee-react": "^4.0.0",
        "coffee-script": "~1.9.3",
        "grunt": "~0.4.5",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-clean": "~0.6.0",
        "grunt-contrib-concat": "~0.5.1",
        "grunt-contrib-jshint": "~0.11.2",
        "grunt-contrib-uglify": "~0.9.1",
        "load-grunt-tasks": "~3.2.0",
        "mocha": "~2.2.5",
        "phantomjs": "1.9.17",
        "react": "^0.13.3",
        "requirejs": "~2.1.19",
        "travis-cov": "*",
        "uglify-save-license": "~0.4.1"
    },
    "directories": {},
    "dist": {
        "shasum": "151b4987c3bd84552bb5f03b90ef5f7e5931e473",
        "tarball": "https://registry.npmjs.org/blanket/-/blanket-1.2.3.tgz"
    },
    "engines": {
        "node": ">=0.10.7"
    },
    "gitHead": "0155c14cf19bef4df2b175f8173ea467b644a3fe",
    "homepage": "https://github.com/alex-seville/blanket",
    "keywords": [
        "coverage"
    ],
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "alexseville",
            "email": "hi@alexanderseville.com"
        }
    ],
    "name": "blanket",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/alex-seville/blanket.git"
    },
    "scripts": {
        "build": "grunt build",
        "test": "grunt --verbose blanketTest"
    },
    "version": "1.2.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module blanket](#apidoc.module.blanket)



# <a name="apidoc.module.blanket"></a>[module blanket](#apidoc.module.blanket)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
