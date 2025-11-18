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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop screenshot](./images/desktop-screenshot.png)
![Mobile screenshot](./images/mobile-screenshot.png)

### Links

- Solution [here](https://github.com/odunlemi/product-preview-component)
- Live Site [here](https://odunlemi.github.io/product-preview-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Cursor

### What I learned

This one was an experiment in using Cursor. I've been learning about its integrated AI environment, and how I can speed up my workflow with AI. Yes, I should be coding a simple frontend challenge by hand (and I definitely [have](https://www.frontendmentor.io/profile/odunlemi)), it's just so good to see how efficient using AI can prove.

My agent choice was set to `Auto`, and it used some curious choices, like in the html:

```html
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
```

Which it explained as:

> Preconnect hints tell the browser to establish early connections to external domains before they’re needed.

1. `<link rel="preconnect" href="https://fonts.googleapis.com">`
   Starts a connection to Google Fonts’ API server early.

2. `<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>`
   Starts a connection to Google’s font CDN.
   crossorigin is required because fonts are loaded cross-origin.

They help by reducing latency, by setting up DNS, TCP, and TLS before the font request and can make fonts load faster, improving perceived performance.

The CSS was how I'd write it. Most units were in `rem`:

```css
body {
  padding: 1.75rem 1rem;
}
```

### Continued development

No continued development as it executed it perfectly, the webpage matches the designs given and is responsive across all screen sizes.

### Useful resources

- [Agents | Cursor Learn](https://cursor.com/learn/agents) - This helped me onboard to using the Cursor environment properly.

- [Lengths](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Values_and_units#lengths) - Covers the relative length units; em and rem.

## Author

- Website - [Abiodun Longe](https://odunlemi.github.io/)
- Frontend Mentor - [@odunlemi](https://www.frontendmentor.io/profile/odunlemi)
- X - [@odunlemi](https://www.x.com/odunlemi)
