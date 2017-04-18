# npmtest-react-select

#### test coverage for  [react-select (v0.9.1)](https://github.com/JedWatson/react-select#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-select.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-select) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-select.svg)](https://travis-ci.org/npmtest/node-npmtest-react-select)

#### A Select control built with and for ReactJS

[![NPM](https://nodei.co/npm/react-select.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-select)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-select/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-select/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-select/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-select/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-select/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-select/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-select/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-select/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-select/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-select/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-select/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-select/build/test-report.html](https://npmtest.github.io/node-npmtest-react-select/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-select/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-select/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-select/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-select/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-select/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-select/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-select/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-select/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jed Watson"
    },
    "browserify-shim": {
        "classnames": "global:classNames",
        "react": "global:React",
        "react-input-autosize": "global:AutosizeInput"
    },
    "bugs": {
        "url": "https://github.com/JedWatson/react-select/issues"
    },
    "dependencies": {
        "classnames": "^2.2.0",
        "react-input-autosize": "^0.6.2"
    },
    "description": "A Select control built with and for ReactJS",
    "devDependencies": {
        "babel": "^5.8.23",
        "babel-eslint": "^4.1.3",
        "chai": "^3.4.0",
        "coveralls": "^2.11.4",
        "eslint": "^1.8.0",
        "eslint-plugin-react": "^3.6.3",
        "gulp": "^3.9.0",
        "istanbul": "^0.4.0",
        "jsdom": "^7.0.2",
        "mocha": "^2.3.3",
        "react": "^0.14.1",
        "react-addons-test-utils": "^0.14.1",
        "react-component-gulp-tasks": "^0.7.7",
        "react-dom": "^0.14.1",
        "react-gravatar": "^2.2.2",
        "sinon": "^1.17.2",
        "unexpected": "^10.0.2",
        "unexpected-dom": "^3.0.2",
        "unexpected-sinon": "^8.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e322a2d0a06396a48206b0553df5ec47d16083ba",
        "tarball": "https://registry.npmjs.org/react-select/-/react-select-0.9.1.tgz"
    },
    "gitHead": "d8fe544f32dc28e1f72592671f7c70bddae3258a",
    "homepage": "https://github.com/JedWatson/react-select#readme",
    "keywords": [
        "combobox",
        "form",
        "input",
        "multiselect",
        "react",
        "react-component",
        "select",
        "ui"
    ],
    "license": "MIT",
    "main": "lib/Select.js",
    "maintainers": [
        {
            "name": "jedwatson"
        }
    ],
    "name": "react-select",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.1",
        "react-dom": "^0.14.1"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/JedWatson/react-select.git"
    },
    "scripts": {
        "build": "gulp clean && NODE_ENV=production gulp build",
        "bump": "gulp bump",
        "bump:major": "gulp bump:major",
        "bump:minor": "gulp bump:minor",
        "cover": "istanbul cover _mocha -- -u exports --compilers js:babel/register -R spec",
        "coveralls": "NODE_ENV=test istanbul cover _mocha --report lcovonly -- -u exports --compilers js:babel/register -R spec && cat coverage/lcov.info | coveralls",
        "examples": "gulp dev:server",
        "lint": "eslint .",
        "publish:examples": "NODE_ENV=production gulp publish:examples",
        "release": "NODE_ENV=production gulp release",
        "start": "gulp dev",
        "test": "mocha --compilers js:babel/register",
        "watch": "gulp watch:lib"
    },
    "style": "dist/default.css",
    "version": "0.9.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
