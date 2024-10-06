# Basic Web Techniques

## Reading Assignment 2: WWW and HTML

### Html

1. Name the components of html elements properly
   1. Tags: Also known as element names, these are the words that define the element, such as p, img, div, etc.
   2. Attributes: These are additional information that can be added to an element to provide more context or functionality, such as src, href, class, etc.
   3. Values: These are the values assigned to attributes, such as the URL of an image or the text content of a paragraph.
   4. Content: This is the text or other elements that are contained within an element, such as the text inside a paragraph or the image inside an img element.
   5. Opening tag: This is the first part of an element, which includes the element name and any attributes, such as ```<p class="intro">```.
   6. Closing tag: This is the second part of an element, which includes the element name preceded by a forward slash, such as ```</p>```.
   7. Self-closing tag: This is a special type of tag that does not require a closing tag, such as ```<img src="image.jpg" />```.
2. Identify void elements and how they are denoted: self-closing tags
3. Identify attributes: src, href, class
4. Write down the correct ``DOCTYPE`` declaration for html 5: ```<!DOCTYPE html>```
5. Write down syntactically correct statements for the following elements
   - Article (``<article>``):
   ~~~
   <article>
       <h2>My First Article</h2>
       <p>This is the content of my first article.</p>
   </article>
   ~~~
   - Body (``<body>``):
   ~~~
   <body>
       <h1>My First Heading</h1>
       <p>This is the content of my first heading.</p>
   </body>
   ~~~
   - line break (``<br/>``):
   ~~~
   <br>
   ~~~
   - Headings (``<h1>``, ...):
   ~~~
   <h1>My First Heading</h1>
   ~~~
   - Section with meta-information (``<head>``):
   ~~~
   <head>
       <meta charset="utf-8">
   </head>
   ~~~
   - Top level element (``<html>``):
   ~~~
   <html>
   </html>
   ~~~
   - Image named ``Team.jpg`` (``<img src="Team.jpg">``):
   ~~~
   <img src="Team.jpg">
   ~~~
   - Paragraph (``<p>``):
   ~~~
   <p>This is the content of my first paragraph.</p>
   ~~~
   - Section (``<section>``):
   ~~~
   <section>
       <h2>My First Section</h2>
       <p>This is the content of my first section.</p>
   </section>
   ~~~
   - Label appearing in the title bar (``<title>``):
   ~~~
   <title>My First Title</title>
   ~~~
   - Link to other pages (``<a>``):
   ~~~
   <a href="https://www.w3schools.com">W3Schools.com</a>
   ~~~
   - Comment:
   ~~~
   <!-- This is a comment -->
   ~~~
   - Head with title and meta elements:
   ~~~
   <head>
       <title>My First Title</title>
       <meta charset="utf-8">
   </head>
   ~~~

## Css

1. Name the components of a css rule properly: selector, property, value
2. Use combinators properly: direct child, descendant, adjacent sibling, sibling:
   ~~~
   h1 ~ p (p is a direct child of h1)
   h1 + p (p is a sibling of h1)
   div p (p is a descendant of div)
   div > p (p is a sibling of div)
   ~~~
3. Specify colors by color names and in hexadecimal notation:
   ~~~
   color: red;
   color: #ff0000;
   ~~~
4. Declarations for color, background color:
   ~~~
   color: red;
   background-color: yellow;
   ~~~
5. Pseudo classes for the ``<a>`` element:
   ~~~
   a:link { color: red; }
   a:visited { color: green; }
   a:hover { color: yellow; }
   ~~~
6. Declaration for background image:
   ~~~
   background-image: url("image.jpg");
   ~~~
7. Declaration for text alignment (left, right, center, justify):
   ~~~
   text-align: center;
   ~~~
8. Declaration for text decoration (overline, underline, line-through):
   ~~~
   text-decoration: underline;
   ~~~
9. Declaration for text transformation (uppercase, lowercase, capitalize):
   ~~~
   text-transform: uppercase;
   ~~~
10. Identify the difference between serif and sans-serif fonts: serif fonts have these serifs at the end of letters
11. Declarations for font families:
   ~~~
   font-family: serif;
   ~~~
12. Declarations for font style normal and italic:
   ~~~
   font-style: italic;
   ~~~
13. Declarations for font sizes:
   ~~~
   font-size: 16px;
   ~~~
14. Declarations for font weights:
   ~~~
   font-weight: bold;
   ~~~
