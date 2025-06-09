# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

![](./assets/images/Screenshot%20recipe-page-main.png)
![](./assets/images/Screenshot%20recipe-page-main%20(2).png)

### Links

- Solution URL: [https://github.com/j4n1na/recipe-page-main.git]
- Live Site URL: [(https://j4n1na.github.io/recipe-page-main/)]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

Spacing: padding vs. margin
I learned how to use padding and margin to control spacing more precisely.

padding adds space inside an element — between its content and the border.

margin adds space outside an element — between the element and its neighbors.

For example, I used padding: 0.05rem 1.5rem; inside the #prep-time box, and margin-top: 2rem; to push it down from the content above. 


Table Structure & Layout Control
I also learned how to style and structure tables effectively.
By using border-collapse: collapse;, I removed the extra space between adjacent table cell borders — making the table look much cleaner.

I adjusted the spacing in th and td using padding-right to push the text without breaking the layout, and text-align: left to keep everything aligned nicely.

I even removed the bottom border from the last row using tr:last-child { border: 0; }, so the table doesn’t have a double bottom line.


```css
th, td {
  padding: 1rem 0; /* 1rem vertical space creates space between text and border */
}


th {
  text-align: left;
  padding-left: 1.8rem; /* or whatever value creates a balanced gap */
  font-weight: 400;
  padding-right: 245px;
}

td {
  font-weight: 700;
  text-align: left;
  padding-right: 260px;
}


table {
  border-collapse: collapse;    /* Removes space between adjacent cell borders by merging them into a single border */
}

tr {
  border-bottom: 1px solid hsl(30, 18%, 87%);
  
   
}

table tr:last-child {
  border: 0;
}
```


### Continued development

One area I’d like to continue improving is layout and positioning. While I’ve made good progress using tools like flexbox, padding, and margin, I sometimes still struggle with getting elements to align exactly how I want — especially when combining different layout techniques or dealing with nested elements.
Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources
- [Resource 1](https://www.youtube.com/watch?v=dK27jWKtJxs) - Table In HTML and CSS
- [Resource 2](https://www.geekster.in/articles/table-headers-html/#:~:text=In%20HTML%2C%20table%20headers%20are,bold%20and%20centered%20by%20default.) - Vertical Table Headers
- [Resource 3](https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing) - box-sizing


## Author

- Frontend Mentor - [@j4n1na](https://www.frontendmentor.io/profile/j4n1na)





