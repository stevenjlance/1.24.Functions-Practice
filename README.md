# Most Populated Cities Quiz

We have some pretty big and bustling cities here in the US. At over 8.5 million people, New York City is the most populated city in America. But that's not even half the population of the 10th most populated city in the world! Use your knowledge of HTML and Javascript to create a quiz that will test user's knowledge of the 10 most populated cities in the world and their population size. How many do you think you can guess?

## The Goal

![](assets/Exemplar.gif)

Use HTML and JavaScript to accept input from users, and dynamically add content to the page if the user enters a correct city. The final product can be found here: <a href="https://most-populated-cities-fin.glitch.me">https://most-populated-cities-fin.glitch.me</a>. For a cheatsheet, check out `mostPopulatedCities.txt`.

## The Lab
1. Using `document.querySelector()` select for the input field. Store this information in a variable.
2. Place an event listener on the input field. Log to the console a message every time a user updates the input field (we call this "change").
3. Store the `#textBox` portion of the DOM in a variable using `document.querySelector()`.
4. Update the `#textBox` using conditionals and innerHTML. Start by getting the textBox to log something like "You picked Beijing!" if the user picks the correct city.
5. There are seven more cities to go. Code out your conditional so that each city appears when their name is input into the input field.
6. Declare a function called `checkCorrect()` and place ALL of this inside the function. Then call this function (and only this function) inside the event listener.
7. Print a message to the div with an id of `#message` when the user has guessed all the correct cities.