# Coding For Beginners 
--
## Installation
- Install [Sublime Text](http://www.sublimetext.com/)
	- Sublime Text is a text-editor for code.  

## What is front-end web development?
- Everything your eyes can see on the page. 
- Composed of HTML, CSS, and JavaScript.
- A front-end developer will take the work of a designer, and code it on the front-end so a back-end developer can build on top of that. 

### What is HTML? 
- Stands for: Hyper Text Markup Language.
- It is the content of the page. 
	- e.g. header or paragraph
- Has its own default styles. 

### What is CSS?
- Stands for: Cascading Style Sheet. 
- It is the stylistic component of the page. 
- Overrides the default styles of HTML. 
	- e.g. change the color or the font-family of your header

### What is JavaScript?
- Helps increase interactivity of the page. 
- Helps with page interactions such as animations 
- Helps with dynamic loading of content. 

## Let's Dive Deeper
### HTML:
#### Tags < >
- Allow you to set up structure of the page. 
- Tell the browser how to format content. 

`<h1>Hello World!</h1>`

#### Basic layout for an HTML file

```
<!DOCTYPE html>
<html lang="en">
	<head>
	<meta charset="UTF-8">
	<title>My First Webpage</title>
	</head>
	<body>
		<h1>Hello World!</h1>
	</body>
</html>

```
### CSS:
- In order to run external CSS you need to link it to the HTML. This usually goes in the head tag:

`<link rel=“stylesheet” href=“css/style.css” />`

#### Basic layout for a CSS file

```
h1 {
	color: #FF9966;
	text-align: center;
}

```
### What about different ways to organize content?

#### divs:
- Define a division.
- They are equivalent to empty rectangles. 
- They are used to format block elements that can be styled via CSS. 

`<div> </div `

#### spans:
- They are inline elements that are normally displayed without line breaks. 

`<span> </span> `

### Id's versus classes
#### Id's: 
- Are selectors. 
- They are used if you want a single, unique element. 

HTML:

```
<div id=“header”>
	<h1>Welcome to my website</h1>	
</div>
``` 
CSS: hash/pound sign designate an id

```
#header{
	text-align: center;
	color: red;
}
```


#### Classes:
- Are selectors. 
- Select an element with a specific class attribute. 

HTML:

```
<div class=“paragraph”>
     Here are my favorite hobbies:
     skateboarding, scuba diving, and
     riding motorcycles.
</div> 

```
CSS: a period designates a class

```
.paragraph {
	color: green;
}

```

## How can you edit an existing webpage?
- Hit "command+option+j" and this will open the developer tools. 
- This can then be used as a “console” to test new code/change code and see what it looks like. 


## Summary
- HTML and CSS work together. 
- What do you think is happening on the back-end?
