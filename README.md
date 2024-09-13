# AI Tetris
AI implemented over a simple Tetris game built with Pygame.

## How to Play
AI Tetris can be downloaded and played in a few simple steps.

#### 1. Clone the Repository
```sh
git clone https://github.com/gumdropsteve/ai-tetris
cd ai-tetris
```

#### 2. Install Pygame
```sh
pip install pygame
```

#### 3. Run the Game
```sh
python tetris.py
```

## How it Works
AI Heuristics: The AI evaluates each possible move for the current piece based on the following factors:
- Aggregate height of columns.
- Cleared lines.
- Number of holes (empty spaces beneath blocks).
- Bumpiness (difference in height between adjacent columns).

AI Decision: The AI chooses the move with the highest score based on these factors and automatically moves and rotates the piece.
