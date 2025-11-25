# html-and-css

## Proj 1 Basic HTML and CSS 
- **div**---> The div tag in HTML, short for "division," is a generic container element used to group and structure content on a webpage. It is a block-level element, meaning it typically starts on a new line and takes up the full available width by default.
- Exercise 1 --> apply css on all the div tag, such set background color, height and width..etc ```exercise1.html```
- Exercise 2 --> apply different css on both div. This we can do with the help of css class.
- Exercise 3 --> Nesting div tag
- Exercise 4 --> Define css in seprate file.

## Proj 2 Restaurant website
- First install html hint extension that will suggest if there is any html/syntax error.
- Create new file ```index.html``` and ```style.css```
- Set background color of entire page ```body{background-color: lightblue;}```
- Add image, alt attribute in image tag used to display text if there is any issue loading image. Used ``` text-align: center;``` css  in header to move logo in center.
- Add CSS refer style1.css.
- Add stretching background image to a website(to add use  background-image: url(/images/background-adare-restaurant.jpg); in css (body)). Now if resize window u will observe image is not aligned properly to fix it use ```background-size: cover;``` in same css. apply other css such as background-repeat, background-position ...etc
- How to make div tag transparent using html and css ---> example lets say i want to make transparent tag <nav>, we can do it using ``` background-color: rgb(0, 0, 0,0.338);``` css for nav tag.
- Adding navigation link ---> Add navigation tag and css for it, aslo mention css property ```text-align: center``` for nag tag.
- How to apply css to more than one class tag at a time/ compound css classes ---> add following css
  ```
   nav a {
    text-decoration: none; /* added to remove underline from <a> tag content */
    font-size: 12px;
    padding-left: 10px;
    padding-right: 10px;
   }
  ```
- **Designing footer**
   - make footer background transparent but make sure its darker than nav.
- add email button ---> when anyone will click on this new email box will appear with prefiled subject and to, or many be we can also include cc
- embed map --> Go to google map, selecct location, click on share--> embed-->Custom size give the size and copy html
  

## Proj 3 Vehicle Repair 

- Create index.html, style.css and reset-css.css file.
- add required div, if u see without ```display: flex;``` css in .cards class, all three cards will be displayed vertically. after using display: flex property it will start apearing inline.
- Add even space between div tags using flex box without any other margins ---> use css ```justify-content: space-between;``` in .cards class
- Having two div tag of different size in same row--->
   - we could use withd:200px kind of property but its not recomended
   - Or we could use percentage width:30%
   - Or we could use flex: 2 and flex: 1 kind of css attributes. But flex can we used if and only if immediate parent have this in css ex in main we have dispaly: flex
- How to vertically center content in an html div tag using flexbox css -->  use ```align-items: center;``` css in main
- Design Header
  - add following CSS
    ```
     header {
     min-height: 100px;
     display: flex;
     justify-content: space-between;
     align-items: center;
     padding-top: 20px;
     padding-bottom: 20px;
     }
    ``` 
