# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on a desktop screen (WARNING: design not yet optimized for mobile)
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Repository URL: [https://github.com/windu80/Frontend-challenge03](https://github.com/windu80/Frontend-challenge03)
- Live Site URL: [https://windu80.github.io/Frontend-challenge03/](https://windu80.github.io/Frontend-challenge03/)

## My process

### Built with

- Sublime Text (code editor)
- normal CSS and HTML

### What I learned

- Use the different font weights (200, 300, etc)
- Specify margin with one, two or three values
- Customize a horizontal rule with the border-style property
- Enter SVG image directly as SVG code in the HTML (SVG inline) (https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Adding_vector_graphics_to_the_Web)
- Change property (fill) of SVG depending on hover state
- Change property of an element when hovering over another element
(https://stackoverflow.com/questions/6867257/is-there-any-way-to-hover-over-one-element-and-affect-a-different-element)
(https://stackoverflow.com/questions/43216520/changing-property-of-an-element-on-hover-of-another-element)
(https://codepen.io/StefanBobrowski/pen/ZeZGmQ)
```css
.eye-icon:hover > g .eye-path {
    fill: #FFF;
}
```
- Display shadow around an element (https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow), with the help also of a shadow generator (https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Backgrounds_and_Borders/Box-shadow_generator)
```css
box-shadow: 0px 30px 50px 50px rgb(12, 23, 41);
```
- Have an image as anchor tag (-> put <img> tag inside <a> tag): https://www.w3schools.com/html/html_links.asp
- Add an opacity element to a color (e.g. hsla(178, 100%, 50%, 0.5) -> 50% opacity) (https://www.w3schools.com/css/css_image_transparency.asp)
```css
.eye-icon:hover {
  background-color: hsla(178, 100%, 50%, 0.5);
}
```
- Know that we have 4 pixels by default between inline-block elements
- Have a color gradient
```css
background-image: linear-gradient(to bottom, hsl(217, 54%, 11%), hsl(217, 54%, 12%));
```

### Useful resources

- [Google Fonts](https://fonts.google.com/) - To get the Outfit font
- [MDN](https://developer.mozilla.org/en-US/)
- [W3schools](https://www.w3schools.com/)
- [Stackoverflow](https://stackoverflow.com/)

