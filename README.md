# @ox2/css-icons-material
![NPM version](https://img.shields.io/badge/npm-private-orange.svg?style=flat)
<!-- ![NPM version](https://img.shields.io/npm/v/@ox2/css-icons-material.svg?style=flat) -->

Material font icon pack base64-encoded and embedded into a css file.


## Installation
Install using [npm](http://npmjs.com):
```sh
npm install @ox2/css-icons-material --save
```
Install using [yarn](http://yarnpkg.com):
```sh
yarn add @ox2/css-icons-material
```

### Usage
You can use it in a webpack project by importing it `import '@ox2/css-icons-material` in your top level js file like `index.js` or in a `.storybook/config.js` if your using [React Storybook](https://github.com/storybooks/react-storybook).


### Update instructions

1. Download new icon pack from icomoon app to `css-icons-material/downloads/`
2. Copy `selection.json` to `src/`
2. Generate data uri in `src/index.css` from woff2 file: `../downloads/fonts/icons-material.woff2`.
3. Bump package version, `npm run build` and publish the package, output: `build/`
```
npm run build
cd build && npm publish
```


## Change Log
Changes are tracked in the [CHANGELOG.md](https://github.com/ox2/css-icons-material/blob/master/CHANGELOG.md)

## License
[MIT](https://github.com/ox2/css-icons-material/blob/master/LICENSE)
