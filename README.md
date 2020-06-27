# reflow-rs.github.io

Reflow website available [here](https://reflow-rs.github.io/)

## Dev

Site is built with awesome impress.js library. Source can be found in `pug` and `sass` files. Logo created with inkscape.

## Build

To install dependencies run:

```bash
npm install
```

To run dev env use:

```bash
npm run dev
```

This will start live local server on port :8080. Command will watch for changes in `pug` and `sass` files and transpile them. Page should aouto-reload on each change.

To build site from `pug` and `sass` run:

```bash
npm run build
```

Watch for sass changes

```bash
npm run sass-watch
```

Watch for pug changes

```bash
npm run pug-watch
```
