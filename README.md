
# PureChess

**PureChess**, a chess engine written in Haskell. Project done for my Artificial Intelligence course (BEE411L).

## Introduction

**PureChess** is an educational project designed to showcase a chess engine implemented entirely in Haskell. This project is intended for the BEE4111L AI course and focuses on leveraging Haskell's strengths in functional programming to build a chess engine that demonstrates fundamental AI principles, such as search algorithms and evaluation functions.

## Features

- **Legal Move Generation**: Generates all possible legal moves for any given position.
- **Board Representation**: Efficient representation of the chessboard and pieces.
- **Minimax Algorithm**: Implements the Minimax algorithm for decision-making.
- **Alpha-Beta Pruning**: Optimizes the Minimax algorithm with Alpha-Beta pruning.
- **Heuristic Evaluation**: Basic heuristic evaluation function to assess board positions.
- **User Interface**: Command-line interface to interact with the engine and play games.

## Installation

To build and run PureChess, you need to have the ghc and cabal
` installed on your machine. You can follow these steps:

1. **Clone the repository:**

   ```sh
   git clone https://github.com/highsanburger/purechess.git
   cd purechess
   ```

2. **Install dependencies:**

   PureChess uses the `cabal` build tool. Install the required dependencies with:

   ```sh
   cabal update
   cabal install --only-dependencies
   ```

3. **Build the project:**

   ```sh
   cabal build
   ```

4. **Run the engine:**

   After building, you can run PureChess with:

   ```sh
   cabal run purechess
   ```

## Architecture

PureChess is organized into several key modules:

- **`Board`**: Handles the representation of the chessboard and pieces.
- **`MoveGeneration`**: Contains functions for generating legal moves.
- **`Search`**: Implements the Minimax algorithm and Alpha-Beta pruning.
- **`Evaluation`**: Contains the heuristic evaluation functions.
- **`UI`**: Provides the command-line interface for user interaction.
