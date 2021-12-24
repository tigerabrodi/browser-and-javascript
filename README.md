# Browser, Document, DOM

- The Browser Object Model (BOM) represents additional objects provided by the browser (host environment) for working with everything except the document.

- Every HTML tag is an object. Tags are the core of an HTML document.

- Everything in HTML, even comments, becomes a part of the DOM.

- The `elem.matches(css)` does not look for anything, it merely checks if elem matches the given CSS-selector. It returns true or false.

- The method `elem.closest(css)` looks for the nearest ancestor that matches the CSS-selector. The elem itself is also included in the search.

- Methods containing `getElementsBy` return a live collection, meaning they always reflect the current state of the document, and updates automatically when changes happen.

- The root of the DOM node's hierachy is EventTarget, which is an object that represents a target to which an event can be triggered whenever something has happened.

- Get more information of a Node: nodeType, nodeName, tagName, outerHTML, nodeValue, data, textContent.

- We can create more properties on the DOM, and not only have to use the existing ones.

- Use `dataset` to set `data-*` attributes progrmatically, i.e. good for ids when looping and returning items.

- Creating an element: createElement, createTextNode.

- Clone node via cloneNode.

- DocumentFragment is a special DOM node to be used as a wrapper around lists of nodes. When outputted on the DOM, it sort of "blends in", rather used programatically to group items, and insert them onto the DOM as a group.

- Use getComputedStyle to get an object which contains the resolved values, styles, of a node/element.
