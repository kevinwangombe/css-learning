# CSS Learning Project

A hands-on exploration of modern CSS functions including `calc()`, `min()`, and `max()` for responsive and dynamic styling.

## 📚 Topics Covered

### CSS Functions
- **`calc()`** - Mathematical calculations in CSS
- **`min()`** - Setting upper limits for responsive design
- **`max()`** - Setting lower limits for minimum sizes

### Concepts Demonstrated
- Mixing different units (rem, px, %, vw)
- Responsive typography
- Dynamic spacing and margins
- Flexible layouts with constraints

## 🎯 Learning Objectives

This project demonstrates:
- How to use `calc()` to combine relative and fixed units
- Creating responsive designs that adapt to screen size
- Setting intelligent boundaries with `min()` and `max()`
- Practical applications of modern CSS functions

## 📁 Project Structure

```
├── index.html          # HTML structure with demonstration elements
├── cssfunctions.css    # CSS with function examples
└── README.md          # This file
```

## 🔍 Code Examples

### calc() Function
```css
padding: calc(1rem + 10px); /* Combines rem and px units */
width: calc(100% - 40px);   /* Percentage minus fixed value */
```

### min() Function
```css
width: min(calc(100% - 40px), 800px);
/* Uses smaller value: responsive but capped at 800px */
```

### max() Function
```css
width: max(calc(300px + 2rem), 400px);
/* Uses larger value: minimum 400px width guaranteed */
```

## 🚀 How to Use

1. Clone the repository
2. Open `index.html` in your browser
3. Resize your browser window to see the responsive behavior
4. Inspect the elements to see the calculated values

## 🌐 Live Demo

Visit the live version: [CSS Learning Demo](https://kevinwangombe.github.io/css-learning/)

## 🛠 Technologies Used

- HTML5
- CSS3 (Modern CSS Functions)
- Git & GitHub

## 📖 References

- [MDN Web Docs - calc()](https://developer.mozilla.org/en-US/docs/Web/CSS/calc())
- [MDN Web Docs - min()](https://developer.mozilla.org/en-US/docs/Web/CSS/min())
- [MDN Web Docs - max()](https://developer.mozilla.org/en-US/docs/Web/CSS/max())

---

**Part of The Odin Project curriculum** - Building modern web development skills through hands-on practice.
