# win-release-id

[![npm version](https://img.shields.io/npm/v/win-release-id.svg)](https://www.npmjs.com/package/win-release-id)

> Get the release id of the current Windows OS

## Installation

```sh
npm install win-release-id
```

## Usage

```js
const winReleaseId = require('win-release-id');

// on Windows 10 v1607 Build 14393
winReleaseId();
// => 1607

// before 10
winReleaseId();
// => -1

winReleaseId('10.0.16299.214');
// => 1709
```

## License

MIT
