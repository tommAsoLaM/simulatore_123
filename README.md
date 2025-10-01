
# 1,2,3 Game Simulator

This project simulates the card game **1,2,3** using a standard Neapolitan deck of 40 cards. The simulator is designed to gather statistical data about the game, such as the distribution of attempts needed to win and the probability of winning.

## Game Rules

- The deck consists of 40 cards, with values from 1 to 10, each appearing 4 times.
- The deck is shuffled before each game.
- The game proceeds by checking each card in the shuffled deck in order.
- At each step, you are "looking for" the number 1, then 2, then 3, cycling through these as you go through the deck.
- **You lose** if you encounter a card with the value you are currently looking for (e.g., you are looking for a 2 and the next card is a 2).
- **You win** if you make it through the entire deck without this happening.

## Program Purpose

The simulator runs many games in succession, recording how many attempts (failed games) are needed before a win occurs. It then analyzes and visualizes the results, providing insights into:

- The distribution of attempts needed to win
- The average, minimum, and maximum number of attempts
- The probability of winning on the first try

## Features

- Efficient simulation of thousands of games
- Data collection for each game
- Visualization of the distribution of attempts using bar charts
- Calculation of statistical measures (mean, min, max)

## How to Use

1. Run the notebook or script.
2. The simulation will automatically generate and shuffle the deck, play the game multiple times, and collect data.
3. Results and plots will be displayed, showing the distribution of attempts needed to win.

## Requirements

- Python 3.x
- `matplotlib`
- `numpy`
- `pandas`

Install dependencies with:
```
pip install matplotlib numpy pandas
```

---

Feel free to modify the simulation parameters (number of games, deck size, etc.)
