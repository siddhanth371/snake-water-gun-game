# Snake Water Gun Game

A simple Python game inspired by the classic Rock-Paper-Scissors game. The player chooses one of the following:

- `s` for Snake
- `w` for Water
- `g` for Gun

The computer randomly picks one option, and the winner is decided using the game rules.

## How the game works

- Snake drinks Water → Snake wins
- Water douses Gun → Water wins
- Gun shoots Snake → Gun wins

## Rules

- `snake` beats `water`
- `water` beats `gun`
- `gun` beats `snake`
- Same choice by both players results in a draw

## Run the project

1. Make sure Python is installed on your system.
2. Open a terminal in the project folder.
3. Run:

```bash
python main.py
```

4. Enter your choice:

- `s` for Snake
- `w` for Water
- `g` for Gun

## Example

```text
enter your choice:s
you chose snake
computer chose water
you win!
```

## Project files

- `main.py` — game logic and user interaction

## License

This project is open for learning and personal use.
