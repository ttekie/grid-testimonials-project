# Frontend Mentor - Testimonials grid section solution

## Table of contents

- [Overview](#overview)
- [The challenge](#the-challenge)
- [Screenshot](#screenshot)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

[solution screenshot](./images/grid-testimonials.png)

### Links

[Solution URL](https://github.com/ttekie/grid-testimonials-project)
[Live Site URL](https://cosmic-bubblegum-ac83f3.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned
In this project I was able to apply css grid to work on the layout part of the web page. I learned how helpful grid is when it comes to the layout part of the web development. Here are some of the css code that I applied in this project that I am proud of. "Information won't stick with out practice!"

```css
.main-container {
   display: grid;
   grid-template-columns: repeat(4, 15rem);
   grid-template-rows: auto auto;
   grid-auto-flow: dense;
   grid-gap: 1.5rem;
   justify-content: center;
   align-content: center;
   height: 100vh; 
}
@media (max-width: 28.75rem) {
   .main-container {
      grid-template-columns: 1fr;
      grid-template-rows: auto;
      grid-template-areas: "first-item"
                           "second-item"
                           "third-item"
                           "fourth-item"
                           "fifth-item";
      height: 100%;
      margin: 3rem 0;
      padding: 0 1.5rem;
   }
```
### Useful resources

- [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - This complete css grid guide is the most helpful resource I found from css-tricks. please check it out, if you are looking for a good resource on css grid.
- [wes bos css grid course](https://courses.wesbos.com/account/access/6239259594de5257d1dc70a5) - wes bos css grid course is also one of the best course I found. you can check it out.

## Author

- Website - [Tesfalem Tekie](https://ttekie.github.io/portfolio/)
-  Frontend Mentor - [@ttekie](https://www.frontendmentor.io/profile/ttekie)
- Github - [@ttekie](https://github.com/ttekie)

## Acknowledgments

I would like to thank Frontend mentor for all the challenges they provided for the front end developers!

