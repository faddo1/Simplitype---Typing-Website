# Simplitype — Typing Practice Game

A browser-based typing speed game that challenges users to type a set of random words as accurately and quickly as possible within a time limit. Built as a class project to practice front-end web development with HTML, CSS, and JavaScript.

---

## Overview

Simplitype presents the user with a randomized set of words and starts a countdown timer when they begin typing. The game tracks how many words the user completes correctly before time runs out, giving immediate visual feedback on each keystroke through word highlighting.

---

## Technologies Used

| Technology | Purpose |
| HTML | Page structure and layout |
| CSS | Styling, animations, and visual feedback |
| JavaScript | Game logic, timer, word generation, and input handling |

---

## Features

- Randomized word list on each new game
- Live word highlighting as the user types
- Countdown timer that starts on first keystroke
- WPM (words per minute) calculation at the end of each round
- Restart functionality to play again without refreshing the page

---

## Setup & Usage

No installation or build step required — runs entirely in the browser.

```bash
# Clone the repository
git clone https://github.com/faddo1/Simplitype---Typing-Website.git

# Open in browser
open Product/index.html
```

Or simply download the ZIP, unzip it, and open `index.html` in any modern browser.

---

## My Contribution

This was a class project completed with a team. My contributions included:

- Implementing the word highlighting and real-time input comparison logic in JavaScript
- Designing and styling the game interface using CSS
- Connecting the timer logic to the input events so the countdown begins on first keystroke

---

## Challenges & Lessons Learned

One of the trickier parts of this project was syncing the timer with the typing input — making sure the clock only starts when the user actually begins typing, not when the page loads. Working through that taught me a lot about JavaScript event listeners and how to manage state across multiple DOM elements.

I also learned how to break a UI interaction (typing a word) into smaller, trackable steps: character-by-character comparison, whole-word validation, and cursor advancement.

---

## Future Improvements

- Difficulty modes (more obscure words, shorter timer)
- Leaderboard to track personal best scores
- Mobile-friendly layout
