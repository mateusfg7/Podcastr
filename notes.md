# CSS
## Y-Scroll just to a component
_You need to set a fixed height_
```css
.component {
  height: 100vh;
  overflow-y: scroll;
} 
```

## Use "..." when the text exceed component width
```css
.component {
  text-overflow: ellipsis;
}
```


## JS

### Ternary If/Else
```js
a = 1
b = 2

c = a == 1 ? a : b
```

_without "else"_
```js
a = 1
b = 2

c = a == 1 && a
```

_just the "else"_
```js
a = 1
b = 2

c = a != 1 || b
```

