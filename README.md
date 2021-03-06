# [gulp-es6-template][author-www-url] [![npmjs.com][npmjs-img]][npmjs-url] [![The MIT License][license-img]][license-url] 

> Gulp plugin for [`es6-template`](https://github.com/tunnckoCore/es6-template) - easy and small template engine.

[![code climate][codeclimate-img]][codeclimate-url] [![standard code style][standard-img]][standard-url] [![travis build status][travis-img]][travis-url] [![coverage status][coveralls-img]][coveralls-url] [![dependency status][david-img]][david-url]


## Install
```
npm i gulp-es6-template --save
```


## Usage
> For more use-cases see the [tests](./test.js)

```js
var gulp = require('gulp')
var es6template = require('gulp-es6-template')

gulp.src('./src/*.{html,txt,es6template}')
  .pipe(es6template({name: 'Charlike'}))
  .pipe(gulp.dest('./dest'))
```


## Related
- [octet](https://github.com/tunnckoCore/octet): 1kb template engine for the browser and nodejs. Support helpers, partials and more.
- [es6-template](https://github.com/tunnckoCore/es6-template): Easy and small template engine for the browser and nodejs.
- [es6-template-regex](https://github.com/jonschlinkert/es6-template-regex): Regular expression for matching es6 template delimiters in a string.
- [es6-template-strings](https://github.com/medikoo/es6-template-strings): Compile and resolve template strings notation as specified in ES6
- [gulp-j140](https://github.com/tunnckoCore/gulp-j140): Gulp plugin for `j140` - template engine in 140 bytes by @jed Schmidt.
- [gulp-octet](https://github.com/tunnckoCore/gulp-octet): Gulp plugin for `octet` - template engine in just 20 lines - used in AbsurdJS.
- [gulp-es6-template](https://github.com/tunnckoCore/gulp-es6-template): Gulp plugin for `es6-template` - easy and small template engine.
- [gulp-es6-template-strings](https://github.com/tunnckoCore/gulp-es6-template-strings): Gulp plugin for `es6-template-strings` package.
- [jstransformer-es6-template](https://github.com/tunnckoCore/jstransformer-es6-template): es6-template support for JSTransformers
- [jstransformer-es6-template-strings](https://github.com/jstransformers/jstransformer-es6-template-strings): es6-template-strings support for JSTransformers
- [jstransformer-octet](https://github.com/jstransformers/jstransformer-octet): octet support for JSTransformers
- [jstransformer-j140](https://github.com/tunnckoCore/jstransformer-j140): j140 support for JSTransformers


## Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/tunnckoCore/gulp-es6-template/issues/new).  
But before doing anything, please read the [CONTRIBUTING.md](./CONTRIBUTING.md) guidelines.


## [Charlike Make Reagent](http://j.mp/1stW47C) [![new message to charlike][new-message-img]][new-message-url] [![freenode #charlike][freenode-img]][freenode-url]

[![tunnckocore.tk][author-www-img]][author-www-url] [![keybase tunnckoCore][keybase-img]][keybase-url] [![tunnckoCore npm][author-npm-img]][author-npm-url] [![tunnckoCore twitter][author-twitter-img]][author-twitter-url] [![tunnckoCore github][author-github-img]][author-github-url]


[npmjs-url]: https://www.npmjs.com/package/gulp-es6-template
[npmjs-img]: https://img.shields.io/npm/v/gulp-es6-template.svg?label=gulp-es6-template

[license-url]: https://github.com/tunnckoCore/gulp-es6-template/blob/master/LICENSE.md
[license-img]: https://img.shields.io/badge/license-MIT-blue.svg


[codeclimate-url]: https://codeclimate.com/github/tunnckoCore/gulp-es6-template
[codeclimate-img]: https://img.shields.io/codeclimate/github/tunnckoCore/gulp-es6-template.svg

[travis-url]: https://travis-ci.org/tunnckoCore/gulp-es6-template
[travis-img]: https://img.shields.io/travis/tunnckoCore/gulp-es6-template.svg

[coveralls-url]: https://coveralls.io/r/tunnckoCore/gulp-es6-template
[coveralls-img]: https://img.shields.io/coveralls/tunnckoCore/gulp-es6-template.svg

[david-url]: https://david-dm.org/tunnckoCore/gulp-es6-template
[david-img]: https://img.shields.io/david/tunnckoCore/gulp-es6-template.svg

[standard-url]: https://github.com/feross/standard
[standard-img]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg


[author-www-url]: http://www.tunnckocore.tk
[author-www-img]: https://img.shields.io/badge/www-tunnckocore.tk-fe7d37.svg

[keybase-url]: https://keybase.io/tunnckoCore
[keybase-img]: https://img.shields.io/badge/keybase-tunnckoCore-8a7967.svg

[author-npm-url]: https://www.npmjs.com/~tunnckoCore
[author-npm-img]: https://img.shields.io/badge/npm-~tunnckocore-cb3837.svg

[author-twitter-url]: https://twitter.com/tunnckoCore
[author-twitter-img]: https://img.shields.io/badge/twitter-@tunnckoCore-55acee.svg

[author-github-url]: https://github.com/tunnckoCore
[author-github-img]: https://img.shields.io/badge/github-@tunnckoCore-4183c4.svg

[freenode-url]: http://webchat.freenode.net/?channels=charlike
[freenode-img]: https://img.shields.io/badge/freenode-%23charlike-5654a4.svg

[new-message-url]: https://github.com/tunnckoCore/ama
[new-message-img]: https://img.shields.io/badge/ask%20me-anything-green.svg