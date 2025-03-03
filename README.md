# Slot Machine JS

This is a simple slot machine game built with Node.js. The game allows the player to deposit an amount, choose how many lines to bet on, and place a bet per line. After spinning the reels, the player can win based on matching symbols across the selected lines.

## Features

- **Deposit**: Start the game by depositing an amount.
- **Betting**: Choose the number of lines to bet on (1 to 3) and the amount to bet per line.
- **Reels Spin**: The reels will randomly generate symbols and display them.
- **Winning Calculation**: Winnings are based on matching symbols across the selected lines. Each symbol has a predefined value.
- **Play Again**: After each round, the player can choose to play again or exit the game.

## Symbols and Values

The slot machine uses 4 different symbols with the following properties:

- Symbol `A`: Appears 2 times and is worth 5 per match.
- Symbol `B`: Appears 4 times and is worth 4 per match.
- Symbol `C`: Appears 6 times and is worth 3 per match.
- Symbol `D`: Appears 8 times and is worth 2 per match.

## Installation

To run this game, you need Node.js installed on your computer. If you haven't already, you can download and install it from [Node.js official website](https://nodejs.org/).

### Steps to run the game:

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/your-username/slot-machine-game.git

2. Navigate to the project directory.
   ```bash
   cd slot-machine-game

3. Install dependencies
   ```bash
   npm install prompt-sync

4. Run It
   ```bash
   node index.js


