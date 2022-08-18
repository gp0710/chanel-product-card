# Product Preview Card

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [click here](https://github.com/gp0710/chanel-product-card)
- Live Site URL: [click here](https://gp0710.github.io/chanel-product-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Instead of using img tags to add images via HTML, the background-image property can be used to configure the image via CSS instead. There is one caveat, however. A div will have to be prepared beforehand, and the width and height values will have to be added to the corresponding selectors. In addition, sometimes the image can be too big for the div. In cases like those, background-size: 100% 100% will help the background image be contained in the div.

Border radius can also be added in the CSS with the background image property!

```html
<div class="hero-image">
  </div>
```
```css
  div.hero-image {
    background-image: url(images/image-product-mobile.jpg);
    max-width: 100%;
    height: 250px;
    background-size: 100% 100%;
}
```

### Continued development

One day I hope to be super comfortable enough with CSS that when I use a preprocessor like SASS, I won't get confused and lost.

### Useful resources

- [hslpicker](https://hslpicker.com/#173127) - I used the hsl picker to set the color from clicking the "Add to Cart" button.

- [stackoverflow](https://stackoverflow.com/questions/8200204/fit-background-image-to-div) - This question was asked 10 years ago, but is still applicable today. It's how I was able to fit the background image within a div.

- [stackoverflow](https://stackoverflow.com/questions/14353777/border-radius-on-background-image) - border radius on background image
