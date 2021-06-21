# Stats-preview👊🏾

Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help me improve my coding skills by building realistic projects.

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

## Overview

### The challenge

 - Build the Stats preview card component making it look close to the designs given for mobile and laptop as I possibly can. Let's do it👊🏾😉

- View the optimal layout depending on their device's screen size

### Screenshot

![](images/1440preview.png)
Image preview showing grid use in laptop view of the stat card

![](images/375mobilepreview.png)
Preview of mobile view of card ...didn't know how to effectivly deal with the margins and width of the divs used ...
Ended up using a bunch of @medias for this
### Links

- Solution git URL: (https://issagoodlifeinc.github.io/stats-preview/)
- Live Site URL:(https://issagoodlifeinc.github.io/stats-preview/)

## My process
  #started with the HTML markup of the stat card
  Completed the html this time not using span too much as compared to previous solutions

  #Then dealt with css first declaring variables used for the colors provided for the projects
  Designed in desktop view first then mobile responsive last
  Used too much @media in this project which is not ideal ....😅 Help here if you can please ..Did't know how to deal with the widths and margins properly

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow 💯

### What I learned

How to capitalize with css
Added quite a bit of grid knowledge

Know this is too much medias , If you know what can help shorten ,your input will be much appreciated, see below:


```css
@media (max-width:635px){
  section{
  margin: 8% 5%;
  }
  .stat-image img{
    width: auto;
  }
}
@media (max-width:583px){
  section{
  margin: 8% 3%;
  }
  .stat-image img{
    width: auto;
  }
}
@media (max-width:567px){
  section{
    margin: 8% 12%;
  }
   .insights{
    width: 300px;
  }
  .stat-image{
    width: 370.4px;
    height: 305.917px;
  }
  .stat-image img{
    width: 370.4px;
    height: auto;
  }
}
@media (max-width:447px){
  section{
    margin: 8% 6%;
  }
}
@media (max-width:419px){
  .stat-image img{
    width: 270.4px;
  }
  .stat-image{
    width: 270.4px;
    height: 223.333px;
  }
  .insights{
    width: 200px;
  }
  section{
    margin: 8% 16%;
  }
}
```

### Continued development

Dealing with Width and Margin of divs ......can't seem to get it right

Flexbox and Grid use

General Margin 🤣

Quickness

## Author

- Website - [Lesley Kimutai](https://leskim.github.io/myweb/)
- Frontend Mentor - [@Leskim](https://www.frontendmentor.io/profile/@Leskim)
