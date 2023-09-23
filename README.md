# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshots

![./images/screenshot-mobile.png](./images/screenshot-mobile.png)
![./images/screenshot-desktop.png](./images/screenshot-desktop.png)

### Links

- Solution URL: [https://github.com/harnettd/single-price-grid-component](https://github.com/harnettd/single-price-grid-component)
- Live Site URL: [https://harnettd.github.io/single-price-grid-component/](https://harnettd.github.io/single-price-grid-component/)

## My process

### Built with

- HTML5
- CSS including CSS Grid using OOCSS
- Sass

### What I learned

In completing this project, I learned how to set up a simple two-dimensional, repsonsive
layout using CSS Grid, i.e.,

```css
.card {
  display: grid;
  grid-template-columns: 50% 1fr;
  grid-template-rows: auto auto;
}

.hero-area {
  grid-column: 1 / 3;
  grid-row: 1 / 2;
}

.price-area {
  grid-column: 1 / 2;
  grid-row: 2 / 3;
}

.features-area {
  grid-column: 2 / 3;
  grid-row: 2 / 3;
}
```

### Continued development

For this project, I used a very simple CSS Grid layout. To handle more complicated layouts,
I'll need to study more advanced CSS Grid.

### Useful resources

- [CSS Grid Layout Module](https://www.w3schools.com/css/css_grid.asp) - This W3Schools webpage 
served as my first introduction to CSS Grid.

## Author

- Github - [Derek Harnett](https://github.com/harnettd)
- Frontend Mentor - [@harnettd](https://www.frontendmentor.io/profile/harnettd)

## Acknowledgements

- Thanks to [Frontend Mentor](https://www.frontendmentor.io/) for posting this challenge.
