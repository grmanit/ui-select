Simple fork of [angular-ui/ui-select](https://github.com/angular-ui/ui-select) with some additional fixes:

- Fixed [angular-ui#753](https://github.com/angular-ui/ui-select/issues/753) ([commit](https://github.com/szsolt/ui-select/commit/a274f49122c522bb8621e5f2cb701344c5164e69), [PR](https://github.com/angular-ui/ui-select/pull/1121/files))
- Fixed [angular-ui#974](https://github.com/angular-ui/ui-select/issues/974) ([commit](https://github.com/homerjam/ui-select/commit/637be080c19f1c16e2e2c87fca30dbca3dff9369), [PR](https://github.com/angular-ui/ui-select/pull/1036))
- Fixed [angular-ui#258](https://github.com/angular-ui/ui-select/issues/258), [angular-ui#850](https://github.com/angular-ui/ui-select/issues/850), [angular-ui#914](https://github.com/angular-ui/ui-select/issues/914)([commit](https://github.com/slawekkolodziej/ui-select/commit/d1d522b445ab25ec12fbd9bf64527d23dc60d3bb), [PR](https://github.com/angular-ui/ui-select/pull/1026))

# AngularJS ui-select [![Build Status](https://travis-ci.org/angular-ui/ui-select.svg?branch=master)](https://travis-ci.org/angular-ui/ui-select)

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/angular-ui/ui-select?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

AngularJS-native version of [Select2](http://ivaynberg.github.io/select2/) and [Selectize](http://brianreavis.github.io/selectize.js/).

- [Demo](http://plnkr.co/edit/a3KlK8dKH3wwiiksDSn2?p=preview)
- [Demo Multiselect](http://plnkr.co/edit/juqoNOt1z1Gb349XabQ2?p=preview)
- [Examples](https://github.com/angular-ui/ui-select/blob/master/examples)
- [Documentation](https://github.com/angular-ui/ui-select/wiki)

## Last Changes

- Check [CHANGELOG.md](/CHANGELOG.md)

## Features

- Search, Select, and Multi-select
- Themes: Bootstrap, Select2 and Selectize
- Keyboard support
- jQuery not required (except for old browsers)
- Small code base: 4.57KB min/gzipped vs 20KB for select2

For the roadmap, check [issue #3](https://github.com/angular-ui/ui-select/issues/3) and the [Wiki page](https://github.com/angular-ui/ui-select/wiki/Roadmap).

## Installation using [Composer](http://getcomposer.org/)

Make sure composer is install globally before we proceed. After that we need to add below piece of code in `composer.json` file located inside your project root folder.

```
{
    "require": {
        "components/ui-select": "dev-master"
    }
}
```

- Run `composer update` and composer will install the component.
- Inside your HTML add below script and link tags.
  - select.js: `<script src="components/ui-select/dist/select.min.js"></script>`
  - select.css: `<link rel="stylesheet" href="components/ui-select/dist/select.min.css">`


## Development

### Prepare your environment
* Install [Node.js](http://nodejs.org/) and NPM (should come with)
* Install global dev dependencies: `npm install -g bower gulp`
* Install local dev dependencies: `npm install && bower install` in repository directory

### Development Commands

* `gulp` to jshint, build and test
* `gulp build` to jshint and build
* `gulp test` for one-time test with karma (also build and jshint)
* `gulp watch` to watch src files to jshint, build and test when changed

## Contributing

- Check [CONTRIBUTING.md](/CONTRIBUTING.md)
- Run the tests
- Try the [examples](https://github.com/angular-ui/ui-select/blob/master/examples)

When issuing a pull request, please exclude changes from the "dist" folder to avoid merge conflicts.
