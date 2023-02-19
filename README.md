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
- [Author](#author)


## Overview
HTML5, CSS, and flexbox were used in designing this site, to get it looking as close to the design files as possible.  

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./Screenshot%202023-02-19%20at%2010-06-39%20Frontend%20Mentor%20NFT%20preview%20card%20component.png)


### Links

- Solution URL: [https://github.com/rdpinkst/nft-preview-card-component-main]
- Live Site URL: [https://rdpinkst.github.io/nft-preview-card-component-main/]

## My process
Initially I designed the HTML5 markup and then styled the page using CSS, working on making the site look as close to the design as possible.  

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox


### What I learned

Completing this challenge I learned that in order to get the hover effect over the picture, a div was needed like the html below:

```html
<div class="hover-image-and-display">
  <img src="image source" alt="alt of image">
</div>
```

Initially I thought I would put the view image in an image tag without a div surrounding it.  Then when the cursor hovered over the image div it would change background to the desired color, add an opacity, and set the view image tag to display: block.  Initially that way of thinking worked, but when the cursor hovered over the view image the background and opacity disappeared.  The way I solved that was through creating a div to surround the view image and with the hover effect display that div.


## Author

- Frontend Mentor - [@rdpinkst](https://www.frontendmentor.io/profile/rdpinkst)

