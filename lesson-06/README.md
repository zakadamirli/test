### Cascading Style Sheets

### Document Object Model DOM(Tree)

## CSS OM -> CSS Object Model

## CSS in html

- Inline CSS
  style attribute
- Internal
  CSS
  `<style> </style>` tag
- External CSS
  ````html
  <link rel="stylesheet" href="file.css" />```
  ````

## CSS SELECTORS

- tag selector

```css
body {
  font-size: 45px;
}
```

- CLASS Selector
  ````html
  <div class="greeting">Hello World!</div>
  ```
  ````

```css
.greeting {
  font-size: 22px;
}
```

ID selector

```html
<div id="friend">Hello friend</div>
```

```css
#friend {
    background="purple"
}
```

- Attribute selector

```html
<span title="John Doe">Helo John </span>
<p data-status="success">Jon Doe</p>
```

```css
[title]{
    color: green;
}
[data-status="success"]{
    background-color= green;
}
```

-PSEUDO ELEMENT & PSEUDO CLASS SELECTOR

```html
<input placeholder="enter your name" />
```
```css
::placeholder{
    color: red;
}
```
## SPECIFITY
