# GitHub HTML+JS page template

## Initial setup

1. Fork this project
2. Go to `https://github.com/<username>/<project>/settings/pages`
   * Enable from a branch
   * Branch > main

   ![img.png](img.png)
3. Visit your page: `https://<username>.github.io/<project>/`

## JavaScript & CSS
1. Create css file `/css/style.css`
```css
body {
  text-align: center;
  background: black;
  color: white;
}

h1 {
  margin-top: 40vh;
}
```
2. Create js file `/js/main.js`
```js
console.log("hello world")
```
3. Add a `favicon.ico` to the root
4. Modify `index.html` to add css, js and favicon
```html
  <head>
   ...
    <link rel="stylesheet" href="css/style.css">
    <link rel="shortcut icon" type="image/png" href="favicon.ico">
    <link rel="apple-touch-icon" href="favicon.ico">
  </head>
  <body>
    ...
    <script src="js/main.js"></script>
  </body>
```