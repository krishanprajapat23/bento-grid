# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size


### Links

- Solution URL: [solution](https://github.com/krishanprajapat23/bento-grid)
- Live Site URL: [live](https://krishanprajapat23.github.io/bento-grid/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS
- CSS Grid
- Flexbox
- Mobile-first workflow


### What I learned

Throughout this project, I gained a deeper understanding of CSS Grid and how to implement responsive designs effectively. One of the key takeaways was mastering grid placement and media queries to adjust layouts for different screen sizes.


```html
<div class="grid-group">
  <div class="grid-item">Item 1</div>
  <div class="grid-item">Item 2</div>
  .......
</div>
```
```css
.grid-group {
  display: grid;
  gap: 2rem;
  grid-template-rows: repeat(10, auto);
  grid-template-columns: repeat(4, minmax(0, 1fr));
}

 .grid-item {
    &:nth-child(1) {
      @media (min-width: 991px){
        grid-row: 1 / 5;
        grid-column: 2 / span 2;
      }
    }
  }

  .........

```



### Continued development

In future projects, I want to explore:

- Advanced CSS techniques.
- Implementing JavaScript to add interactivity.

## Author

- Frontend Mentor - [@krish](https://www.frontendmentor.io/profile/krishanprajapat23)
