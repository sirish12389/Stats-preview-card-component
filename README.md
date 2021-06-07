# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size

  - Optimal layout for screens with width 1000px is a vertical layout
  - On the other hand a screeen with width 1000px will have a horizontal layout

### Screenshot
![](design/My-design-moblie.png)


![](design/My-Design-desktop.png)

### Links

- [Solution URL](https://github.com/sirish12389/Stats-preview-card-component)
- [Live Site URL]( https://sirish12389.github.io/Stats-preview-card-component/)

## My process

I divied the entire web page into two major elements
  
  1) The text part of the preview card
  2) The image part of the preview card

This division was performed by placing the image and the text into seprate classes and by use **FlexBox** combine the two elements into two, side-by-side, panel.

Apply backgroud color to both the panels through css and by using the **opacity** fuction to redecue the opacity and giving it a soft violet tint

The text part of the preview card can be divied further into 2 different elements

  1) The main heading and paragraph
  2) The List of stats(though I used the word list, I did not use list tag to dipaly the stats, rather I used a combination of heading and paragraph tag to display it)

Using css change the font family and color the all the text in the text element.

the main paragraph and heading can be created using the head and the paragraph tag in html

For the List, 
  - Create a three divsion using div tag and insert the content into header and paragraph into each division
  - Using flex align all the three division
  - Adjust the size and padding of the heading and the paragraph



### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned
These are some of the things I learned while trying to solve this problem

- I learned the basic syntax of css and important tag that are commonly used to design a web page

- I learned the importance of the div tag. The div tag is very important while dealing with multiple panel and with help of the class attribute, you can make easy and meaningful design  

```html
  <div>
      <image src="#" name="NULL">
  </div>
```
 - I learned importance of modular programming. At the start randomly tried to place all the objects and design it from there, but I was not able to do it. When I removed all the components and started developing each element one by one and placing each of the elements into proper container, I was finally able to solve the problem

### Continued development
I have to no plans to developing this any futher

### Useful resources

- [CSS Tutorial](https://www.youtube.com/watch?v=yfoY53QXEnI&t=243s) - To understand the basic syntax of css and a List of very useful properties
- [FlexBox Tutorial](https://www.youtube.com/watch?v=JJSoEo8JSnc) - To understand how to implement FlexBox
- [CSS Styling Images](https://www.w3schools.com/css/css3_images.asp) - To understand how to edit the image to your preference


## Author

- Frontend Mentor - [@sirish12389] https://www.frontendmentor.io/profile/sirish12389


## Acknowledgments
Thank you [Traversy Media](https://www.youtube.com/user/TechGuyWeb) for helping me learn css and FlexBox through very useful videos on how to implement diffenent concept of css and flexbox, and also providing a cheatsheet of all the usefull commands in css and flexbox
