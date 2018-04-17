# Build a Pet
Build your own pet! Use your imagination!

## Objective
Use HTML Forms, JS Functions, DOM, for loops,  and CSS styles to customize your personal pet. 

## Prerequisites
To complete this project, students should have the following:

- Intermediate understanding of HTML structures.
- Intermediate understanding of JavaScript, For Loops, Objects, and DOM (Variables, Functions, getElementById, Events)

## Concepts
HTML | Description
-----| -----------
form | An element that defines a form to collect user input. Contains form elements.
input | An element that obtains information from the user. Can have different types.
input type="text" | Defines a one-line text input field.
input type="radio" | Defines a radio button.
input type="submit" | Defines a submit button.
input type="email" | Input must be email format.
input type="password" | Password will be masked when typing.
select | An element that creates a drop dropdown menu.
options | An element nested within the select element that sets a specific value.
text-area | An element that allows multiple lines of text.

JS | Description
---| -----------
addEventListener "Submit" | An event that occurs when a form is submitted. 
addEventListener "Button" | An event that occurs when a button is clicked. 

## Your Challenge

### Part I File Structure

To complete Part I, fulfill the following requirements:
1. Set up your project file structure through the command line.
2. Create the following:
* HTML file
* CSS file
* JS file
3. Link all of your files correctly.

---

### Part II HTML

To complete Part II, fulfill the following requirements in your **HTML** file with the following parent and child relationships.

![Wireframe](https://i.imgur.com/h5kvicO.png)

##### Required Form Elements
 - Pet Name
 - Type of Animal(Minimum of 4 options)
 - Number of Legs(Minimum of 4 options)
 - Special Abilities(Minimum of 3 options)
 - Pet Email
 - Pet Password
 - Pet Description
 - "Submit" Button
    
### Part III JS

Before you begin, create a function that will run our code as soon as our webpage loads:

```JavaScript
window.onload = function() {


//All code goes in here


}
```

1. Save ID from the `form` element into varialbe `form`
2. Save each input field ID into a varialble 
3. Add Event Listener `submit` to the `form` variable when submit is clicked
4. Add each input value to an empty object declared above
5. Values should all be rendered below

### Stretch Goals
- Make it pretty with CSS
- Add more input fields

### Resources
- HTML Forms - https://www.w3schools.com/html/html_forms.asp
- Event Listener - https://www.w3schools.com/jsref/met_element_addeventlistener.asp
- Object Properties - https://www.w3schools.com/js/js_properties.asp
- For In Loop - https://www.w3schools.com/jsref/jsref_forin.asp
