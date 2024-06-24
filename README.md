# WebFont Kazmann Sans

Package for integrating `Kazmann Sans` fonts in a web environment.

![npm](https://img.shields.io/npm/v/@wikiline/webfont-kazmann-sans?style=for-the-badge)
![npm](https://img.shields.io/npm/dm/@wikiline/webfont-kazmann-sans?style=for-the-badge)
![npm](https://img.shields.io/npm/dt/@wikiline/webfont-kazmann-sans?style=for-the-badge)
___

## Installation

This package can be deployed automatically using NPM:

```
npm i @wikiline/webfont-kazmann-sans
```

## Usage (CSS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```css
body {
    font-family: 'Kazmann Sans', sans-serif;
}
```

### Importing

```css
@import "~@wikiline/webfont-kazmann-sans/css/all.css";
@import "~@wikiline/webfont-kazmann-sans/css/all-normal.css";
```

To import specific fonts, you can use:

```css
@import "~@wikiline/webfont-kazmann-sans/css/weight-400.css";
@import "~@wikiline/webfont-kazmann-sans/css/weight-400-normal.css";
```

Note: Also, each file is presented in a minimized form.

### Variables

Each font uses the following CSS variables to set the font display property with the default `swap` value if CSS
variables are not defined:

```css
:root {
    --font-display: swap;
    --font-display-kazmann-sans: swap;
}
```

## Usage (LESS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```scss
body {
    font-family: 'Kazmann Sans', sans-serif;
}
```

### Importing

```less
@import "~@wikiline/webfont-kazmann-sans/less/all";
@import "~@wikiline/webfont-kazmann-sans/less/all-normal";
```

To import specific fonts, you can use:

```less
@import "~@wikiline/webfont-kazmann-sans/less/_weight-400";
@import "~@wikiline/webfont-kazmann-sans/less/_weight-400-normal";
```

### Variables

Each font uses the following LESS variables to set the font display property with the default `swap` value if SCSS
variables are not defined:

```less
@font-display: swap;
@font-display-kazmann-sans: swap;
```

or

```less
@import "~@wikiline/webfont-kazmann-sans/less/config/_variables";
```

## Usage (SCSS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```scss
body {
  font-family: 'Kazmann Sans', sans-serif;
}
```

### Importing

```scss
@import "~@wikiline/webfont-kazmann-sans/scss/all";
@import "~@wikiline/webfont-kazmann-sans/scss/all-normal";
```

To import specific fonts, you can use:

```scss
@import "~@wikiline/webfont-kazmann-sans/scss/weight-400";
@import "~@wikiline/webfont-kazmann-sans/scss/weight-400-normal";
```

### Variables

Each font uses the following SCSS variables to set the font display property with the default `swap` value if SCSS
variables are not defined:

```scss
$font-display: swap;
$font-display-kazmann-sans: swap;
```

## Licensing

It is important to always read the license for every font that you use. Most of the fonts in the collection use the SIL
Open Font License, v1.1. Some fonts use the Apache 2 license. The Ubuntu fonts use the Ubuntu Font License v1.0.
