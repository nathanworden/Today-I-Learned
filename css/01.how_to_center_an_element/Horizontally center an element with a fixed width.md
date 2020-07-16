### Horizontally center a element with a fixed width

To horizontally center a positioned element with a fixed width, you can move it to the center of the container with a `left` offset of 50%, and a negative left margin that is half the width of the element.

```css
section {
  box-sizing: border-box;
  text-align: center;
  left: 50%;
  width: 200px;
  background-color: #00D18E;
  position: absolute;
  margin-left: -100px;
  margin-top: 100px;
}
```



```html
<html> 
  <head>
    <link rel="stylesheet" href="stylesheet.css" />
  </head>
  <body>
    <section>
      <p>I'm centered!</p>
    </section>
  </body>
</html>
```



