# How to implement 2d parallax effect

First, add the [parallax.js](https://github.com/wagerfield/parallax) in `index.html` by cdn reference.

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/parallax/3.1.0/parallax.min.js"></script>
```

Second, add the following code in the `./src/index.js` file:

```js
const scene = document.getElementById("scene");

new Parallax(scene, {
    relativeInput: true,
});
```

Done!
