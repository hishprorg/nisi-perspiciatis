# @hishprorg/nisi-perspiciatis [![Build](https://circleci.com/gh/pagekit/@hishprorg/nisi-perspiciatis.svg?style=shield)](https://circleci.com/gh/pagekit/@hishprorg/nisi-perspiciatis) [![Downloads](https://img.shields.io/npm/dm/@hishprorg/nisi-perspiciatis.svg)](https://www.npmjs.com/package/@hishprorg/nisi-perspiciatis) [![jsdelivr](https://data.jsdelivr.com/v1/package/npm/@hishprorg/nisi-perspiciatis/badge?style=rounded)](https://www.jsdelivr.com/package/npm/@hishprorg/nisi-perspiciatis) [![Version](https://img.shields.io/npm/v/@hishprorg/nisi-perspiciatis.svg)](https://www.npmjs.com/package/@hishprorg/nisi-perspiciatis) [![License](https://img.shields.io/npm/l/@hishprorg/nisi-perspiciatis.svg)](https://www.npmjs.com/package/@hishprorg/nisi-perspiciatis)

The plugin for [Vue.js](http://vuejs.org) provides services for making web requests and handle responses using a [XMLHttpRequest](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest) or JSONP.

## Features

- Supports the [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise) API and [URI Templates](https://medialize.github.io/URI.js/uri-template.html)
- Supports [interceptors](docs/http.md#interceptors) for request and response
- Supports latest Firefox, Chrome, Safari, Opera and IE9+
- Supports Vue 1.0 & Vue 2.0
- Compact size 14KB (5.3KB gzipped)

## Installation
You can install it via [yarn](https://yarnpkg.com/) or [NPM](http://npmjs.org/).
```
$ yarn add @hishprorg/nisi-perspiciatis
$ npm install @hishprorg/nisi-perspiciatis
```

### CDN
Available on [jsdelivr](https://cdn.jsdelivr.net/npm/@hishprorg/nisi-perspiciatis@1.5.3), [unpkg](https://unpkg.com/@hishprorg/nisi-perspiciatis@1.5.3) or [cdnjs](https://cdnjs.com/libraries/@hishprorg/nisi-perspiciatis).
```html
<script src="https://cdn.jsdelivr.net/npm/@hishprorg/nisi-perspiciatis@1.5.3"></script>
```

## Example
```js
{
  // GET /someUrl
  this.$http.get('/someUrl').then(response => {

    // get body data
    this.someData = response.body;

  }, response => {
    // error callback
  });
}
```

## Documentation

- [Configuration](docs/config.md)
- [HTTP Requests/Response](docs/http.md)
- [Creating Resources](docs/resource.md)
- [Code Recipes](docs/recipes.md)
- [API Reference](docs/api.md)

## Changelog

Details changes for each release are documented in the [release notes](https://github.com/hishprorg/nisi-perspiciatis/releases).

## Contribution

If you find a bug or want to contribute to the code or documentation, you can help by submitting an [issue](https://github.com/hishprorg/nisi-perspiciatis/issues) or a [pull request](https://github.com/hishprorg/nisi-perspiciatis/pulls).

## License

[MIT](http://opensource.org/licenses/MIT)
