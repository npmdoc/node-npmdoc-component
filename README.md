# api documentation for  [component (v1.1.0)](https://github.com/componentjs/component)  [![npm package](https://img.shields.io/npm/v/npmdoc-component.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-component) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-component.svg)](https://travis-ci.org/npmdoc/node-npmdoc-component)
#### Component package manager consuming git repositories

[![NPM](https://nodei.co/npm/component.png?downloads=true)](https://www.npmjs.com/package/component)

[![apidoc](https://npmdoc.github.io/node-npmdoc-component/build/screenCapture.buildNpmdoc.browser.%2Fhome%2Ftravis%2Fbuild%2Fnpmdoc%2Fnode-npmdoc-component%2Ftmp%2Fbuild%2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-component/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-component/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-component/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk",
        "email": "tj@vision-media.ca"
    },
    "bin": {
        "component": "bin/component",
        "component-build": "bin/component-build",
        "component-crawl": "bin/component-crawl",
        "component-duplicates": "bin/component-duplicates",
        "component-help": "bin/component-help",
        "component-install": "bin/component-install",
        "component-link": "bin/component-link",
        "component-ls": "bin/component-ls",
        "component-outdated": "bin/component-outdated",
        "component-pin": "bin/component-pin",
        "component-search": "bin/component-search",
        "component-update": "bin/component-update",
        "component-validate": "bin/component-validate"
    },
    "bugs": {
        "url": "https://github.com/componentjs/component/issues"
    },
    "dependencies": {
        "co": "^3.0.0",
        "commander": "^2.2.0",
        "component-build": "^1.2.2",
        "component-consoler": "^2.0.0",
        "component-flatten": "^1.0.1",
        "component-ls": "^2.1.0",
        "component-outdated2": "^1.0.4",
        "component-pin": "^1.0.4",
        "component-remotes": "^1.2.0",
        "component-resolver": "^1.3.0",
        "component-search2": "^1.1.1",
        "component-updater": "^1.0.4",
        "component-watcher": "^1.0.1",
        "debug": "*",
        "mkdirp": "~0.3.5",
        "rimraf": "^2.2.6",
        "semver": "^2.2.1",
        "superagent": "~0.17.0",
        "tiny-lr-fork": "0.0.5",
        "win-fork": "~1.1.1"
    },
    "description": "Component package manager consuming git repositories",
    "devDependencies": {
        "mocha": "1",
        "should": "3"
    },
    "directories": {},
    "dist": {
        "shasum": "36049aa257798b7ee57142961e18e0767918c9aa",
        "tarball": "https://registry.npmjs.org/component/-/component-1.1.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "homepage": "https://github.com/componentjs/component",
    "keywords": [
        "component",
        "package",
        "client",
        "browser",
        "module"
    ],
    "main": "lib/component",
    "maintainers": [
        {
            "name": "tjholowaychuk",
            "email": "tj@vision-media.ca"
        },
        {
            "name": "jongleberry",
            "email": "jonathanrichardong@gmail.com"
        },
        {
            "name": "dominicbarnes",
            "email": "dominic@dbarnes.info"
        },
        {
            "name": "tootallnate",
            "email": "nathan@tootallnate.net"
        },
        {
            "name": "rauchg",
            "email": "rauchg@gmail.com"
        },
        {
            "name": "retrofox",
            "email": "rdsuarez@gmail.com"
        },
        {
            "name": "coreh",
            "email": "thecoreh@gmail.com"
        },
        {
            "name": "forbeslindesay",
            "email": "forbes@lindesay.co.uk"
        },
        {
            "name": "kelonye",
            "email": "kelonyemitchel@gmail.com"
        },
        {
            "name": "mattmueller",
            "email": "mattmuelle@gmail.com"
        },
        {
            "name": "yields",
            "email": "yields@icloud.com"
        },
        {
            "name": "anthonyshort",
            "email": "antshort@gmail.com"
        },
        {
            "name": "ianstormtaylor",
            "email": "ian@ianstormtaylor.com"
        },
        {
            "name": "cristiandouce",
            "email": "cristian@gravityonmars.com"
        },
        {
            "name": "swatinem",
            "email": "arpad.borsos@googlemail.com"
        },
        {
            "name": "stagas",
            "email": "gstagas@gmail.com"
        },
        {
            "name": "amasad",
            "email": "amjad.masad@gmail.com"
        },
        {
            "name": "juliangruber",
            "email": "julian@juliangruber.com"
        },
        {
            "name": "shtylman",
            "email": "shtylman@gmail.com"
        },
        {
            "name": "calvinfo",
            "email": "calvin@calv.info"
        },
        {
            "name": "blakeembrey",
            "email": "hello@blakeembrey.com"
        },
        {
            "name": "timoxley",
            "email": "secoif@gmail.com"
        },
        {
            "name": "jonathanong",
            "email": "jonathanrichardong@gmail.com"
        },
        {
            "name": "queckezz",
            "email": "fabian.eichenberger@gmail.com"
        },
        {
            "name": "nami-doc",
            "email": "vendethiel@hotmail.fr"
        },
        {
            "name": "clintwood",
            "email": "clint@anotherway.co.za"
        },
        {
            "name": "thehydroimpulse",
            "email": "dnfagnan@gmail.com"
        },
        {
            "name": "stephenmathieson",
            "email": "me@stephenmathieson.com"
        },
        {
            "name": "trevorgerhardt",
            "email": "trevorgerhardt@gmail.com"
        },
        {
            "name": "timaschew",
            "email": "timaschew@gmail.com"
        },
        {
            "name": "jasonkuhrt",
            "email": "jasonkuhrt@me.com"
        }
    ],
    "name": "component",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/componentjs/component.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "1.1.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module component](#apidoc.module.component)



# <a name="apidoc.module.component"></a>[module component](#apidoc.module.component)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
