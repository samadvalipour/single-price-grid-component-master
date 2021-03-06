# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](https://github.com/samadvalipour/single-price-grid-component-master/blob/master/design/first.JPG)

### Links

- Solution URL: [here](https://www.frontendmentor.io/solutions/html-css-css-grid-YkTy4CqS7)
- Live Site URL: [here](https://samadvalipour.github.io/single-price-grid-component-master/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I learned how to develop a responsive web page:

```css
@media  (min-width:480px) {
    #header {
        grid-column: 1/3;
    }
    .container{
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        grid-template-rows: repeat(2, auto);
    }
    #subscription{
      border-bottom-left-radius: 5px;
    }
    #why_section {
      border-radius: 0px 0px 5px 0px;
    }
}
```


## Author

- Frontend Mentor - [@samadvalipour](https://www.frontendmentor.io/profile/samadvalipour)

- Linked in - @samad valipour
