# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### Screenshot

![Desktop](./images/screenshot-1.png.jpg)
![Mobile](./images/screenshot-2.png.jpg)

### Links

- Solution URL: [Add solution URL here](https://github.com/samirhembrom/qr)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I am practicing ordering css styles. First position, second box model, after that typography, then comes visual, and at last misc.

Second using height and width in img tag, this helps browser to calculate aspect ratio prior to the image being loaded.

```html
      <img
        class="qr"
        width="288"
        height="288"
        src="./images/image-qr-code.png"
        alt="qr code for frontend mentor"
      />
```
```css
.card {
    width: 320px;
    padding: 1rem;
    padding-bottom: 2.5rem;

    text-align: center;

    background-color: white;
    border-radius: 20px;
    box-shadow:
        2px 2px 18px rgb(0 0 0 / 5%),
        -2px 2px 18px rgb(0 0 0 / 5%);
}
```


### Continued development

Going to follow on more best practices in web development and including it in my development process.

### Useful resources

- [Learn HTML](https://web.dev/learn/html) - Whenever I am confused about some stuff, I'd probably go here and check it out. 
- [Learn CSS](https://web.dev/learn/css) - Currently I am still reading through this. It has some magical tricks to use in future challenges. 

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Frontend Mentor - [@samirhembrom](https://www.frontendmentor.io/profile/samirhembrom)
