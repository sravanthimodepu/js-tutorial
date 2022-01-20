## Welcome to JavaScript Tutorial for Beginners

JavaScript is the most programming language of Web

### Introduction

JavaScript is used to create interactive websites. it is mainly used for:
1. Client-side vaildation
2. Dynamic drop-down menu
3. Displayng date and time
4. Displaying popup windows	and dialogue boxes	

<script></script> tag is used to write javascript and include it in html page

## How to use Javascript code
 - we will use document.write(); method is used to display the content in the webpage with the help of script tags.
 
## JavaScript Syntax 
```Syntax
<script type="text/javascript">
	document.write("JavaScript Programming Tutorials");
</script>	
```

## Inserting Javascript

We can insert javascript code in 3 ways:
1. Head 
2. Body	
3. External file

### Head
we can use javascript in head tag of the html as 
```
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>example</title>
	<script type="text/javascript">
	document.write("JavaScript Programming Tutorials");
    </script>
</head>
<body>

</body>
</html>	
```

### Body
we can write the javascript code in the body tag.

```
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>example</title>	
</head>
<body>
	<script type="text/javascript">
	document.write("JavaScript Programming Tutorials");
    </script>	
</body>
</html>
``` 
### External file	
- create a new file named external.js and add the code in document.write(); method as below:
```
document.write("Welcome to prgramming");
```

- add external.js file path in the html file using source(src) attribute as below to read the content from the external file
```
<script type="text/javascript" src="external.js"></script>
```
- external js file is mostly used when we use one js file for multiple web pages.

## Different ways to Display content on web page 

- There are 3 ways to display the content in the webpage
1. document.write(); // we will use it for testing purpose
2. alert();  or window.alert(); // it displays as the popup box or alertbox
3. innerHTML(); // form validation 

```
<p id="demo"> welcome Friends</p>
<script>
document.getElementById("demo"),innerHTML="Programming Tutorials";
</script>

output:

*Programming Tutorials*	
```
Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
