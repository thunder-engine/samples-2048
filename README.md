# Thunder 2048 - A 2048 Puzzle Game

A sleek and addictive **2048-style puzzle game** built with **Thunde Engine** where players combine numbered tiles on a grid to reach the elusive 2048 tile.

![Screenshot](https://raw.githubusercontent.com/thunder-engine/sample-2048/main/screen.png)

## Features

*   **Smooth Grid Movement:** Slide tiles in four directions using keyboard controls
*   **Tile Merging Mechanics:** Combine identical tiles to create higher numbers
*   **Score System:** Track your progress with live score and best score display
*   **Visual Feedback:** Smooth animations for tile movements and merges
*   **Game State Management:** Win condition detection and game over states

## Getting Started

### Prerequisites

*   Ensure you have the **Thunde Engine** installed and properly set up on your system


## How to Play

1.  **Start:** The game begins with two randomly placed tiles (either 2 or 4)
2.  **Slide Tiles:** Use arrow keys to move all tiles in one direction
3.  **Combine Tiles:** When two tiles with the same number collide, they merge into one tile with their sum
4.  **New Tiles:** After each move, a new tile (2 or 4) appears in a random empty space
5.  **Goal:** Create a tile with the number **2048**
6.  **Game Over:** The game ends when no more moves are possible

## Controls

| Action | Control |
| :--- | :--- |
| Move Up | `Up Arrow` or `W` |
| Move Down | `Down Arrow` or `S` |
| Move Left | `Left Arrow` or `A` |
| Move Right | `Right Arrow` or `D` |


## Game Mechanics

*   **4×4 Grid:** Play on a standard 16-cell game board
*   **Tile Values:** Tiles start at 2 and double when merged (2, 4, 8, 16... 2048)
*   **Simultaneous Merges:** Multiple merges can occur in a single move
*   **Move Validation:** Tiles only move and merge if space is available
*   **Random Spawn:** New tiles appear in random empty positions after valid moves


## Scoring System

*   **Merge Points:** Score equals the value of newly created merged tiles
*   **Example:** Merging two 8-tiles gives 16 points
*   **Strategy Bonus:** Higher-value merges yield exponentially more points

## Tile Progression

```
2 → 4 → 8 → 16 → 32 → 64 → 128 → 256 → 512 → 1024 → 2048
```

## Technology

This project is built as a learning exercise using the **Thunde Engine**, demonstrating 2D grid-based game development, state management, input handling, and algorithmic puzzle logic.

## Strategy Tips

*   **Corner Strategy:** Keep your highest tile in a corner
*   **Build Chains:** Plan multiple merges in sequence
*   **Avoid Clutter:** Try to keep the board as empty as possible
*   **Think Ahead:** Consider where new tiles will spawn


## License

This project is created for educational purposes and is distributed under the [MIT License](LICENSE).
