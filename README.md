# CSS Mastery 🚀

A structured collection of CSS concepts, examples, and practical notes created while preparing for **MAANG-level Software Engineering interviews and real-world frontend development**.

This repository focuses on understanding **how CSS actually works**, not just memorizing properties.

---

## 📚 What This Repository Covers

### 1. CSS Fundamentals
- How CSS works in the browser
- DOM, CSSOM and Render Tree
- Critical Rendering Path
- Ways to apply CSS
- CSS At-rules

### 2. Selectors
- Universal selector
- Element selector
- Class selector
- ID selector
- Attribute selectors
- Descendant selector
- Child selector
- Adjacent sibling selector
- General sibling selector
- Grouping selectors
- Pseudo-classes
- Pseudo-elements

### 3. Cascade & Specificity
- CSS cascade
- Specificity
- Source order
- Inline vs internal vs external CSS
- `!important`
- Cascade layers
- Understanding why one CSS rule wins over another

### 4. Inheritance
- Inherited properties
- Non-inherited properties
- `inherit`
- `initial`
- `unset`
- `revert`

### 5. CSS Units
- `px`
- `%`
- `em`
- `rem`
- `vw`
- `vh`
- `vmin`
- `vmax`
- `ch`
- `fr`
- `deg`
- `s`
- `ms`

### 6. CSS Math Functions
- `calc()`
- `min()`
- `max()`
- `clamp()`
- `minmax()`

### 7. Box Model
- Content
- Padding
- Border
- Margin
- `box-sizing`
- `content-box`
- `border-box`

### 8. Flexbox
- Main axis and cross axis
- `flex-direction`
- `justify-content`
- `align-items`
- `align-content`
- `flex-wrap`
- `gap`
- `flex-grow`
- `flex-shrink`
- `flex-basis`
- `flex`
- `align-self`
- `order`

### 9. CSS Grid
- Grid container and items
- Rows and columns
- Grid lines
- Grid tracks
- Grid cells
- Grid areas
- `fr`
- `repeat()`
- `minmax()`
- `auto-fit`
- `auto-fill`
- Spanning rows and columns
- Implicit grids
- Grid alignment

### 10. Positioning
- `static`
- `relative`
- `absolute`
- `fixed`
- `sticky`
- `inset`
- Positioning relative to containing blocks
- Absolute centering
- Practical layering use cases

### 11. Stacking Context & `z-index`
- Stacking order
- Stacking contexts
- `z-index`
- Parent vs child stacking contexts
- Common stacking-context creators
- `isolation: isolate`
- Debugging `z-index` issues

### 12. Responsive Design
- Media queries
- Breakpoints
- Mobile-first CSS
- `min-width`
- `max-width`
- Orientation queries
- Dark mode
- Reduced motion
- Hover and pointer capabilities
- Container queries
- Fluid responsive layouts

### 13. Typography
- `font-family`
- `font-size`
- `font-weight`
- `font-style`
- `line-height`
- `text-align`
- `letter-spacing`
- `word-spacing`
- `text-transform`
- `text-decoration`
- `text-indent`
- `text-shadow`
- Responsive typography
- `clamp()`
- Text overflow
- `white-space`
- `text-overflow`
- `@font-face`
- Web fonts and `font-display`
- Readable text widths

### 14. Backgrounds, Gradients & Images
- Background colors
- Background images
- `background-size`
- `background-position`
- `background-repeat`
- Background shorthand
- Linear gradients
- Radial gradients
- Conic gradients
- Gradient overlays
- Multiple backgrounds
- `background-attachment`
- `object-fit`
- `object-position`
- Responsive images

### 15. Borders & Shadows
- Border styles
- Border width and color
- Individual borders
- `border-radius`
- Circular elements
- `outline`
- `box-shadow`
- Inset shadows
- Multiple shadows
- `text-shadow`
- Accessible focus indicators

### 16. Transitions
- CSS transitions
- Transition properties
- Duration
- Delay
- Timing functions
- `cubic-bezier()`
- Transition shorthand
- Performance-friendly transitions
- `prefers-reduced-motion`
- Transition vs animation

### 17. Animations & Keyframes
- `@keyframes`
- `from` / `to`
- Percentage-based keyframes
- Animation duration
- Timing functions
- Delay
- Iteration count
- Infinite animations
- Animation direction
- Fill mode
- Play state
- Multiple animations
- Loading spinners
- Animation performance
- Reduced-motion accessibility

---

## 🎯 Engineering Focus

This repository is not only focused on learning CSS syntax.

The goal is to understand CSS from an **engineering perspective**, including:

- Maintainable CSS
- Responsive layouts
- Browser rendering
- Performance
- Accessibility
- Animation performance
- Component isolation
- Debugging
- Real-world layout patterns
- Interview concepts
- Production best practices

---

## ⚡ Performance Principles

Some important principles covered throughout the examples:

- Prefer `transform` and `opacity` for animations.
- Avoid unnecessary layout-triggering animations.
- Use responsive images where appropriate.
- Optimize image formats and sizes.
- Avoid unnecessarily large background images.
- Use readable and maintainable selectors.
- Avoid excessive specificity.
- Prefer fluid layouts before adding many breakpoints.
- Respect `prefers-reduced-motion`.
- Use semantic HTML along with CSS.
- Avoid removing visible focus indicators without providing an accessible replacement.

---

## 🧠 Important Mental Models

### CSS Rendering

```text
HTML
 ↓
DOM

CSS
 ↓
CSSOM

DOM + CSSOM
 ↓
Render Tree
 ↓
Style Calculation
 ↓
Layout
 ↓
Paint
 ↓
Composite
 ↓
Screen