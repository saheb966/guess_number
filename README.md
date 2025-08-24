## 🎮 Guess the Number (Tkinter Edition)

A small GUI-based number guessing game built with Python and Tkinter. The user tries to guess a randomly chosen number between 1 and 10. Feedback is given after each guess, and the number of attempts is tracked.

---

### 🧠 How to Play

1. Enter a number between **1 and 10** in the input field.
2. Click the **"Check"** button.
3. The game will tell you if your guess is too low, too high, or correct.
4. When you guess correctly, it will show the number of attempts taken.
5. Click **"Restart"** to play a new game.

---

### 🚀 Getting Started

#### ✅ Prerequisites

Make sure Python is installed on your system. This game uses the built-in `tkinter` module, which comes pre-installed with most Python distributions.

#### ▶️ To Run the Game

1. Save the Python script as `guess_the_number.py`
2. Open a terminal and run:

   ```bash
   python guess_the_number.py
   ```

---

### 🧾 Code Overview

* `secret_number` – a random number from 1 to 10
* `attempts` – tracks how many tries you've taken
* `check_guess()` – checks the user's input and updates the game state
* `restart_game()` – resets the game with a new number

---

### 📦 Features

* Simple and intuitive GUI
* Input validation
* Resettable game session
* Feedback for every guess


Let me know if you want to include enhancements like difficulty settings or high-score tracking.
