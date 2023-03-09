# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

This was a great challenge to jump in and get the basics of HTML and CSS.

### Screenshot

![](./qr-code-component-main\Screenshot 2023-03-08 225655.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

It has been a while since I worked with HTML and CSS and it was fun to relearn the properties of classes and divs for CSS. I also learned that the paragraph HTML tag does not abide by block properties which required me to make a class to encompass all of my elements instead of just packaging them in <p></p>.

```html
<div class="total">
    <img src="qr-code-component-main\images\image-qr-code.png" alt="QR Code">
    <div class="primary">
      Improve your front-end skills by building projects
    </div>
    <div class="secondary">
      Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
    </div>
    
  </div>
```
```css
.total {
    padding: 15px;
    padding-bottom: 20px;
    border-radius: 5%;
    display: block;
    margin-top: 150px;
    margin-left: auto;
    margin-right: auto;
    align-self: center;
    width: 300px;
    background-color: white;
    font-family: 'Outfit', sans-serif;
}
.primary {
    padding: 15px;
    display: block;
    text-align: center;
    color: hsl(218, 44%, 22%);
    font-weight: 700;
    font-size: 22px;
}
.secondary {
    margin-right: 15px;
    margin-left: 15px;
    padding-bottom: 15px;
    display: block;
    text-align: center;
    color: hsl(220, 15%, 55%);
    font-size: 15px;
}
```

### Useful resources

- [W3 Schools](https://www.w3schools.com/css/default.asp) - This really worked as a good reference/tutorial for CSS.
- [Stack Overflow](https://stackoverflow.com/) - This helped with any weird syntax issues or odd things I did not know about HTML.

## Author

- LinkedIn - [Javin Page](https://www.linkedin.com/in/javin-page/)
- Frontend Mentor - [@pageja25](https://www.frontendmentor.io/profile/pageja25)
- Twitter - [@elmagoamateur](https://twitter.com/elmagoamateur)
