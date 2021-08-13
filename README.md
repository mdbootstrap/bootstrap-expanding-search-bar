# Bootstrap Expanding Search Bar

Responsive Expanding Search Bar built with Bootstrap 5. Examples with the trigger on click and on hover.

To learn more read [Search Docs](https://mdbootstrap.com/docs/standard/forms/search/).

## On click

HTML
```html
<input type="text" class="search-click" name="" placeholder="search here..." />
```

CSS
```css
.search-click {
  border: 1px solid #ccc;
  outline: none;
  background-size: 22px;
  background-position: 13px;
  border-radius: 10px;
  width: 50px;
  height: 50px;
  padding: 25px;
  transition: all 0.5s;
}
.search-click:focus {
  width: 300px;
  padding-left: 50px;
}
.search-click {
  position: relative;
  overflow: hidden;
  height: 50px;
}
.search-click input {
  background: transparent;
  border: 1px solid #ccc;
  outline: none;
  position: absolute;
  width: 300px;
  height: 50px;
  left: 0%;
  padding: 10px;
}
```

#### Much more examples and a detailed description can be found at [📄 Expanding Search Bar documentation page](https://mdbootstrap.com/docs/standard/extended/search-expanding/)
