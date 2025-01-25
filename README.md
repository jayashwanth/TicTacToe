# Tic-Tac-Toe Game

A simple and interactive Tic-Tac-Toe game built with HTML, CSS, and JavaScript.

## Features
- Two-player gameplay with "X" and "O".
- Detects a winner or a draw.
- Reset and New Game functionality.
- Minimal and responsive design.
- 
## How to Play
1. Open the game in a browser.
2. Players take turns clicking on the boxes to place "X" or "O".
3. The game announces the winner or a draw once all boxes are filled or a winning condition is met.
4. Use the "Reset Game" button to clear the board or "New Game" to start fresh.


## How It Works
1. **Game Board**: A 3x3 grid is displayed using buttons styled as tiles.
2. **Winning Logic**: Checks for winning patterns or a draw after each turn.
3. **Reset Functionality**: Resets the board for continued gameplay.
4. **Message Container**: Displays the winner or a draw message.

## Files Overview
### `index.html`
Defines the structure of the game, including:
- 3x3 game grid.
- Buttons for reset and new game actions.

### `style.css`
Handles the styling for the game, including:
- Responsive design for the game board.
- Styles for buttons and winner/draw messages.

### `app.js`
Contains the game logic:
- Tracks player turns.
- Checks for winning patterns and draws.
- Provides reset and new game functionalities.

## How to Run
1. Download the files.
2. Open `index.html` in a browser.
3. Enjoy the game!

## Winning Patterns
The game checks for these patterns:
- Horizontal: [0, 1, 2], [3, 4, 5], [6, 7, 8]
- Vertical: [0, 3, 6], [1, 4, 7], [2, 5, 8]
- Diagonal: [0, 4, 8], [2, 4, 6]

## License
This project is open source and available under the MIT License.
