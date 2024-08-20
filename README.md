# Tic-Tac-Toe Game

This is a simple implementation of the classic Tic-Tac-Toe game using HTML, CSS, and JavaScript. The game is played between two players, X and O, who take turns marking spaces in a 3x3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.

## Features

- Player vs. Player mode.
- Game reset functionality to start a new game.
- Visual indication of the winner or if the game ends in a draw.

## How to Play

1. Open the `index.html` file in your browser.
2. The first player, O, starts the game.
3. Click on any empty box in the grid to place your mark (O or X).
4. Players alternate turns until one player wins by forming a straight line (horizontal, vertical, or diagonal) or the game ends in a draw.
5. After the game ends, click the "New Game" button to start a new round.

## Files

- `index.html`: The main HTML file containing the structure of the game.
- `style.css`: The CSS file for styling the game layout and elements.
- `app.js`: The JavaScript file containing the game logic.

## Game Logic

- The game keeps track of each player's turn and updates the grid accordingly.
- Winning patterns are predefined, and the game checks for a winner after each turn.
- If all boxes are filled and no player has won, the game ends in a draw.

## Resetting the Game

- The "Reset Game" button allows players to reset the game at any time.
- The "New Game" button appears after the game ends, allowing players to start a fresh game.

## How to Run

To play the game, simply open the `index.html` file in your preferred web browser. No additional setup is required.

## Technologies Used

- **HTML**: For the structure of the game.
- **CSS**: For styling the game elements and layout.
- **JavaScript**: For implementing the game logic and interactivity.

## License

This project is open-source and available under the MIT License.
