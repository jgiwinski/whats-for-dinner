
### Iteration 0: Build Out Comp [COMPLETED] 
- Images are below
- An assets directory is provided in the repo, and colors are provided in the CSS file.

### Iteration 1: Add Random Side, Main and Dessert Functionality COMPLETED

- When a user selects a dish option (don't worry about "Entire Meal" yet) and then clicks the "Let's Cook!" button, the user sees a random dish from the list of possible dishes for that category
- When the dish name appears, the cookpot icon disappears

### Iteration 2: Entire Meal Funcitonality COMPLETED

- When the user selects the "Entire Meal" option and then clicks the "Let's Cook!" button, the user sees a message with a side, main and dessert option from the lists of possible dishes for all categories
- When the meal items appear, the cookpot icon disappears

### Iteration 3: Error Handling and Clear Button COMPLETED

- The user can click a clear button, which clears the page of any message. User should only be able to click the clear button if a food is visible. When the clear button is clicked and the food is removed, the image of the cookpot should re-appear.
- User should not be able to click the "Let's Cook" button for a recipe unless they have selected an option.

_Note: You can disable these buttons, hide them, or display a message to the user for error handling. The choice is yours!_

### Iteration 4: Adding a Recipe COMPLETED (kinda)

- The user can click an "Add a Recipe" button, which will display a form to add a new recipe at the bottom of the page
- The user can add a type and a name, click the "Add New" recipe and that recipe will be added to the appropriate list
- When a new recipe is added, that recipe should automatically display instead of the cookpot icon

_NOTE: None of this needs to persist on page refresh_








### Iteration 5: BONUS ROUND (Ideas for Extensions)

_NOTE: This round is not required, and you should absolutely not be working on this unless your UI is solid and you are 100% sure that all of Iterations 1-4 are fully functional and bug free._

- Add a loading animation when a user clicks the "Let's Cook" button to simulate searching for a recipe. Hint - You will need to use CSS Keyframes, and a Javascript timeout function for this.
- When a user tries to add to a recipe type that does not exist, we see an error message, OR the new category gets added!
- Add the ability to delete a recipe (ie: when a recipe shows up, show a button that says "I don't like this recipe" (or something similar), and remove it from the array so that it will not show up any more (does not need to persist on page load). Make sure to alert the user in some way that the recipe has been removed. 
- Make sure that the same recipe (single item or entire meal) won't be generated more than once. Make sure to add error handling for when a user "runs out of recipes." (does not need to persist on page load)
- Additional functionality for entire meal -> add the ability to swap out meal items. Note: Make sure your design for this matches the theme
- CYOA Extension! Make sure you run your idea by instructors
<hr/>
