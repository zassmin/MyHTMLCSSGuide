# What is HTML and CCS?

* `HTML: HyperText Markup Language`
* `HyperText: "text with links in it."`
* `CSS: Cascading Style Sheets`
* `CSS: makes webpages pretty`

# Simple HTML commands

to bold text

~~~~
@@@ html

<strong> <\strong>

~~~~

to set up page, first, it tells to browser what language it's reading

~~~~
@@@ html

<!DOCTYPE html>

~~~~

to start the html doc use, 

~~~~
@@@ html

<html>
</html>

~~~~

# to know

* `there are 2 parts to an html file: head and body`
* `head includes important info, such as title`
* `body includes what will be visible on the page`
* `open html files using a browser`
* `browser renders show the file`


# more on html basics

~~~~
@@@ html

<!DOCTYPE html>
<html>
  <head>
  </head>
</html>
~~~~

titling

~~~~
@@@ html

<!DOCTYPE html>
<html>
  <head>
    <title> The title </title>
  </head>
</html>

~~~~

!SLIDE

content between tags is called an element

~~~~
@@@ html

element = <opening tag> + content + <closing tag>

~~~~

body

~~~~
@@@ html

<html>
    <head></head>
    <body></body>
</html>

~~~~

paragraphs! inside body

~~~~
@@@ html

<body>
  <p>    
  </p>           
</body>

~~~~

# a little on headings

headings in the body

~~~~
@@@ html

<body>
  <h1>
  </h1>
  <p>    
  </p>           
</body>

~~~~

6 heading sizes h1 - h6

# adding images

~~~~
@@@ html

<!DOCTYPE html>
<html>
	<head>
		<title></title>
	</head>
	<body>
		<img src="url" />
	</body>
</html>
~~~~

# want to make a hyperlink?

~~~~
@@@ html

<!DOCTYPE html>
<html>
	<head>
		<title></title>
	</head>
	<body>
		<a href="url" />Add link title here</a>
	</body>
</html>

~~~~



