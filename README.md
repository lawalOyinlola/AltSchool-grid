# Solution to AltSchool Grid Component Project

![2 * 4](https://res.cloudinary.com/drnqdd87d/image/upload/v1693414503/altschool/oxtmohuvcsswye05wppl.png)

Here's what the DOM structure looks like, for a 2×4 grid:

```html
<div class="grid">
  <div class="row">
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
  </div>
  <div class="row">
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
  </div>
</div>
```

My mission was to replicate this structure, but for a variable number of rows and columns.

Acceptance criteria:

- I've been given the template for a Grid component, which was provided with a numRows prop for the number of rows, and a numCols prop for the number of columns.
- There is X divs with a class of row, where X is equal to the numRows prop.
- Inside each row, there is Y divs with a class of cell, where Y is equal to the numCols prop.
- I used the provided range function to solve this problem.
- **There wasn't be any key-related warnings in the console.**
