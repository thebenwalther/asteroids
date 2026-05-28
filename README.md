# Asteroids

A classic Asteroids arcade game built with Python and pygame. Shoot asteroids before they hit you — large asteroids split into smaller, faster ones when destroyed.

## Gameplay

- Fly your ship around the screen and shoot incoming asteroids
- Large asteroids split into two smaller, faster asteroids when hit
- The game ends when an asteroid collides with your ship
- A shot cooldown (0.3s) prevents you from spamming bullets

## Controls

| Key | Action |
|-----|--------|
| `W` | Thrust forward |
| `S` | Thrust backward |
| `A` | Rotate left |
| `D` | Rotate right |
| `Space` | Shoot |

## Requirements

- Python 3.13+
- [uv](https://github.com/astral-sh/uv) (recommended) or pip

## Installation & Running

### With uv (recommended)

```bash
git clone https://github.com/thebenwalther/asteroids.git
cd asteroids
uv run main.py
```

### With pip

```bash
git clone https://github.com/thebenwalther/asteroids.git
cd asteroids
pip install pygame
python main.py
```

## Project Structure

```
asteroids/
├── main.py           # Game loop and collision detection
├── player.py         # Player ship logic and controls
├── asteroid.py       # Asteroid behavior and splitting logic
├── asteroidfield.py  # Spawns asteroids from screen edges
├── shot.py           # Projectile logic
├── circleshape.py    # Base class for all circular game objects
└── constants.py      # Tunable game parameters
```

## Built With

- [Python](https://www.python.org/) 3.13
- [pygame](https://www.pygame.org/) 2.6
