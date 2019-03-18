# Stisla Theme

This is the standalone CSS and SCSS theme of the popular [stisla free Bootstrap admin template](https://github.com/stisla/stisla.git).

[![Stisla Preview](https://camo.githubusercontent.com/2135e0f6544a7286a3412cdc3df32d47fc91b045/68747470733a2f2f692e6962622e636f2f3674646d6358302f323031382d31312d31312d31352d33352d676574737469736c612d636f6d2e706e67)](https://getstisla.com)

## Quick Start

Install
```bash
# using NPM
npm i stisla-theme

# using yarn
yarn add stisla-theme
```

Using SCSS
```scss
@import 'stisla-theme/dist/scss/style.scss';

/* optional imports */
@import 'stisla-theme/dist/scss/components.scss';
@import 'stisla-theme/dist/scss/rtl.scss';
```

Using CSS
```css
@import 'stisla-theme/dist/css/style.css';

/* optional imports */
@import 'stisla-theme/dist/css/components.css';
@import 'stisla-theme/dist/css/rtl.css';
```

## Development

Get stisla as a git submodule.
```bash
git submodule init
git submodule update
```

Install dependencies
```bash
yarn
```

Build
```bash
yarn prepublish
```

## License
Stisla is under the [MIT License](LICENSE)

## Credits

All credits go to the creators of [stisla](https://getstisla.com/).
