# 2048 Game (Tkinter Version)

## Project Description

This is a desktop version of the classic **2048 game** built using **Python** and **Tkinter**.
The player uses arrow keys to combine numbered tiles and reach the 2048 tile.

The game features:

* 4x4 grid layout
* Random tile generation (2 or 4)
* Score tracking
* Keyboard controls
* Automatic grid updates

---

## Features

* 4x4 dynamic grid
* Random tile generation after each move
* Arrow key controls (Up, Down, Left, Right)
* Tile merging logic
* Live score tracking
* Clean Tkinter GUI

---

## Tech Stack

* Python 3
* Tkinter (Built-in Python GUI library)
* Random module

---

## Project Structure

```
project-folder/
│
└── index.ipynb   # Contains the complete 2048 game code
```

---

## How to Run

### Step 1: Install Python

Make sure Python 3 is installed.

### Step 2: Install Jupyter Notebook (if needed)

```
pip install notebook
```

### Step 3: Run the notebook

```
jupyter notebook
```

Open `index.ipynb` and run all cells.

---

## How to Play

* Use Arrow Keys:

  * Up
  * Down
  * Left
  * Right
* Tiles with the same number merge when they collide.
* Each merge increases your score.
* The goal is to reach the **2048 tile**.

---

## Game Logic Overview

* A 4x4 grid is initialized with all zeros.
* Two tiles are added at random positions.
* On each move:

  1. Tiles shift in the pressed direction.
  2. Matching tiles merge.
  3. Score updates.
  4. A new tile appears randomly.

---

## Future Improvements (Optional)

* Add restart button
* Add game over detection popup
* Add high score saving
* Add animations
* Add dark mode UI

---

## License

This project is open-source and free to use for learning purposes.
