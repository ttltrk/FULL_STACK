
---

### HTML Attributes

---

[<<<]()

---

* <a href="#01">Core Attributes</a>
* <a href="#02">Internationalization Attributes</a>
* <a rhef="#03">Generic Attributes</a>


---

An attribute is used to define the characteristics of an HTML element and is placed inside the element's opening tag. All attributes are 
made up of two parts − a name and a value

---

```html
<!DOCTYPE html> 
<html>
 
   <head> 
      <title>Align Attribute  Example</title> 
   </head>
	
   <body> 
      <p align = "left">This is left aligned</p> 
      <p align = "center">This is center aligned</p> 
      <p align = "right">This is right aligned</p> 
   </body>
	
</html>
```

[OUTPUT](http://htmlpreview.github.io/?https://github.com/ttltrk/WEB/blob/master/BHM/05/05_01.HTML)

---

<h4 id="01">Core Attributes</h4>

```html
Id, Title, Class, Style
```

The ```id``` attribute of an HTML tag can be used to uniquely identify any element within an HTML page.

```html
<p id = "html">This para explains what is HTML</p>
<p id = "css">This para explains what is Cascading Style Sheet</p>
```

The ```title``` attribute gives a suggested title for the element. They syntax for the title attribute is similar as explained for id 
attribute.

```html
<!DOCTYPE html>
<html>

   <head>
      <title>The title Attribute Example</title>
   </head>
	
   <body>
      <h3 title = "Hello HTML!">Titled Heading Tag Example</h3>
   </body>
	
</html>
```

[OUTPUT](http://htmlpreview.github.io/?https://github.com/ttltrk/WEB/blob/master/BHM/05/05_02.HTML)

The ```class``` attribute is used to associate an element with a style sheet, and specifies the class of element.

```html
class = "className1 className2 className3"
```

The ```style``` attribute allows you to specify Cascading Style Sheet (CSS) rules within the element.

```html
<!DOCTYPE html>
<html>

   <head>
      <title>The style Attribute</title>
   </head>
	
   <body>
      <p style = "font-family:arial; color:#FF0000;">Some text...</p>
   </body>
	
</html>
```

[OUTPUT](http://htmlpreview.github.io/?https://github.com/ttltrk/WEB/blob/master/BHM/05/05_03.HTML)

---

<h4 id="02">Internationalization Attributes</h4>

```html
dir, lang, xml:lang
```

The ```dir``` attribute allows you to indicate to the browser about the direction in which the text should flow. 

|Value|Meaning|
|----|----|
|ltr|Left to right|
|rtl|Right to left|

[OUTPUT](http://htmlpreview.github.io/?https://github.com/ttltrk/WEB/blob/master/BHM/05/05_04.HTML)

The ```lang``` attribute allows you to indicate the main language used in a document, but this attribute was kept in HTML only for 
backwards compatibility with earlier versions of HTML. This attribute has been replaced by the ```xml:lang``` attribute in new XHTML 
documents.

[OUTPUT](http://htmlpreview.github.io/?https://github.com/ttltrk/WEB/blob/master/BHM/05/05_05.HTML)

The ```xml:lang``` attribute is the XHTML replacement for the lang attribute. The value of the ```xml:lang``` attribute should be an 
ISO-639 
country code as mentioned in previous section.

---

<h4 id="03">Generic Attributes</h4>

|Attribute|Options|Function|
|---------|-------|--------|
|align	|right, left, center|	Horizontally aligns tags|
|valign	|top, middle, bottom|	Vertically aligns tags within an HTML element.|
|bgcolor|	numeric, hexidecimal, RGB values|	Places a background color behind an element|
|background|	URL|	Places a background image behind an element|
|id	|User Defined|	Names an element for use with Cascading Style Sheets.|
|class	|User Defined|	Classifies an element for use with Cascading Style Sheets.|
|width	|Numeric Value|	Specifies the width of tables, images, or table cells.|
|height	|Numeric Value|	Specifies the height of tables, images, or table cells.|
|title	|User Defined|	"Pop-up" title of the elements.|

---

[src](https://github.com/ttltrk/WEB/blob/master/BHM/BHM.MD)

---
