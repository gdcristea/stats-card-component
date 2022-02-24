# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
  - [Author](#author)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Links

- Solution URL: https://github.com/gdcristea/stats-card-component
- Live Site URL: https://gdcristea.github.io/stats-card-component/

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

```css
body {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
}

.image2 {
    display: none; /*want to use it in the media query. Solution here: https://stackoverflow.com/questions/27853884/media-queries-and-image-swapping*/
}

img {
    mix-blend-mode: multiply; /* The mix-blend-mode property specifies how an element's content should blend with its direct parent background. */
    display: block; /* why did I used it? there was an extra space below the image => solution here: https://stackoverflow.com/questions/5804256/image-inside-div-has-extra-space-below-the-image */
} 

```

### Useful resources
- (https://stackoverflow.com/questions/27853884/media-queries-and-image-swapping) - media-queries-and-image-swapping.

- (https://stackoverflow.com/questions/5804256/image-inside-div-has-extra-space-below-the-image) - image-inside-div-has-extra-space-below-the-image.

## Author

- Linkedin - [Daniel Cristea](https://www.linkedin.com/in/daniel-cristea-629069191/)

- Frontend Mentor - [@gdcristea](https://www.frontendmentor.io/profile/gdcristea)

- Twitter - [@gdcristea10](https://twitter.com/gdcristea10)


