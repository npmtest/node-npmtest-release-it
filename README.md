# npmtest-release-it

#### test coverage for  [release-it (v2.7.1)](https://github.com/webpro/release-it#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-release-it.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-release-it) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-release-it.svg)](https://travis-ci.org/npmtest/node-npmtest-release-it)

#### Interactive release tool for Git repositories. Increment version, commit, tag, push, build, publish to npm. Supports to build and release to a distribution/component repository.

[![NPM](https://nodei.co/npm/release-it.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/release-it)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-release-it/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-release-it/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-release-it/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-release-it/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-release-it/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-release-it/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-release-it/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-release-it/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-release-it/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-release-it/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-release-it/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-release-it/build/test-report.html](https://npmtest.github.io/node-npmtest-release-it/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-release-it/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-release-it/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-release-it/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-release-it/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-release-it/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-release-it/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-release-it/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-release-it/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lars Kappert"
    },
    "bin": {
        "release-it": "./bin/release.js"
    },
    "bugs": {
        "url": "https://github.com/webpro/release-it/issues"
    },
    "dependencies": {
        "chalk": "1.1.3",
        "github": "9.1.0",
        "glob": "7.1.1",
        "graceful-fs": "4.1.11",
        "inquirer": "3.0.6",
        "lodash": "4.17.4",
        "minimist": "1.2.0",
        "mkdirp": "0.5.1",
        "parse-repo": "1.0.1",
        "semver": "5.3.0",
        "shelljs": "0.7.6",
        "when": "3.7.8"
    },
    "description": "Interactive release tool for Git repositories. Increment version, commit, tag, push, build, publish to npm. Supports to build and release to a distribution/component repository.",
    "devDependencies": {
        "eslint": "^3.17.0"
    },
    "directories": {},
    "dist": {
        "shasum": "dcd87544c45d32bb74e86ebceab4e152fcc87773",
        "tarball": "https://registry.npmjs.org/release-it/-/release-it-2.7.1.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "5997b7a1b1a0915bdad3a2c395a9e9b561e82ce7",
    "homepage": "https://github.com/webpro/release-it#readme",
    "keywords": [
        "build",
        "commit",
        "distribution",
        "git",
        "github",
        "interactive",
        "npm",
        "publish",
        "push",
        "release",
        "repository",
        "script",
        "shell",
        "tag",
        "tool",
        "version"
    ],
    "license": "MIT",
    "main": "./lib/release.js",
    "maintainers": [
        {
            "name": "webpro"
        }
    ],
    "name": "release-it",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/webpro/release-it.git"
    },
    "scripts": {
        "lint": "eslint lib"
    },
    "version": "2.7.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
