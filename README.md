# npmtest-babel-plugin-react-transform

#### test coverage for  [babel-plugin-react-transform (v2.0.2)](https://github.com/gaearon/babel-plugin-react-transform#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-babel-plugin-react-transform.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-babel-plugin-react-transform) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-babel-plugin-react-transform.svg)](https://travis-ci.org/npmtest/node-npmtest-babel-plugin-react-transform)

#### Babel plugin to instrument React components with custom transforms

[![NPM](https://nodei.co/npm/babel-plugin-react-transform.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babel-plugin-react-transform)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-babel-plugin-react-transform/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-plugin-react-transform/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-babel-plugin-react-transform/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-babel-plugin-react-transform/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-babel-plugin-react-transform/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-babel-plugin-react-transform/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-babel-plugin-react-transform/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-babel-plugin-react-transform/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-babel-plugin-react-transform/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-plugin-react-transform/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-babel-plugin-react-transform/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-babel-plugin-react-transform/build/test-report.html](https://npmtest.github.io/node-npmtest-babel-plugin-react-transform/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-babel-plugin-react-transform/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-babel-plugin-react-transform/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-babel-plugin-react-transform/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-babel-plugin-react-transform/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babel-plugin-react-transform/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babel-plugin-react-transform/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-babel-plugin-react-transform/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-babel-plugin-react-transform/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dan Abramov"
    },
    "bugs": {
        "url": "https://github.com/gaearon/babel-plugin-react-transform/issues"
    },
    "dependencies": {
        "lodash": "^4.6.1"
    },
    "description": "Babel plugin to instrument React components with custom transforms",
    "devDependencies": {
        "babel-cli": "^6.2.0",
        "babel-core": "^6.2.1",
        "babel-eslint": "^4.1.6",
        "babel-preset-es2015": "^6.1.18",
        "babel-register": "^6.2.0",
        "eslint": "^1.10.3",
        "eslint-plugin-react": "^3.11.2",
        "mocha": "^2.2.5",
        "rimraf": "^2.4.3"
    },
    "directories": {},
    "dist": {
        "shasum": "515bbfa996893981142d90b1f9b1635de2995109",
        "tarball": "https://registry.npmjs.org/babel-plugin-react-transform/-/babel-plugin-react-transform-2.0.2.tgz"
    },
    "gitHead": "827843e1da56b1edbd4f9e526339d9968ada652d",
    "homepage": "https://github.com/gaearon/babel-plugin-react-transform#readme",
    "keywords": [
        "babel-plugin",
        "react-transform",
        "instrumentation",
        "dx",
        "react",
        "reactjs",
        "components"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "gaearon"
        },
        {
            "name": "thejameskyle"
        }
    ],
    "name": "babel-plugin-react-transform",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gaearon/babel-plugin-react-transform.git"
    },
    "scripts": {
        "build": "babel src -d lib",
        "clean": "rimraf lib",
        "prepublish": "npm run clean && npm run build",
        "test": "mocha --compilers js:babel-register",
        "test:watch": "npm run test -- --watch"
    },
    "version": "2.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
