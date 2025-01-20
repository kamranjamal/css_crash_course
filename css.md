# Beginner CSS Quick Guide

## Table of Contents
1. [Introduction to CSS](#introduction-to-css)
2. [CSS Syntax](#css-syntax)
3. [Selectors](#selectors)
    - [Universal Selector](#universal-selector)
    - [Type Selector](#type-selector)
    - [Class Selector](#class-selector)
    - [ID Selector](#id-selector)
    - [Attribute Selector](#attribute-selector)
    - [Pseudo-classes](#pseudo-classes)
    - [Pseudo-elements](#pseudo-elements)
4. [CSS Box Model](#css-box-model)
5. [CSS Units](#css-units)
6. [CSS Colors](#css-colors)
    - [Named Colors](#named-colors)
    - [HEX](#hex)
    - [RGB](#rgb)
    - [HSL](#hsl)
7. [Typography](#typography)
    - [Font Properties](#font-properties)
    - [Text Properties](#text-properties)
8. [CSS Layout](#css-layout)
    - [Display](#display)
    - [Positioning](#positioning)
    - [Flexbox](#flexbox)
    - [Grid](#grid)
9. [CSS Styling](#css-styling)
    - [Borders](#borders)
    - [Margins and Padding](#margins-and-padding)
    - [Backgrounds](#backgrounds)
    - [Shadows](#shadows)
10. [Responsive Design](#responsive-design)
    - [Media Queries](#media-queries)
    - [Viewport Units](#viewport-units)
11. [CSS Animations and Transitions](#css-animations-and-transitions)
    - [Transitions](#transitions)
    - [Keyframe Animations](#keyframe-animations)

---

## 1. Introduction to CSS
CSS (Cascading Style Sheets) is used to style and layout web pages, including colors, layouts, and fonts.

---

## 2. CSS Syntax
A CSS rule consists of a selector and a declaration block:
```css
selector {
  property: value;
}
```

---

## 3. Selectors
### Universal Selector
```css
* {
  margin: 0;
  padding: 0;
}
```

### Type Selector
```css
h1 {
  color: blue;
}
```

### Class Selector
```css
.button {
  background-color: green;
}
```

### ID Selector
```css
#header {
  font-size: 20px;
}
```

### Attribute Selector
```css
a[target="_blank"] {
  color: red;
}
```

### Pseudo-classes
```css
a:hover {
  text-decoration: underline;
}
```

### Pseudo-elements
```css
p::first-line {
  font-weight: bold;
}
```

---

## 4. CSS Box Model
Understand the structure of an element:
- Content
- Padding
- Border
- Margin

![CSS Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model/box-model-standard-small.png)

---

## 5. CSS Units
### Absolute Units
- `px`, `cm`, `mm`, etc.

### Relative Units
- `%`, `vw`, `vh`

---

## 6. CSS Colors
### Named Colors
```css
color: red;
```

### HEX
```css
color: #ff5733;
```

### RGB
```css
color: rgb(255, 87, 51);
```

### HSL
```css
color: hsl(10, 100%, 60%);
```

---

## 7. Typography
### Font Properties
```css
font-family: Arial, sans-serif;
font-size: 16px;
font-weight: bold;
```

### Text Properties
```css
text-align: center;
line-height: 1.5;
text-transform: uppercase;
```

---

## 8. CSS Layout
### Display
```css
div {
  display: flex;
}
```

### Positioning
```css
div {
  position: absolute;
  top: 10px;
}
```

### Flexbox
```css
display: flex;
justify-content: center;
align-items: center;
```

### Grid
```css
display: grid;
grid-template-columns: 1fr 1fr;
```

---

## 9. CSS Styling
### Borders
```css
div {
  border: 2px solid black;
}
```

### Margins and Padding
```css
div {
  margin: 10px;
  padding: 10px;
}
```

### Backgrounds
```css
body {
  background-color: lightblue;
  background-image: url('image.jpg');
}
```

### Shadows
```css
div {
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}
```

---

## 10. Responsive Design
### Media Queries
```css
@media (max-width: 600px) {
  body {
    background-color: yellow;
  }
}
```

### Viewport Units
```css
height: 100vh;
width: 100vw;
```

---

## 11. CSS Animations and Transitions
### Transitions
```css
div {
  transition: all 0.3s ease;
}
```

### Keyframe Animations
```css
@keyframes example {
  0% {
    background-color: red;
  }
  100% {
    background-color: blue;
  }
}

div {
  animation: example 5s infinite;
}
