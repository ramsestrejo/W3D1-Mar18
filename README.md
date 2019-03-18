# The CSS Box Model

## Topics 
1. Demo of Application 
2. HTML5 semantic
3. Block Level Elements / Inline Level Elements
4. CSS, Reset & Normalization
5. CSS Box Model
6. CSS Debugging in DevTools

## 1. Demo of Application 
https://web.compass.lighthouselabs.ca/projects/w3-tweeter?day_number=w03d1


## 2. Writing Semantic HTML5
Provides meaning and intent to web pages. Assist in communication with browsers, search engines and fellow developers. Examples are (nav, section, article, main, header). They give proper meaning to different sections in HTML documents and no longer depend on multiple and generic divs that add confusion and lead to time consuming troubleshooting.
Other topics discussed:

## 3. Block vs inline Elements
Block elements 'block' the whole row of where they are in the browser , pushing any neighbouring elements down.
Inline elements take only the space that used by their contents, enough to hold itself.
Inline and block element act like block elements but they do not take entire width of the container, allows to set dimensions.
The display property is used to set the block behavior : block, inline, inline-block respectively.


## 4. CSS, Reset & Normalization
Browsers apply a different default CSS to HTML documents. Resetting and normalizing CSS will provide more predictible results.

## CSS Box Model
All HTML elements are considered boxes, many of these play the role of containers of other elements, and the way the width and height is calculated in the document becomes even more important. The box model setting determines how browser renders elements on the screen.

## Why is CSS Box Model important?
In order to set width and height of an element correctly in all browsers, and set expectations for sizing elements in the document. By default, the width and height of the content area is set via CSS and the total width and height for its "box" is determined by adding padding and border widths.

Actual visible/rendered width of an element's box = content width + padding + border 

Actual visible/rendered height of an element's box = content height + padding + border 

[Some history about the box model](https://css-tricks.com/box-sizing)
In conclusion, the box model is defined by the box-sizing property:
content-box is the default behaviour (element box dimensions are calculated by adding padding and border value)
border-box is equivalent to IE's “quirks mode" (element's padding & border are included in the box's width & height)

[Demo of the box model](http://guyroutledge.github.io/box-model)



## Semantic HTML5
We used this demo to show the use of semantic HTML elements 


  