# Interactive Tile Matching Game

This is an interactive tile-matching game built using Python's **Turtle Graphics** module. In this game, players click on tiles to reveal hidden numbers and attempt to match pairs of numbers. The game leverages randomization, event handling, and real-time updates to create a fun and engaging memory-based puzzle.

## Features

- **64 Tile Grid**: A grid of 64 tiles is displayed on a yellow background.
- **Hidden Numbers**: Each tile hides a number from 0 to 31. The numbers are shuffled and randomly assigned to the tiles.
- **Click to Reveal**: Players can click on tiles to reveal the numbers hidden beneath.
- **Match Pairs**: If two clicked tiles have matching numbers, they remain visible. If not, they are hidden again.
- **Real-Time Feedback**: The game updates the display every 10 milliseconds to ensure smooth and interactive gameplay.

## Gameplay

1. Click on any tile to reveal the hidden number.
2. Click on a second tile to reveal its number.
3. If the numbers match, both tiles remain visible. Otherwise, they are hidden again.
4. The goal is to match all pairs of tiles with the same number.

## Project Structure

- **Square()**: This function defines the appearance of each tile on the grid.
- **Numbering()**: Converts the clicked coordinates to the tile’s index.
- **Coordinates()**: Maps the tile's index to its location on the screen.
- **click()**: Handles mouse click events and manages the game logic for revealing/hiding tiles.
- **draw()**: Responsible for rendering the grid, updating the screen, and displaying tile numbers.

## Technologies Used

- **Python**: The core programming language for the project.
- **Turtle Graphics**: Used for rendering the grid and handling user interaction.
- **Random Module**: To shuffle and assign numbers randomly to the tiles.
- **Event Handling**: Captures user clicks and controls game flow using Turtle’s `onscreenclick()` function.



