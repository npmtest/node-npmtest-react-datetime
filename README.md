# npmtest-react-datetime

#### basic test coverage for  [react-datetime (v2.8.9)](https://github.com/YouCanBookMe/react-datetime)  [![npm package](https://img.shields.io/npm/v/npmtest-react-datetime.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-datetime) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-datetime.svg)](https://travis-ci.org/npmtest/node-npmtest-react-datetime)

#### A lightweight but complete datetime picker React.js component.

[![NPM](https://nodei.co/npm/react-datetime.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-datetime)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-datetime/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-datetime/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-datetime/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-datetime/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-datetime/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-datetime/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-datetime/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-datetime/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-datetime/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-datetime/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-datetime/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-datetime/build/test-report.html](https://npmtest.github.io/node-npmtest-react-datetime/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-datetime/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-datetime/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-datetime/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-datetime/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-datetime/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-datetime/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-datetime/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-datetime/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Javier Marquez"
    },
    "bugs": {
        "url": "https://github.com/YouCanBookMe/react-datetime/issues"
    },
    "dependencies": {
        "object-assign": "^3.0.0",
        "react-onclickoutside": "^5.9.0"
    },
    "description": "A lightweight but complete datetime picker React.js component.",
    "devDependencies": {
        "@types/react": "^0.14.49",
        "babel-core": "^6.22.1",
        "babel-jest": "^18.0.0",
        "babel-loader": "^6.2.1",
        "babel-plugin-transform-remove-strict-mode": "0.0.2",
        "babel-preset-es2015": "^6.22.0",
        "babel-preset-react": "^6.22.0",
        "enzyme": "^2.7.1",
        "eslint": "^3.1.0",
        "gulp": "^3.9.0",
        "gulp-babel": "^6.1",
        "gulp-insert": "^0.4.0",
        "gulp-plumber": "^1.1.0",
        "gulp-rename": "^1.2.2",
        "gulp-sourcemaps": "^2.4.0",
        "gulp-uglify": "^1.2.0",
        "jest": "^18.1.0",
        "jest-cli": "^18.1.0",
        "jsdom": "^7.0.2",
        "mocha": "^3.2.0",
        "moment": ">=2.16.0",
        "pre-commit": "^1.1.3",
        "react": ">=0.13",
        "react-addons-test-utils": ">=0.13",
        "react-dom": ">=0.13",
        "react-test-renderer": "^15.4.2",
        "through2": "^2.0.3",
        "typescript": "^2.0.10",
        "webpack": "^2.2.1",
        "webpack-dev-server": "^1.7.0",
        "webpack-stream": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "52f3a1a28b0e34146664c057d480c80b33d39793",
        "tarball": "https://registry.npmjs.org/react-datetime/-/react-datetime-2.8.9.tgz"
    },
    "files": [
        "DateTime.js",
        "react-datetime.d.ts",
        "typings/index.d.ts",
        "src",
        "css",
        "dist"
    ],
    "gitHead": "e609a12ba958f009a742ee160152fb18b940b6b1",
    "homepage": "https://github.com/YouCanBookMe/react-datetime",
    "keywords": [
        "react",
        "react-component",
        "datepicker",
        "timepicker",
        "datetimepicker",
        "datetime"
    ],
    "license": "MIT",
    "main": "./DateTime.js",
    "maintainers": [
        {
            "name": "arqex"
        },
        {
            "name": "simeg"
        }
    ],
    "name": "react-datetime",
    "optionalDependencies": {},
    "peerDependencies": {
        "moment": ">=2.16.0",
        "react": ">=0.13",
        "react-dom": ">=0.13"
    },
    "pre-commit": [
        "lint",
        "test:all"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/YouCanBookMe/react-datetime.git"
    },
    "scripts": {
        "build:mac": "gulp",
        "build:win": "gulp.cmd",
        "dev": "webpack-dev-server --config example/webpack.config.js --devtool eval --progress --colors --hot --content-base example",
        "lint": "eslint src/ DateTime.js tests/",
        "test": "jest",
        "test:all": "npm run test:typings && npm run test",
        "test:typings": "tsc -p ./typings",
        "test:watch": "jest --watch"
    },
    "types": "./typings/index.d.ts",
    "version": "2.8.9",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
