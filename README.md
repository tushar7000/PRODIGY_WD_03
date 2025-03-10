# PRODIGY_WD_03
# Description 

This is a **Tic-Tac-Toe Web Game** built using **HTML**, **CSS**, and **JavaScript**. The game allows two players to take turns playing Tic-Tac-Toe on a 3x3 grid. The game will show the current player's turn, detect a winner, and allow players to reset the game. It features a clean and user-friendly interface with dynamic updates and simple interactions.

### Features:
- **Player Turns**: Players alternate between "X" and "O" by clicking on the empty cells.
- **Winner Detection**: The game automatically detects if a player wins or if the game results in a draw.
- **Game Reset**: A button is provided to reset the game to its initial state.
- **Interactive Board**: The game board is dynamically created using JavaScript, and each cell reacts to player clicks.
- **Responsive Design**: The game is built to be responsive and works on various screen sizes.

# How to Play:
1. The game starts with Player "X" taking the first turn.
2. Players alternate clicking on empty cells to place their respective marks ("X" or "O").
3. The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins the game.
4. If all cells are filled without a winner, the game results in a draw.
5. Click the "Reset Game" button to restart the game.

# Technologies Used:
- **HTML**: The structure of the game, including the grid and buttons.
- **CSS**: Styling for the game board, cells, and buttons.
- **JavaScript**: Logic for handling the game state, alternating turns, checking for a winner, and resetting the game.

# How it Works:
1. **Dynamic Board**: The board cells are generated dynamically in the `createBoard` function, which is called when the page loads or after the game is reset.
2. **Handling Clicks**: When a cell is clicked, the `handleCellClick` function is triggered. It updates the board with the current player's symbol and checks for a winner or draw.
3. **Winner Check**: The `checkWinner` function evaluates all possible winning combinations and checks if there is a winner.
4. **Reset Functionality**: Clicking the "Reset Game" button resets the game state to its initial conditions, clearing the board and setting Player "X" to start.

# Customizations:
- You can adjust the styling or add animations to enhance the visual experience.
- Extend the game logic to include features such as a computer opponent or advanced difficulty levels.

# Live Demo:
Open the HTML file in any browser to play the Tic-Tac-Toe game.

This game is a simple yet fun implementation of the classic Tic-Tac-Toe game and can be a great addition to a portfolio or a beginner project to practice working with JavaScript event handling and game logic.
