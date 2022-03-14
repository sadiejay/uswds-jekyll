# Timeline Overview Jekyll Page


This is a solution to the [COIL take home challenge](#). 

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
Create a new page and implement the design, using best practices to make the content simple to update and modular (e.g., we should be able to use the info about participants elsewhere in the site). 
### Screenshot
### Mobile view

### Tablet view


### Desktop view





### Links

To build run:
`bundle exec jekyll serve`

For live reload add the flag:
` --livereload`


- Repo URL: [https://github.com/sadiejay/uswds-jekyll](https://github.com/sadiejay/uswds-jekyll)
- Live Site URL: [https://sadiejay.github.io/uswds-jekyll/](https://sadiejay.github.io/uswds-jekyll/)

## My process
- Build out HTML / CSS from figma file
- Transfer txt file to yml for _data
    - not sure if I need to add `week-topic-date:` to every entry but I did just in case
- Build out _layout with HTML
    - The hero area isn't translating to the template from the design. The background doesn't take the width of the screen.
- Created timeline.md with partials made in _layout
    - changed the meta partial to add fonts
- Styled layout using the _uswds-theme-setting

### Built with

- Jekyll
- Ruby
- Liquid
- asdf
- homebrew


### What I learned
 - Jekyll
 - Liquid tags

  #### code snippets
```html
{% assign week-topic-date = topic.week-topic-date %}
                {% if week-topic-date %}
                <h6 class="week-topic-date">{{week-topic-date}}</h6>
                {% endif %}
```

### Continued development

- I would add the tab slider
    - something like this but more tailored to the design: https://codepen.io/w3codemasters/pen/vQdzPj?editors=1010

- I would like to figure out whether the hero area is styled front matter or if I need to redo the HTML/CSS.

- Would also like to change the menu button to red and add the correct logo to the bottom

- Adjust the loop so that the boarder goes around the entire card

### Useful resources
- [https://github.com/sadiejay/uswds-jekyll/blob/main/_includes/meta.html](https://github.com/sadiejay/uswds-jekyll/blob/main/_includes/meta.html) - Wrapping `if` syntax 
- [Using GitHub Pages & Jekyll to Create a Portfolio Site](https://bit.ly/github-pages-and-jekyll) - Resources for every step of the build process
- [Collections](https://jekyllrb.com/docs/collections/) - This helped with syntax in the yml and the _includes partials

## Author

- Github - [@sadiejay](https://github.com/sadiejay)


## Acknowledgments
 - Thank you Alessandra and Victoria for this opporunity!
 - Thank you Meg for your guidance and direction!