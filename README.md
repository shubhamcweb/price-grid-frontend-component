# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size (only desktop design implemented as of now)
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshot.png)

### Links

- Live Site URL: [Site deployed on GitHub Page](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Google Fonts

### What I learned

This was my 2nd Frontend Mentor challenge that I completed and it helped me really understand the HTML/CSS frontend workflow. I learned how to use structured and semantic HTML elements and further increased my understanding of CSS layouts and styling.

As of writing this README, I've not yet gotten into learning Grids and Flexbox in CSS, so laying out two divs side by side was quite interesting using CSS's "inline-block" display property. I also learnt that this property doesn't work if the elements are not in-line in the HTML document itself, that is to say that they have some whitespacing or new-line character in between.

I got around that quirk in two ways:
1. By simply putting shorter div elements physically in-line
```html
<div id="price">$29</div><div id="price-frequency">per month</div>
```
2. By putting a multiline comment in the whitespacing between larger divs to maintain readability
```html
    <div>
      .....
    </div><!-- There cannot be any whitespace or new line character between inline-block elements
  --><div id="bottom-right">
      .....
    </div>
```
 
I also learnt that sometimes in-line block elements need their "vertical-align" property to be set otherwise they start behaving in an undesirable manner.
```css
#bottom-left, #bottom-right {
  display: inline-block;
  vertical-align: top;
}
```

Overall, this challenge really helped me learn different concepts and usage of semantic HTML and CSS styling and I see myself ahead from where I was before. I hope to do many more challenges next, and keep learning and growing further!

### Continued development

After completing this project I feel I have a basic understanding of HTML and CSS and now my next goal will be to learn CSS Flexbox and Grid layouts and other CSS frameworks.

Also, I will now be learning how to implement responsive mobile-friendly websites, since that is something I'm currently lacking and then hopefully move on to other challenges that will give me the opportunity to apply my knowledge in a more hands-on manner.

### Useful resources

- [HTML Color Converter](https://htmlcolors.com/color-converter) - A really useful tool to convert different color values from (and to) different formats like RGB, HEX, HSL, etc.
- [Box Shadow CSS Generator](https://www.example.com) - An amazing tool that lets you visually experiment with different box-shadow parameters and outputs the CSS to implement that.

## Author

- LinkedIn - [Shubham Chandravanshi](https://www.linkedin.com/in/shubhamcweb)

## Acknowledgments

I would like to give speacial thanks to @zachgoll (Zach Gollwitzer), for his incredible free crashcourse video "Frontend Web Development Bootcamp Course (JavaScript, HTML, CSS)" on freeCodeCamp.org channel on YouTube, who led me to this challenge. A fantastic teacher in every way!

Here are some links if you want to see his work:
- Website - [zachgollwitzer.com](https://zachgollwitzer.com)
- Twitter - [@zg_dev](https://twitter.com/zg_dev)
- YouTube - [@zachgoll](https://www.youtube.com/@zachgoll/about)
- That above mentioned video - [Frontend Bootcamp](https://www.youtube.com/watch?v=zJSY8tbf_ys&t=58873s)