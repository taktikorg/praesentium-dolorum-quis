# @taktikorg/praesentium-dolorum-quis <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A robust, ES3 compatible, "has own property" predicate.

## Example

```js
const assert = require('assert');
const hasOwn = require('@taktikorg/praesentium-dolorum-quis');

assert.equal(hasOwn({}, 'toString'), false);
assert.equal(hasOwn([], 'length'), true);
assert.equal(hasOwn({ a: 42 }, 'a'), true);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@taktikorg/praesentium-dolorum-quis
[npm-version-svg]: https://versionbadg.es/inspect-js/@taktikorg/praesentium-dolorum-quis.svg
[deps-svg]: https://david-dm.org/taktikorg/praesentium-dolorum-quis.svg
[deps-url]: https://david-dm.org/taktikorg/praesentium-dolorum-quis
[dev-deps-svg]: https://david-dm.org/taktikorg/praesentium-dolorum-quis/dev-status.svg
[dev-deps-url]: https://david-dm.org/taktikorg/praesentium-dolorum-quis#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@taktikorg/praesentium-dolorum-quis.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@taktikorg/praesentium-dolorum-quis.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@taktikorg/praesentium-dolorum-quis.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@taktikorg/praesentium-dolorum-quis
[codecov-image]: https://codecov.io/gh/taktikorg/praesentium-dolorum-quis/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/taktikorg/praesentium-dolorum-quis/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/taktikorg/praesentium-dolorum-quis
[actions-url]: https://github.com/taktikorg/praesentium-dolorum-quis/actions
