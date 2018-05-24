stylus-mixins
=============

  > A personal collection of Stylus mixins.

[![npm package version](https://img.shields.io/npm/v/@simbo/stylus-mixins.svg?style=flat-square)](https://www.npmjs.com/package/@simbo/stylus-mixins)
[![Travis CI build status](https://travis-ci.org/simbo/stylus-mixins.svg?branch=master)](https://travis-ci.org/simbo/stylus-mixins/builds)

---


## Installation

`stylus-mixins` is a user scoped npm package. You can install it…

``` sh
# …using npm
npm install @simbo/stylus-mixins
# …or yarn
yarn add @simbo/stylus-mixins
```


## Usage

``` stylus
/* require all mixins… */
@require 'path/to/node_modules/stylus-mixins'

/* …or only those you need… */
@require 'path/to/node_modules/stylus-mixins/mixins/md-shadow'

/* …and call them where needed: */
.my-container
  mdShadow()
```


## Mixins


### `mdShadow($depth = 2, $alphaMultiplier = 1, $inset = false)`

Material design shadows with umbra, penumbra and ambient shadow

[./mixins/md-shadow](./mixins/md-shadow.styl)


### `ratioExpander($ratio = 1)`

Creates a peudo element expander to maintain aspect ratio

[./mixins/ratio-expander](./mixins/ratio-expander.styl)


### `textEllipsis()`

Ellipsis overflow for single-line text

[./mixins/text-ellipsis](./mixins/text-ellipsis.styl)


## License

[MIT &copy; Simon Lepel](http://simbo.mit-license.org/)
