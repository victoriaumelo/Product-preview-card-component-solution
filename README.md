# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL:(https://github.com/victoriaumelo/Product-preview-card-component-solution)
- Live Site URL:(https://victoriaumelo.github.io/Product-preview-card-component-solution/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

```html
<picture>
 <img class="desktop" src="images/image-product-desktop.jpg" alt="">
 <img class="mobile" src="images/image-product-mobile.jpg" alt="">
</picture> for easy ecustomization of images
```
 ```css
@media only screen and (max-width:641px){
 for workig on mobile.

 .card-img .mobile {
       max-width: 100%;
       height: auto;
       display: block;
  }
  .card-img .desktop {
     display: none;
  } for editing two different pictures; display:none(to hide image), display:block(to show image)
}
```

### Continued development

- CSS Flexbox
- CSS Grid
- Working with @media query

### Useful resources

- [W3 schools](https://www.w3schools.com/css/css3_flexbox_container.asp) - This helped me learn how to use justify-content and text-direction. I really liked this site and will use it going forward.
- [Css froggy game](https://flexboxfroggy.com/) - This is an amazing article which helped me finally understand CSS Flexbox. I'd recommend it to anyone still learning this concept.

## Author

- LinkedIn - [Victoria Umelo](https://www.linkedin.com/mwlite/in/umelo-victoria-b38927283)
- Frontend Mentor - [@victoriaumelo](https://www.frontendmentor.io/profile/victoriaumelo)

## Acknowledgments

I'm particularly thankful for my accountability partner, Saheedat.
