---
layout: page
title: "Interactive elements"
permalink: /controls/interactive-elements/
---
<link rel="stylesheet" href="/assets/css/style.css?v=07f9abc06ad55cffb2433692575c223659db012e" media="screen"><link rel="stylesheet" href="/css/style.css">
<a class="back-link" href="https://shoshiko.github.io">Back to content</a>
   
<div class="inner" markdown="1">

# Interactive elements

The list of interactive elements that are tabbable is:

- Anchors, when the href attribute is present,
  
- <button>,
  
- <input> and <textarea>, with an accompanying label,
  
- <select>,
  
- <details>,
  
- <audio> and <video> when controls are present,
  
- <object>, depending on how it is used,
  
- any element with scroll overflow in Firefox,
  
- any element with the contenteditable attribute applied to it, and
  
- any element with the tabindex attribute applied to it (more on this one in a bit).

&nbsp;
  
An interactive element gains focus when:

- It has been navigated to via the Tab key, 

- it is clicked on, following an anchor that links to another focusable element,
or focus is programmatically set through element.focus() in JavaScript.

Focus is analogous to hovering over an element with your mouse cursor, in that you’re identifying the thing you want to activate. It’s also why visually obvious focus styles are so important.

&nbsp;

[source](https://css-tricks.com/focus-management-and-inert/- ){:target="_blank"}

</div>