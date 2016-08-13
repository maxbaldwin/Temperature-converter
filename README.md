Instructions

Write a program that will convert a temperature from fahrenheit to celsius, or from celsius to fahrenheit.

In the HTML, have one input field where someone can enter in a temperature.
Create a radio button group where Celsius or Fahrenheit can be selected as the scale that the number should be converted to.
Create a block level element that will hold the text of the converted temperature.
Create a button that, when clicked, displays the converted temperature.
Create another button that, when clicked, clears any text in the input field.
Add an event handler to the input field that checks if the user pressed the enter key, and if that happens, perform the conversion.
If the temperature is greater than 90F/32C the color of the converted temperature should be red.
If the temperature is less than 32F/0C the color of the converted temperature should be blue.
For any other temperature, the color should be green.
function toCelsius () {

}

function toFahrenheit () {

}

// Get a reference to the button element in the DOM
var button = document.getElementById("converter");

// This function should determine which conversion should
// happen based on which radio button is selected.
function determineConverter (clickEvent) {
  console.log("event", clickEvent);
}

// Assign a function to be executed when the button is clicked
button.addEventListener("click", determineConverter);

//Notes from August 1st (1st Class Back)
Converter Exercise

1. Create Files
    1. index.html - DONE
    2. converter.js - DONE
    3. style.css - DONE
    4. readme.md - DONE
2. Github repo/link files - DONE
3. basic html - DONE
4. even listeners —> button click
    1. Do this after HTML is done
5. get value from input
6. which radio button is selected?
7. MATH!
8. Answer to DOM
9. Colors (problems 7 -9)

Problem: convert temp C -> F, F -> C

Steps
1. Type in Temp
2. Click on unit system
3. click on submit
4. calculate conversion
5. write answer to DOM

What to Research?
1. Click Events
    1. Make the event listener work first, console log it. 
2. How to get value out of input
3. Conversion formula