# Score Keeper
A scorekeeper project from Colt Steele's Web Development Course on uDemy

A project where you can keep score for a any game that you play with another player. 

It utilises a mix of HTML, CSS, and Javascript. In addition, styling was completed using Bulma.



Part 1:Cancel changes

Main components worked on: 

- coded for Player 1 and Player 2
- coded for the score display

Created the basic setup for the HTML and JavaScript files. Then, added a basic heading, buttons for Player 1, Player 2 and a reset button,  with corresponding id names to the elements. Created functions for both the Player One and Player Two buttons, where once clicked, the counter will show a number.  

Quick Note: The use of <span> for the counters to update is very useful when you need the counter to activate. 





Part 2: 

Main components worked on:
 
 - Coded for the reset button
 - Used CSS to style the number counter for the winner and loser

In the HTML file, in order for players to be able to select a number of rounds that they would like to play up to, a <select> element was used with the following <option> elements, indicating amount of rounds. 

Then, created a function for reseting the display, so when the reset button is clicked on, the display returns to 0. Once this is done, I needed the rounds dropdown menu to function so that when players reach the desired amount of rounds, then the game stops. 

Next, added an extra function for when the winner reaaches the end of the round, a green colour is applied, vice versa with the loser, and when the reset button is clicked, the colors go back to black. classList.remove/add was used to achieve this. 

Quick Note: The dropdown round numbers will be passed as a string rather than a number. This is where parseInt() is used to convert the rounds to a number. 




Part 3:

Main components worked on:

- First time using Bulma
- Styled elements and positioned everything using Bulma

Used the templates from Bulma to set up the positioning, card design and button designs. Added my own picture for a basketball score keeper.  

Quick Note: Use section class to center every element on the webpage






Part 4:

Main components worked on:

- Refactoring code, making it more compact

Made p1 and p2 as objects which contains the selectors and the score global variable. Created an updateScore function to streamline the code. Instead of having separate functions for p1 and p2, it's now refactored to player and opponent.  Reset button was also made into a for loop, will make adding extra players easier. 

Quick Note: Can use for loop for the reset function. Makes it easier to allow additional players. Extra extra note: I have looked and compared my code to the sample one and it's exactly the same, however my code was not running properly which was strage. 
