# api documentation for  [hotel (v0.7.1)](https://github.com/typicode/hotel)  [![npm package](https://img.shields.io/npm/v/npmdoc-hotel.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-hotel) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-hotel.svg)](https://travis-ci.org/npmdoc/node-npmdoc-hotel)
#### Local domains for everyone and more!

[![NPM](https://nodei.co/npm/hotel.png?downloads=true)](https://www.npmjs.com/package/hotel)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hotel/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-hotel_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hotel/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-hotel/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-hotel/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Typicode",
        "email": "typicode@gmail.com"
    },
    "ava": {
        "serial": true,
        "verbose": true,
        "require": [
            "babel-register"
        ],
        "babel": "inherit"
    },
    "bin": {
        "hotel": "lib/cli/bin.js"
    },
    "bugs": {
        "url": "https://github.com/typicode/hotel/issues"
    },
    "dependencies": {
        "after-all": "^2.0.2",
        "ansi2html": "0.0.1",
        "chalk": "^1.1.3",
        "chokidar": "^1.2.0",
        "connect-sse": "^1.2.0",
        "exit-hook": "^1.1.1",
        "express": "^4.13.3",
        "get-port": "^2.0.0",
        "http-proxy": "^1.16.2",
        "matcher": "^0.1.2",
        "mkdirp": "^0.5.1",
        "once": "^1.3.2",
        "respawn": "^2.4.1",
        "server-ready": "^0.3.1",
        "strip-ansi": "^3.0.0",
        "strip-indent": "^2.0.0",
        "sudo-block": "^1.2.0",
        "tildify": "^1.1.2",
        "unquote": "^1.1.0",
        "untildify": "^3.0.2",
        "update-notifier": "^1.0.0",
        "user-startup": "^0.2.1",
        "vhost": "^3.0.2",
        "yargs": "^6.3.0"
    },
    "description": "Local domains for everyone and more! ",
    "devDependencies": {
        "ava": "^0.18.2",
        "babel-cli": "^6.1.2",
        "babel-core": "^6.7.4",
        "babel-loader": "^6.2.4",
        "babel-plugin-transform-runtime": "^6.5.0",
        "babel-polyfill": "^6.9.1",
        "babel-preset-es2015": "^6.5.0",
        "babel-preset-stage-2": "^6.5.0",
        "babel-register": "^6.9.0",
        "babel-runtime": "^6.6.1",
        "cross-env": "^3.1.4",
        "css-loader": "^0.25.0",
        "escape-html": "^1.0.3",
        "husky": "^0.13.1",
        "json-loader": "^0.5.4",
        "lodash.difference": "^4.3.0",
        "mock-fs": "^3.9.0",
        "nodemon": "^1.8.1",
        "npm-run-all": "^3.1.0",
        "pkg-ok": "^1.0.1",
        "rimraf": "^2.5.2",
        "sinon": "^1.17.7",
        "standard": "^8.5.0",
        "supertest": "^2.0.1",
        "uid": "0.0.2",
        "vue": "^2.1.0",
        "vue-loader": "^10.0.0",
        "vue-template-compiler": "^2.1.10",
        "webpack": "^2.2.1",
        "whatwg-fetch": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "28d3626faf6c3d614e1330400bd00e79ddead567",
        "tarball": "https://registry.npmjs.org/hotel/-/hotel-0.7.1.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "gitHead": "3c1bfe7c564a148e68efa996f3147bb426d0d2f4",
    "homepage": "https://github.com/typicode/hotel",
    "keywords": [
        "dev",
        "utility",
        "process",
        "manager",
        "local",
        "server",
        "host",
        "proxy"
    ],
    "license": "MIT",
    "main": "lib",
    "maintainers": [
        {
            "name": "typicode",
            "email": "typicode@gmail.com"
        }
    ],
    "name": "hotel",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/typicode/hotel.git"
    },
    "scripts": {
        "build": "run-s build:*",
        "build:babel": "rimraf lib && babel src -d lib --copy-files --ignore src/front",
        "build:webpack": "rimraf dist && cross-env NODE_ENV=production webpack -p",
        "precommit": "npm test",
        "prepublish": "npm run build && pkg-ok",
        "start": "run-p start:*",
        "start:nodemon": "nodemon -- src/daemon",
        "start:webpack": "rimraf dist && webpack -d --watch",
        "test": "ava && standard --fix",
        "uninstall": "node bin/uninstall.js"
    },
    "version": "0.7.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module hotel](#apidoc.module.hotel)



# <a name="apidoc.module.hotel"></a>[module hotel](#apidoc.module.hotel)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
