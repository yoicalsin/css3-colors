# css3-colors

Css3-colors is a package that helps you with color management, `css3-colors` brings variable classes with the colors that have the package [`scss-colors`](https://github.com/yoicalsin/sass-colors)

To see all the colors and their shades, click [here](https://yoicalsin.github.io/sass-colors/)

<!-- ALL-CONTRIBUTORS-BADGE:END -->

<a href="https://github.com/yoicalsin/css3-colors"><img src="https://img.shields.io/spiget/stars/1000?color=brightgreen&label=Star&logo=github" /></a>
<a href="https://www.npmjs.com/css3-colors" target="_blank">
<img src="https://img.shields.io/npm/v/css3-colors" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/css3-colors" target="_blank">
<img src="https://img.shields.io/npm/l/css3-colors" alt="Package License" /></a>
<a href="https://www.npmjs.com/css3-colors" target="_blank">
<img src="https://img.shields.io/npm/dm/css3-colors" alt="NPM Downloads" /></a>
<a href="https://github.com/yoicalsin/css3-colors" target="_blank">
<img src="https://s3.amazonaws.com/assets.coveralls.io/badges/coveralls_95.svg" alt="Coverage" /></a>
<a href="https://github.com/yoicalsin/css3-colors"><img src="https://img.shields.io/badge/Github%20Page-sass.colors-yellow?style=flat-square&logo=github" /></a>
<a href="https://github.com/yoicalsin"><img src="https://img.shields.io/badge/Author-Yoni%20Calsin-blueviolet?style=flat-square&logo=appveyor" /></a>
<a href="https://twitter.com/yoicalsin" target="_blank">
<img src="https://img.shields.io/twitter/follow/yoicalsin.svg?style=social&label=Follow"></a>

## 🎉 Colors Demo

Preview live click [here](https://yoicalsin.github.io/sass-colors/)

## 📦 Installation

Before using, we have to **install** the package via npm or download it directly !

```bash
# To install
npm install --save css3-colors
```

## ▶️ Usage

To use it is very simple, first you have to import the css file into your main file of _html_.

When you install or download the package you will have two css files, `index.css` and `index.min.css`

-  File `index.css` this file is customizable as it is not mined.
-  File `index.min.css` this file brings all the classes with the colors, but unlike the other one, this one will come mirified, that is to say to use it in production.

```html
<!DOCTYPE html>
<html lang="en">
   <head>
      <meta charset="UTF-8" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <title>css-colors - Created by Yoni Calsin</title>

      <!-- This way you'll have to care -->
      <link rel="stylesheet" href="dist/index.css" />
   </head>
   <body>
      <!-- Here he adds all his html code -->
   </body>
</html>
```

But if you want to import it from javascript, you will have to do it this way:

```js
import '~css3-colors/dist/index.css';
```

### 🎨 Color classes

To be able to use the classes are as follows.

The colors are iterated from a map !

```scss
/**
*  Red Colors
**/
$red: (
   'base': #f44336,
   'lighten-5': #ffebee,
   'lighten-4': #ffcdd2,
   'lighten-3': #ef9a9a,
   'lighten-2': #e57373,
   'lighten-1': #ef5350,
   'darken-1': #e53935,
   'darken-2': #d32f2f,
   'darken-3': #c62828,
   'darken-4': #b71c1c,
   'accent-1': #ff8a80,
   'accent-2': #ff5252,
   'accent-3': #ff1744,
   'accent-4': #d50000,
);
```

For example we will use the color red, and if you want more simply add the classes of `.lighten-{number}` or `.accent-{number}`.

```html
<div class="red">
   <h1 class="blue-text">Css3-colors</h1>
</div>
```

To give colors to the texts, it is also very simple, you can use the same classes, _you will have to add the word `-text` to the **end**_

```html
<h1 class="red-text lighten-3">Red title - lighten-3</h1>
```

## ⭐ Support for

css3-colors is an open source project licensed by [MIT](LICENSE). You can grow thanks to the sponsors and the support of the amazing sponsors. If you want to join them, [contact me here](mailto:helloyoicalsin@gmail.com).

## 🎩 Stay in touch

-  Author [Yoni Calsin](https://github.com/yoicalsin)
-  Twitter [Yoni Calsin](https://twitter.com/yoicalsin)

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://twitter.com/yoicalsin"><img src="https://avatars0.githubusercontent.com/u/58490737?v=4" width="70px;" alt=""/><br /><sub><b>Yoni Calsin</b></sub></a><br /><a href="https://github.com/css3-colors/css3-colors/commits?author=yoicalsin" title="Code">💻</a> <a href="https://github.com/css3-colors/css3-colors/issues?q=author%3Ayoicalsin" title="Bug reports">🐛</a> <a href="https://github.com/css3-colors/css3-colors/commits?author=yoicalsin" title="Documentation">📖</a> <a href="#blog-yoicalsin" title="Blogposts">📝</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

## 📜 License

css3-colors is [MIT licensed](LICENSE).
