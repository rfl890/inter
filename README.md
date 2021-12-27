# Inter fonts   
Get all the font weights for the font Inter. Fonts are as followed:
```css
body {
  font-family: 'Inter Thin', sans-serif;
}
body {
  font-family: 'Inter Extra-Light', sans-serif;
}
body {
  font-family: 'Inter Light', sans-serif;
}
body {
  font-family: 'Inter', sans-serif; /* Regular style */
}
body {
  font-family: 'Inter Medium', sans-serif;
}
body {
  font-family: 'Inter Semibold', sans-serif;
}
body {
  font-family: 'Inter Bold', sans-serif;
}
body {
  font-family: 'Inter Extra-Bold', sans-serif;
}
body {
  font-family: 'Inter Black', sans-serif; /* i.e, Bootstrap display headings */
}
```   
## Include in your website   
Just add these tags into the `<head>` of your document:
```html
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/rfl890/inter@release/inter.min.css" integrity="sha384-UVhDDjAsMqomsChoEgS+5OunNmICDJz5zm3W6Kj1yFtWtcYgSE1dF/IDsJxVbF2w" crossorigin="anonymous">
```
Also, add this to your CSS styles, so the font weight displayes properly:   
```css
* {
   font-style: normal !important;
   font-weight: normal !important;
  -webkit-font-smoothing: antialiased !important;
  -moz-osx-font-smoothing: grayscale !important;  
}
```
## Examples   
[https://inter.rfl890.repl.co](https://inter.rfl890.repl.co)
