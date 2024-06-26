# Tic-Tac-Toe AI

A simple Tic-Tac-Toe game with an AI opponent implemented using HTML, CSS, and JavaScript.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [How to Play](#how-to-play)
- [AI Algorithm](#ai-algorithm)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is a web-based implementation of Tic-Tac-Toe where users can play against an AI opponent. The game is designed using modern web technologies and demonstrates basic AI decision-making using the minimax algorithm.

## Features

- Responsive UI with CSS grid layout for game board
- AI opponent using minimax algorithm for optimal moves
- Game state management to handle win, draw, and player turns
- Reset button to restart the game at any point

## Getting Started

To run the game locally, clone this repository:

```bash
git clone https://github.com/shahram8708/tic-tac-toe-ai.git
```

Open `index.html` in your web browser.

## How to Play

- Click on any cell in the grid to make your move.
- The AI opponent will automatically play its move after yours.
- The game announces the winner or declares a draw when appropriate.
- Use the reset button to start a new game.

## AI Algorithm

The AI opponent uses the minimax algorithm to determine the best move:

```javascript
function minimax(board, depth, isMaximizing) {
    // Minimax algorithm implementation
}
```

## Contributing

Contributions are welcome! Feel free to open issues and pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
