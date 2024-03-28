# Selectos
Selectors are a key part of CSS (Cascading Style Sheets) used to target HTML elements for styling. They enable developers to apply styles selectively to specific elements or groups of elements within a web page. Here's a concise overview of CSS selectors and their types:

1. Type Selectors:
   - Target elements based on their tag names.
   - Example: `p { color: blue; }` targets all `<p>` elements to make their text color blue.

2. Class Selectors:
   - Target elements based on their class attribute.
   - Prefixed with a dot (.) followed by the class name.
   - Example: `.highlight { background-color: yellow; }` applies a yellow background color to all elements with the class "highlight".

3. ID Selectors:
   - Target elements based on their id attribute.
   - Prefixed with a hash (#) followed by the id name.
   - Example: `#header { font-size: 24px; }` sets the font size of the element with the id "header" to 24 pixels.

4. Attribute Selectors:
   - Target elements based on the presence or value of their attributes.
   - Enclosed in square brackets ([]).
   - Example: `input[type="text"] { border: 1px solid black; }` applies a black border to all `<input>` elements with a type attribute equal to "text".

5. Pseudo-classes:
   - Target elements based on their state or position.
   - Preceded by a colon (:).
   - Example: `a:hover { color: red; }` changes the color of links to red when hovered over.

6. Pseudo-elements:
   - Target specific parts of an element.
   - Also preceded by a colon (:).
   - Example: `p::first-line { font-weight: bold; }` makes the first line of all `<p>` elements bold.

7. Combinators:
   - Combine multiple selectors to define a new selection.
   - Types include descendant combinator (space), child combinator (>), adjacent sibling combinator (+), and general sibling combinator (~).
   - Example: `div p { color: green; }` applies the color green to all `<p>` elements that are descendants of a `<div>` element.

Understanding and effectively using CSS selectors is crucial for creating well-styled and structured web pages. Each type of selector offers unique ways to target elements, providing flexibility and precision in styling web content.
