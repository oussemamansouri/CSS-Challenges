 # Challenge 16: CSS Pseudo-elements

In this challenge, you'll practice using CSS pseudo-elements to style specific parts of elements.

## Instructions:
1. Style the first letter of a paragraph with the class `.intro` to have:
   - Red color (`#ff0000`)
   - A font size of `xx-large`

2. Style the first line of all paragraphs to:
   - Have blue color (`#0000ff`)
   - Be displayed in `small-caps`

3. Use the `::before` pseudo-element to insert a piece of content before each `<h1>` element:
   - Insert the text "Welcome: " before the heading.

4. Style the selection text within a paragraph to:
   - Have a red color when selected.
   - A yellow background when selected.

## Example:
```html
<h1>Heading Example</h1>
<p class="intro">This is a paragraph where the first letter is styled differently, and the first line is styled in a unique way.</p>
<p>This is another paragraph to apply the pseudo-elements on!</p>
```
## Expected Outcome:

- The first letter of the `.intro` paragraph should appear larger and red.
- The first line of all paragraphs should be blue and in small-caps.
- A "Welcome: " text should appear before every `<h1>` element.
- When any text within a paragraph is selected, the selected text should have a red font color and yellow background.

Good luck!
