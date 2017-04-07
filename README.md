# api documentation for  [npm-gui (v0.3.1)](https://github.com/q-nick/npm-gui#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-npm-gui.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-npm-gui) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-npm-gui.svg)](https://travis-ci.org/npmdoc/node-npmdoc-npm-gui)
#### Graphic User Interface for NPM packages/tasks for front and back -end users.

[![NPM](https://nodei.co/npm/npm-gui.png?downloads=true)](https://www.npmjs.com/package/npm-gui)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-gui/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-npm-gui_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-gui/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-npm-gui/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-npm-gui/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Paweł Stefański"
    },
    "bin": {
        "npm-gui": "bin/npm-gui"
    },
    "bugs": {
        "url": "https://github.com/q-nick/npm-gui/issues"
    },
    "dependencies": {
        "nsp": "^2.4.0"
    },
    "description": "Graphic User Interface for NPM packages/tasks for front and back -end users.",
    "devDependencies": {
        "angular": "^1.5.5",
        "angular-animate": "^1.5.5",
        "angular-route": "^1.5.5",
        "angular-ui-bootstrap": "^0.14.3",
        "angular-websocket": "^1.1.0",
        "bluebird": "^3.4.0",
        "body-parser": "^1.15.1",
        "chai": "^3.5.0",
        "cross-spawn": "^4.0.0",
        "electron-prebuilt": "^1.1.1",
        "express": "^4.13.4",
        "json-loader": "^0.5.4",
        "mocha": "^2.5.1",
        "ng-annotate-webpack-plugin": "^0.1.2",
        "rewire": "^2.5.1",
        "sinon": "^1.17.4",
        "sinon-stub-promise": "^2.0.0",
        "supertest": "^1.2.0",
        "uglify-js": "^2.6.2",
        "webpack": "^1.13.1",
        "ws": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "dfc06ee439816bbb35c7ce04be24c0d2e06e1694",
        "tarball": "https://registry.npmjs.org/npm-gui/-/npm-gui-0.3.1.tgz"
    },
    "gitHead": "fbd68a9a52cb2827d1d013b2d6d5ec1cf9f0070a",
    "homepage": "https://github.com/q-nick/npm-gui#readme",
    "keywords": [
        "gui",
        "npm",
        "view",
        "client",
        "task",
        "runner",
        "dependencies",
        "installer",
        "console"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "q-nick",
            "email": "qnick.mail@gmail.com"
        }
    ],
    "name": "npm-gui",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/q-nick/npm-gui.git"
    },
    "scripts": {
        "app": "node bin/npm-gui-app",
        "build": "node node_modules/webpack/bin/webpack.js -p --config webpack.client.config.js && node node_modules/webpack/bin/webpack.js -p --config webpack.server.config.js",
        "dev": "node node_modules/webpack/bin/webpack.js -p --config webpack.server.config.js && node bin/npm-gui 0.0.0.0:9001 & node node_modules/webpack/bin/webpack.js --progress --colors --watch --config webpack.client.config.js",
        "start": "node bin/npm-gui",
        "test": "node node_modules/mocha/bin/mocha ./lib/modules/**/*.js ./lib/helpers/**/*.js && node node_modules/mocha/bin/mocha responses.test.js"
    },
    "version": "0.3.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module npm-gui](#apidoc.module.npm-gui)



# <a name="apidoc.module.npm-gui"></a>[module npm-gui](#apidoc.module.npm-gui)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
