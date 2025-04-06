# Frontend Mentor - Social Links Profile solution

This is a solution to the [Social links Profile on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)


## Overview

### Screenshot

![Final Result](https://github.com/vanbyu22/Social-links-profile-FM/blob/63a88cbcd85cef130df3c76af3ee885cc108287b/Screenshot_29-3-2025_141916_final-desktop.jpeg)

### Links

- Challenge URL on Frontend Mentor: (https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ)

## My process

Just like the previous Newbie challenges on Frontend Mentor, the majority of the designs consisted of a "Main" container with divs within it.

At first, I made the links into colored divs that changed color when hovered. However, the only way to click the links are to actually click on the texts, but I wanted the whole div to be clickable. So, the most obvious way to fix that is to actually turn the divs into buttons. So I used the < button > element with the onclick attribute (explained more below) to make the buttons click to open the links.

I've also finally used media queries to make the screen responsive for mobile. I believe I've got it as close to the mobile design as possible. It's still a work in progress.

### Built with

- Semantic HTML5 & CSS on VS Code (with Prettier extension)

### What I learned

When I used to the button element to link the websites, it would open the links in the same window. I wanted to them to open in a new tab/window but target="\_blank" does not work with the button element. At first I found a small javascript code that would open the link to a new window but since I'm not learning javascript yet, I wanted to stick to HMTL/CSS for now. After searching around I found this snippet:

```html
<button onclick="window.open('https://www.example.com', '_blank')">
  Open in New Window
</button>
```

And it worked!

### Continued development

Continue to practice as always. I will also attempt to make my own social links profile using this design.
