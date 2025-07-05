# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.JPG)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/product-preview-card-component-yKtxpyw_NX](https://www.frontendmentor.io/solutions/product-preview-card-component-yKtxpyw_NX)
- Live Site URL: [https://product-preview-card-component-phi-vert.vercel.app/](https://product-preview-card-component-phi-vert.vercel.app/)

### Built with

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) - For styles

### What I learned

I learned how to use the `<picture>` element for the first time to serve **responsive images**. I had never that element before.

```html
<picture>
  <source media="(min-width: 768px)" srcset="./images/image-desktop.jpg" />
  <img
    src="./images/image-mobile.jpg"
    alt="Responsive product image"
    class="w-full h-auto"
  />
</picture>
```

### Useful resources

- [Tailwind Play CDN](https://tailwindcss.com/docs/installation/play-cdn) – This was my starting point for using Tailwind without setting up a full build process. It made it really easy to experiment and see results instantly, which was super helpful.

- [Tailwind Cheat Sheet – Nerdcave](https://nerdcave.com/tailwind-cheat-sheet) - This cheat sheet was incredibly useful for quickly looking up class names and syntax while working on the project. It's a great reference to have open alongside your code.

## Author

- Frontend Mentor - [@mubarakik](https://www.frontendmentor.io/profile/mubarakik)
- GitHub - [@mubarakik](https://github.com/mubarakik)
- LinkedIn - [@mubaraka-kikonyogo](https://www.linkedin.com/in/mubaraka-kikonyogo-950010271)
- X - [@mubarakik\_](https://twitter.com/mubarakik_)
