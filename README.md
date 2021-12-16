# Cascading_Style_Sheets


|                         |                         |                         |                         |                         |
| ----------------------- | ----------------------- | ----------------------- | ----------------------- | ----------------------- |
| [CSS Tutorial       ]() | [CSS Simplified PPT ]() | [ CSS Introduction  ](https://github.com/hacker-404-error/Cascading_Style_Sheets#css-introduction) | [ CSS Syntax        ](https://github.com/hacker-404-error/Cascading_Style_Sheets#css-syntax) | [ CSS Selectors     ](https://github.com/hacker-404-error/Cascading_Style_Sheets#css-selectors) |
| [CSS How To         ](https://github.com/hacker-404-error/Cascading_Style_Sheets#how-to-add-css) | [ CSS Comments      ]() | [ CSS Colors        ]() | [ CSS Backgrounds   ]() | [ CSS Borders       ]() |
| [CSS Margins        ]() | [ CSS Padding       ]() | [ CSS Height/Width  ]() | [ CSS Box Model     ]() | [ CSS Outline       ]() |
| [CSS Text           ]() | [ CSS Fonts         ]() | [ CSS Icons         ]() | [ CSS Links         ]() | [ CSS Lists         ]() |
| [CSS Tables         ]() | [ CSS Display       ]() | [ CSS Max-width     ]() | [ CSS Position      ]() | [ CSS Z-index       ]() |
| [CSS Overflow       ]() | [ CSS Float         ]() | [ CSS Inline-block  ]() | [ CSS Align         ]() | [ CSS Combinators   ]() |
| [CSS Pseudo-class   ]() | [ CSS Pseudo-element]() | [ CSS Opacity       ]() | [ CSS Navigation Bar]() | [ CSS Dropdowns     ]() |
| [CSS Image Gallery  ]() | [ CSS Image Sprites ]() | [ CSS Attr Selectors]() | [ CSS Forms         ]() | [ CSS Counters      ]() |
| [CSS Website Layout ]() | [ CSS Units         ]() | [ CSS Specificity   ]() | [ CSS !important    ]() | [ CSS Math Functions]() |


# CSS INTRODUCTION
## What is CSS?
```
1-CSS stands for Cascading Style Sheets.
2-CSS is the language we use to style a Web page.
3-CSS describes how HTML elements are to be displayed on screen, paper, or in other media.
4-CSS saves a lot of work. It can control the layout of multiple web pages all at once.
5-External stylesheets are stored in CSS files.
```

# CSS Syntax
<br>
<div align="center">
    <img src="https://www.w3schools.com/css/img_selector.gif" alt="Syntax">
</div>
<br>

```
The selector points to the HTML element you want to style.

The declaration block contains one or more declarations separated by semicolons.

Each declaration includes a CSS property name and a value, separated by a colon.

Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.
```

# CSS SELECTORS
| No. | Types                         | Info                                                            |
| --- | ----------------------------- | ----------------------------------------------------------------|
| 1-  | [Simple selectors         ](https://github.com/hacker-404-error/Cascading_Style_Sheets#simple-selector) | (select elements based on name, id, class)​                      |
| 2-  | [Combinator selectors     ](https://github.com/hacker-404-error/Cascading_Style_Sheets#combinator-selector) | (select elements based on a specific relationship between them)​ |
| 3-  | [Pseudo-class selectors   ](https://github.com/hacker-404-error/Cascading_Style_Sheets#pseudo-class-selector) | (select elements based on a certain state)​                      |
| 4-  | [Pseudo-elements selectors](https://github.com/hacker-404-error/Cascading_Style_Sheets#pseudo-elements-selector) | (select and style a part of an element)​                         |
| 5-  | [Attribute selectors      ](https://github.com/hacker-404-error/Cascading_Style_Sheets#attribute-selectors) | (select elements based on an attribute or attribute value)      |

## SIMPLE SELECTOR
<div align="center">
    <img src="https://github.com/hacker-404-error/Cascading_Style_Sheets/blob/main/Image/CSS%20Simple%20SELECTORS.PNG" alt="Syntax">
</div>
<br>

## COMBINATOR SELECTOR
<div align="center">
    <img src="https://github.com/hacker-404-error/Cascading_Style_Sheets/blob/main/Image/CSS%20Combinators%20SELECTOR.PNG" alt="Syntax">
</div>
<br>

```
Descendant Selector (Space)
The descendant selector matches all elements that are descendants of a specified element.

Child Selector (>)
The child selector selects all elements that are the children of a specified element.

Adjacent Sibling Selector (+)
The adjacent sibling selector is used to select an element that is directly after another specific element.

General Sibling Selector (~)
The general sibling selector selects all elements that are next siblings of a specified element.
```

## PSEUDO-CLASS SELECTOR

```
A pseudo-class is used to define a special state of an element.

like:
Style an element when a user mouses over it
Style visited and unvisited links differently
Style an element when it gets focus


| Selector             | Example               | Example description                                                                            |
| -------------------- | --------------------- | ---------------------------------------------------------------------------------------------- |
| :active              | a:active              | Selects the active link                                                                        |
| :checked             | input:checked         | Selects every checked <input> element                                                          |
| :disabled            | input:disabled	S      | elects every disabled <input> element                                                          |
| :empty               | p:empty               | Selects every <p> element that has no children                                                 |
| :enabled             | input:enabled         | Selects every enabled <input> element                                                          |
| :first-child         | p:first-child         | Selects every <p> elements that is the first child of its parent                               |
| :first-of-type       | p:first-of-type       | Selects every <p> element that is the first <p> element of its parent                          |
| :focus               | input:focus           | Selects the <input> element that has focus                                                     |
| :hover               | a:hover               | Selects links on mouse over                                                                    |
| :in-range            | input:in-range        | Selects <input> elements with a value within a specified range                                 |
| :invalid             | input:invalid         | Selects all <input> elements with an invalid value                                             |
| :lang(language)      | p:lang(it)            | Selects every <p> element with a lang attribute value starting with "it"                       |
| :last-child          | p:last-child          | Selects every <p> elements that is the last child of its parent                                |
| :last-of-type        | p:last-of-type        | Selects every <p> element that is the last <p> element of its parent                           |
| :link                | a:link                | Selects all unvisited links                                                                    |
| :not(selector)       | :not(p)               | Selects every element that is not a <p> element                                                |
| :nth-child(n)        | p:nth-child(2)        | Selects every <p> element that is the second child of its parent                               |
| :nth-last-child(n)   | p:nth-last-child(2)   | Selects every <p> element that is the second child of its parent, counting from the last child |
| :nth-last-of-type(n) | p:nth-last-of-type(2) | Selects every <p> element that is the second <p> element of its parent, counting from the last |
| :nth-of-type(n)      | p:nth-of-type(2)      | Selects every <p> element that is the second <p> element of its parent                         |
| :only-of-type        | p:only-of-type        | Selects every <p> element that is the only <p> element of its parent                           |
| :only-child          | p:only-child          | Selects every <p> element that is the only child of its parent                                 |
| :optional            | input:optional        | Selects <input> elements with no "required" attribute                                          |
| :out-of-range        | input:out-of-range    | Selects <input> elements with a value outside a specified range                                |
| :read-only           | input:read-only       | Selects <input> elements with a "readonly" attribute specified                                 |
| :read-write          | input:read-write      | Selects <input> elements with no "readonly" attribute                                          |
| :required            | input:required        | Selects <input> elements with a "required" attribute specified                                 |
| :root                | root                  | Selects the document's root element                                                            |
| :target              | #news:target          | Selects the current active #news element (clicked on a URL containing that anchor name)        |
| :valid               | input:valid           | Selects all <input> elements with a valid value                                                |
| :visited             | a:visited             | Selects all visited links                                                                      |
```

## Pseudo-Elements Selector
```
A CSS pseudo-element is used to style specified parts of an element.

1-Style the first letter, or line, of an element.
2-Insert content before, or after, the content of an element.

| Selector       | Example         | Example description                                          |
| -------------- | --------------- | ------------------------------------------------------------ |
| ::after        | p::after        | Insert something after the content of each <p> element       |
| ::before       | p::before       | Insert something before the content of each <p> element      |
| ::first-letter | p::first-letter | Selects the first letter of each <p> element                 |
| ::first-line   | p::first-line   | Selects the first line of each <p> element                   |
| ::marker       | ::marker        | Selects the markers of list items                            |
| ::selection    | p::selection    | Selects the portion of an element that is selected by a user |

```


## Attribute Selectors
```
It is possible to style HTML elements that have specific attributes or attribute values.
The [attribute] selector is used to select elements with a specified attribute

| Selector           | Example              | Example description                                                                     |
| ------------------ | -------------------- | --------------------------------------------------------------------------------------- |
| [attribute]        | [target]             | Selects all elements with a target attribute                                            |
| [attribute=value]  | [target=_blank]      | Selects all elements with target="_blank"                                               |
| [attribute~=value] | [title~=flower]      | Selects all elements with a title attribute containing the word "flower"                |
| [attribute=value]  | [lang=en]            | Selects all elements with a lang attribute value starting with "en"                     |
| [attribute^=value] | a[href^="https"]     | Selects every <a> element whose href attribute value begins with "https"                |
| [attribute$=value] | a[href$=".pdf"]      | Selects every <a> element whose href attribute value ends with ".pdf"                   |
| [attribute*=value] | a[href*="w3schools"] | Selects every <a> element whose href attribute value contains the substring "w3schools" |
```    
    
# How To Add CSS

### Three Ways to Insert CSS

There are three ways of inserting a style sheet:

#### [Internal CSS](https://github.com/hacker-404-error/Cascading_Style_Sheets#internal-css-1)
#### [External CSS](https://github.com/hacker-404-error/Cascading_Style_Sheets#external-css-1)
#### [Inline CSS](https://github.com/hacker-404-error/Cascading_Style_Sheets#inline-css-1)

### Internal CSS
```
An internal style sheet may be used if one single HTML page has a unique style.
The internal style is defined inside the <style> element, inside the head section.

For eg-
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
### External CSS
```
1-With an external style sheet, you can change the look of an entire website by changing just one file!
2-Each HTML page must include a reference to the external style sheet file inside the <link> element, 
  inside the head section.

For Eg-
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

```

### Inline CSS
```
An inline style may be used to apply a unique style for a single element.
To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

 For Eg-

Inline styles are defined within the "style" attribute of the relevant element:
<!DOCTYPE html>
<html>
<body>

<h1 style="color:blue;text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

</body>
</html>

```
