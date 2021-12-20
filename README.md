# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

![Design preview for Stats preview card component](./images/desktop-preview.jpg)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
<!-- - [Acknowledgments](#acknowledgments) -->

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size


### Links


- [Frontend Mentor - solution URL](https://www.frontendmentor.io/solutions/stats-card-component-using-flexbox-and-scss-D4KyAx5Nb)
- [Live Demo](https://stfnpczk.github.io/stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- BEM methodology
- SCSS
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- `<picture>` : handy html tag to switch out images based on the viewport width.

```html
<picture>
  <source
    srcset="./images/image-header-desktop.jpg"
    media="(min-width: 1440px)"
  />
  <img
    src="./images/image-header-mobile.jpg"
    alt=""
  />
</picture>
```

- `mix-blend-mode` : this css property can be used together with opacity like an image filter to blend with the parent element.

```scss
.parentElement {
  background-color: hsl(277, 64%, 61%);

  img {
    mix-blend-mode: multiply;
    opacity: 0.79;
  }
}
```

### Continued development

- At a later point, I will further look into how to build responsive websites with less media queries. This article from [css-tricks](https://css-tricks.com/responsive-layouts-fewer-media-queries/) by Temani Afif looks very promising to help with that.

### Useful resources



- [W3 schools reference -> picture tag ](https://www.w3schools.com/tags/tag_picture.asp) 
- [MDN docs -> mix-blend-mode](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode) 
- [Css-tricks article -> fewer media queries](https://css-tricks.com/responsive-layou%20ts-fewer-media-queries/)

## Author

- Frontend Mentor - [@stfnpczk](https://www.frontendmentor.io/profile/stfnpczk)

<!-- - Website - [Add your name here](https://www.your-site.com) -->
<!-- - Twitter - [@yourusername](https://www.twitter.com/yourusername) -->

<!-- ## Acknowledgments
**ADD TEXT**
This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit. -->
