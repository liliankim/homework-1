Homework 1

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [User Story](#user-story)
  - [Acceptance Criteria](#acceptance-criteria)
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
Accessibility in HTML and CSS
### The challenge
Refactoring a set of completed CSS and HTML codes without breaking the code.

### User Story

We are given a code that has been completed. We want to ensure that the code is accessible and also enables anyone who reads the code to be able to efficiently search and understand the code.

### Acceptance Criteria

1. Alt tags are included in images
2. Codes are not repeated and unrequired codes are not present
3. Proper semantics are included

### Screenshot

(/assets/images/screenshot.png)



### Links

- Solution URL: https://liliankim.github.io/homework-1/
- Live Site URL: https://github.com/liliankim/homework-1.git

## My process
I first went line by line on the HTML to go through all the div tags to make sure all semantics were more detailed. Afterwards, I went to the CSS page to clean up any code that was not necessary. I made sure to toggle back and forth in the browser to make sure teh code did not break after my changes.
### Built with

- HTML
- CSS



### What I learned

What I learned in this lesson was the importance of semantics and keeping a clean code. Upon first look at the code, it was quite overwhelming but as I broke it down one by one it started to make sense. I learned that it is significant that the code is accessible to anyone at any time.

For example:

.content h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

The above code was listed three times when it could have been condensed into one class (content h2).
This is only for one code but I imagined this code being repeated multiple times. Without using class selectors, it uses up unecessary space and time as well.



### Continued development
A few things I would like to practice more is identify more semantic elements. I think doing so would be helpful in being more detailed in my coding. I would also like to practice inheritance in the CSS coding. I believe doing so will help me produce a cleaner code.

### Useful resources

https://www.w3schools.com/
W3 schools helped a lot. It's a very detailed and organized resource for any coding question.



## Author

Lilian Kim


## Acknowledgments

Phil Loy(Tutor)- Phil was able to explain and go over any concepts that I did not understand.
Scott Nelson (TA)- Scott helped me breakdown all the walls I ran into when I could not figure out how to tackle certain aspects of the homework.
