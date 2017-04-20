# npmtest-chromedriver

#### basic test coverage for  [chromedriver (v2.29.0)](https://github.com/giggio/node-chromedriver)  [![npm package](https://img.shields.io/npm/v/npmtest-chromedriver.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-chromedriver) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-chromedriver.svg)](https://travis-ci.org/npmtest/node-npmtest-chromedriver)

#### ChromeDriver for Selenium

[![NPM](https://nodei.co/npm/chromedriver.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/chromedriver)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-chromedriver/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-chromedriver/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-chromedriver/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-chromedriver/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-chromedriver/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-chromedriver/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-chromedriver/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-chromedriver/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-chromedriver/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-chromedriver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-chromedriver/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-chromedriver/build/test-report.html](https://npmtest.github.io/node-npmtest-chromedriver/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-chromedriver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-chromedriver/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-chromedriver/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-chromedriver/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-chromedriver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-chromedriver/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-chromedriver/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-chromedriver/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "chromedriver",
    "version": "2.29.0",
    "keywords": [
        "chromedriver",
        "selenium"
    ],
    "description": "ChromeDriver for Selenium",
    "homepage": "https://github.com/giggio/node-chromedriver",
    "repository": {
        "type": "git",
        "url": "git://github.com/giggio/node-chromedriver.git"
    },
    "licenses": [
        {
            "type": "Apache 2.0",
            "url": "http://www.apache.org/licenses/LICENSE-2.0.html"
        }
    ],
    "author": {
        "name": "Giovanni Bassi",
        "url": "http://www.lambda3.com.br"
    },
    "main": "lib/chromedriver",
    "bin": {
        "chromedriver": "./bin/chromedriver"
    },
    "scripts": {
        "install": "node install.js"
    },
    "dependencies": {
        "adm-zip": "^0.4.7",
        "kew": "^0.7.0",
        "mkdirp": "^0.5.1",
        "rimraf": "^2.5.4"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
