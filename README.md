# Midterm Study Guide

The midterm will be during class using Sakai. It will include questions
from MEJO-487 material along with the new material from class so far.

The review is organized by topic below.

## HTML

What does HTML stand for?

What do these basic tags do / how are they used:

- DOCTYPE
- html
- head
- body
- p
- video
- a
- div
- section
- aside
- select
- ul
- img
- script
- link
- br
- canvas
- textarea
- ol
- strong
- svg
- em
- span
- audio
- form
- dl
- table
- article
- tr
- input
- td
- thead
- tbody
- tfoot
- footer
- header
- nav
- section
- label

What these attributes used for (and which tags they can be used on):

- src
- href
- class
- alt
- style
- type
- required
- action
- method
- placeholder
- id

Basic form elements:

- select
- radio
- checkbox
- input

How to make a comment in HTML.

How to style text with tags.

How to use the style attribute.

How to make links open in a new window.

## CSS

What does CSS stand for?

What is a selector is and how to select elements by tag name, class and id.

What `!important` does.

How to make a comment in CSS.

What's the difference between padding and margin?

How to link a stylesheet to an HTML page.

How to write inline CSS in an HTML page

- style tag
- style attribute

Units:

- %
- em
- rem
- pt
- px
- vh
- vw

How to use the basic styles to:

- create a border
- border styles (colors, line types)
- change the font
- change the background color
- change the font color
- make text bold
- make links without an underline
- use flexbox / flex direction

How compound selectors work:

- div
- div p
- div > p
- .foo
- div.foo
- div .foo

## SVG

What does SVG stand for?

What tag is used to add SVG to a web page?

What is xmlns?

What format SVG is written in (hint: it's not HTML but it can be put in HTML)

The basic elements we've used so far:

- circle
- ellipse
- line
- path

The common attributes of the elements we've used

- stroke
- fill
- r
- x2
- cx
- y2
- cy
- x1
- rx
- ry
- y1
- d

Path commands:

- M
- L
- Q

## JavaScript

What does ES stand for?

What do people usually mean when they say ES6?

What tag do we use to put JS inline in the HTML?

What tag do we use to include external JS in HTML?

How do you make a variable?

The difference between `var a = new Array(1, 2, 3)` & `var a = [1, 2, 3]`
(which one is a literal)?

---

How to use a template literal to insert a variable:

```
var x = "World";
console.log(WHATGOESHERE)
```

to get the output:

```
Hello World
```

---

Server side JS and client side have access to different global variables / objects
functions:

- window
- navigator
- console
- process
- document
- setTimeout

What the difference between these keywords are:

- var
- let
- const

What is an arrow function?

---

What's the difference between these four functions?

```
function foo () {
    return "foo"
}
```

```
var foo = function () {
    return "foo"
}
```

```
var foo = () => "foo";
```

```
var foo = () => { return "foo" };
```

---

What's the difference between `true == 1` and `true === 1`?

What are the return types of `[].forEach(x => x)` and `[].map(x => x)`?

How can you play with JS in the chrome browser?

How can you play with JS on your laptop without a browser?
