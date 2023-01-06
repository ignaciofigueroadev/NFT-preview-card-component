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
  - [Continued development](#continued-development)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![NFT preview card component](/images/screenshot.png)


### Links

- Solution URL: [My solution](https://github.com/FigueroaIgnacio/NFT-Preview-Card-Component)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5
- CSS 
- BEM 
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to create an overlay with the over effect, It was very funny 😊

```css
.image__container {
    position: relative;
    width: 100%;
    background-color: var(--Cyan);
    border-radius: .75em;
    transition: .5s ease;
}

.card__img {
    border-radius: .5em;
}

.card__img--view {
    width: 3em;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    display: none;
}

.card__img:hover {
    opacity: 0.5;
    cursor: pointer;
}
 
.image__container:hover .img__card--overlay  + .card__img--view {
    display: block;
}    
```

I've been practicing BEM methodology, if you have feedback, you're welcome


### Continued development

I want to do more of those cards with overlay effect becouse I thougth it was cool.
And I want to improve on my BEM metodologhy becouse I'm not sure I´m doing it right

I´m going to start to use SASS in next projects 


## Author
- Frontend Mentor - [@ignaciofigueroadev](https://www.frontendmentor.io/profile/ignaciofigueroadev)
