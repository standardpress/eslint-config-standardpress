# eslint-config-standardpress

[![npm version](https://img.shields.io/npm/v/eslint-config-standardpress.svg)](https://npmjs.com/package/eslint-config-standardpress)
[![travis-ci build status](https://travis-ci.com/standardpress/eslint-config-standardpress.svg?branch=master)](https://travis-ci.com/standardpress/eslint-config-standardpress)
[![appveyor build status](https://ci.appveyor.com/api/projects/status/vxlwmo9yy5y3lh04/branch/master?svg=true)](https://ci.appveyor.com/project/jasonnam/eslint-config-standardpress/branch/master)

ESLint shareable config by StandardPress.

## Installation

### install-peerdeps

Install with [`install-peerdeps`](https://npmjs.com/package/install-peerdeps):

```sh
npx install-peerdeps --dev eslint-config-standardpress
```

### npm

Install with npm:

```sh
npm install --save-dev eslint-config-standardpress
```

Next, install the correct versions of each package, which are listed by the command:

```sh
npm info "eslint-config-standardpress@latest" peerDependencies
```

## Usage

Extend ESLint config with `standardpress`.

```json
{
  "extends": "standardpress"
}
```

## License

eslint-config-standardpress is released under the MIT license. [See LICENSE](https://github.com/standardpress/eslint-config-standardpress/blob/master/LICENSE) for details.
