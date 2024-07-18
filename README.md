feat: Add basic tic-tac-toe game logic

- Implement game setup with event listeners on each box to handle player moves
- Add function to check for winning patterns and determine the game winner
- Display winner message when a player wins the game
- Include reset and new game functionality to clear the board and reset the game state

Changes include:
- Handling player turns and marking the boxes with "o" and "x"
- Disabling boxes after they are clicked to prevent multiple clicks
- Checking for winning patterns and displaying a congratulatory message when a player wins
- Adding reset and new game buttons to allow players to restart the game

Functionality:
- `showwinner`: Displays the winner message
- `checkwinner`: Checks for a winner based on predefined winning patterns
- Event listeners on boxes to handle player moves
- Reset and new game functionality to clear the board and reset the game state
