## Table of contents

- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### Links

- Solution URL:

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- position
- pseudo-elements
- hover effect

### What I learned

In this project, I used some CSS properties to help with responsive font size, such as @media
and pseudo-elements and hover effect

To see how you can add code snippets, see below:

main > h1 {
text-align: center;
background-clip: text;
-webkit-background-clip: text;
color: transparent;
background-image: linear-gradient(90deg, #502050ff, #ee68a4ff);
text-transform: capitalize;
font-weight: 800;
margin: 20px auto 0;
padding-top: 20px;
transform: rotateX(90deg);
transform-origin: top;
transition: all 0.5s;
}
main:hover h1 {
transform: rotateX(0deg);
}
@media (max-width: 768px) {
main {
width: 375px;
height: auto;
margin: 20px auto;
}
main > h1 {
margin-bottom: 30px;
padding-top: 0;
font-size: 35px;
line-height: 1.1;
}
}

### Continued development

I want to learn more about responsive websites and how to use the pseudo-elements and hover effect

### Useful resources

- [w3schools] https://www.w3schools.com/cssref/sel_hover.php
- [w3schools] https://www.w3schools.com/css/css_pseudo_elements.asp

## Author

- Frontend Mentor - [@shadymo2291](https://www.frontendmentor.io/profile/shadymo2291)

## Acknowledgments

I want to thank everyone who helped me to learn and to code, especially the Elzero Web School channel on YouTube
