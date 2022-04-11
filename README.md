# sentry-ignores

[![npm](https://img.shields.io/npm/v/sentry-ignores.svg)](https://www.npmjs.com/package/sentry-ignores)
[![npm](https://img.shields.io/npm/types/sentry-ignores.svg)](https://www.npmjs.com/package/sentry-ignores)
[![npm](https://img.shields.io/npm/l/sentry-ignores.svg)](https://www.npmjs.com/package/sentry-ignores)

> A curated list of common ignore rules for [Sentry](https://docs.sentry.io/platforms/javascript/).


## Installation

```
npm install sentry-ignores
```

```
yarn add sentry-ignores
```


## Usage

```js
import { denyUrls, ignoreErrors } from 'sentry-ignores';

Sentry.init({
  ...
  denyUrls,
  ignoreErrors,
});
```


## Sources

The ignored errors and urls in this package come from multiple sources, including but not limited to:

 - https://docs.sentry.io/clients/javascript/tips/
 - http://blog.errorception.com/2012/03/tale-of-unfindable-js-error.html
 - https://gist.github.com/pamelafox/1878283
 - https://gist.github.com/impressiver/5092952
 - https://gist.github.com/Chocksy/e9b2cdd4afc2aadc7989762c4b8b495a

Please create an [issue](https://github.com/fdev/sentry-ignores/issues/new) or [pull request](https://github.com/fdev/sentry-ignores/pulls) to suggest new rules.
