# Sudoku Solver (Along with Demo Video)

This is a web-based Sudoku solver application. It generates a Sudoku puzzle and provides the solution with an animation effect. 

## Table of Contents
- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)

## Demo
[![Sudoku Solver](sudoku_solver_demo.gif)](https://github.com/gpra012333/Sudoku-Solver/assets/142736928/90cc686a-46d1-47ed-911a-1580a3b72a14)

## Features
- Solve the Sudoku puzzle with an animated effect.
- Responsive design with a clean and intuitive user interface.

## Installation
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/gpra012333/sudoku-solver.git
    ```
2. Open the project directory:
    ```bash
    cd sudoku-solver
    ```
3. Open `index.html` in your preferred web browser.

## Usage
1. Open the `index.html` file in your web browser.
2. Click on the "Get Puzzle" button to generate a new Sudoku puzzle.
3. Click on the "Solve Puzzle" button to see the puzzle being solved with an animation.

## Technologies
- HTML
- CSS
- JavaScript
- XMLHttpRequest (for API requests)

## Code Overview

### HTML
The HTML structure includes a header, a main section containing the Sudoku grid, and buttons for getting and solving the puzzle.

### CSS
The CSS provides styling for the Sudoku grid, header, and buttons. It includes animations for when the Sudoku cells are filled with numbers.

### JavaScript
The JavaScript file includes the logic for fetching the puzzle from an API, filling the board, and solving the puzzle with backtracking algorithm.

## File Structure
index.html
style.css
Script.js
