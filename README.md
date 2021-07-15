# sizeInPage.js
Is a JavaScript plugin that helps you better design websites

# How
Used only for sizing and displays width, height and breakpoint <br>
so you can work on sizing better

# How to use
Just link the sizeInPage.js file to your page and then call the startSizeInPage function 
```html
<script src="sizeInPage.js"></script>
```
- startSizeInPage()

# Options
+ theme(Set General theme) <br>
+ align(Set the location on the page) <br>
+ opacity(Adjust transparency) <br>
+ help(Show help)<br>
sizeInPage.min.js:1 Use options :<br>
To use the options, we must pass them as an object and <br>
as an argument to the startSizeInPage() function. <br>
example :
```javascript
startSizeInPage({
 theme: 'dark',
 align: 'bl',
 opacity: '1',
 help:'en'
})
```

# Options values
<h4>theme</h4><br>
theme: 'dark' | 'theme': light <br>
(theme: dark is enabled by default) <br>
Example of use:
```javascript
startSizeInPage({
 theme: 'dark'
})
```
or
```javascript
startSizeInPage({
 theme: 'light'
})
```
<hr>
align <br>
align : 'tl' | 'tr' | 'bl' | 'br' | 'center'  <br>
(align: 'bl' is enabled by default) <br>
(Values ​​stand for directions, example: tr = top right) <br>
Example of use:
```javascript
startSizeInPage({
 align: 'tl' (example)
})
```

opacity <br>
To set the opacity and its value is between 0 and 1 <br>
(opacity: 1 is enabled by default) <br>
Example of use:
```javascript
startSizeInPage({
 opacity: '0.8' (example)
})
```

help <br>
help : 'en' | 'fa' 
To display the plugin guide (en = in English , fa = in Persian) <br>
(help: 'none' is enabled by default) <br>
Example of use:
```javascript
startSizeInPage({
 help: 'en' (example)
})
```
