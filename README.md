# Tic-Tac-Toe 🎮

A clean, responsive Tic-Tac-Toe game built with vanilla HTML, CSS, and JavaScript. Supports two-player mode and a computer opponent with three difficulty levels.

---

## Features

- **Two Game Modes** — Play against a friend locally or challenge the computer
- **Three AI Difficulty Levels**
  - 🟢 Easy — Computer plays randomly
  - 🟡 Medium — Computer plays smart ~50% of the time
  - 🔴 Hard — Unbeatable AI using the Minimax algorithm
- **Persistent Scoreboard** — Tracks wins for X, O, and draws across rounds
- **Animated UI** — Smooth piece placement, win highlight pulse, and AI thinking indicator
- **Responsive Design** — Works on desktop and mobile browsers

---

## Getting Started

### Prerequisites

No build tools or dependencies required. Just a modern web browser.

### Run Locally

1. Clone or download this repository
2. Open `index.html` in any web browser

```bash
# Or serve it with VS Code Live Server (recommended)
# Right-click index.html → Open with Live Server
```

---

## Project Structure

```
tic-tac-toe/
└── index.html      # All HTML, CSS, and JavaScript in a single file
```

---

## How to Play

1. **Choose a mode** — Toggle between *2 Players* and *vs Computer*
2. **Select difficulty** (AI mode only) — Easy, Medium, or Hard
3. **Take turns** clicking empty cells to place your mark (X goes first)
4. **Win** by getting three of your marks in a row — horizontally, vertically, or diagonally
5. Use **New Game** to start a fresh round (scores are preserved)
6. Use **Reset Scores** to clear all scores and start over

---

## AI Logic

| Difficulty | Behavior |
|------------|----------|
| Easy       | Picks a random empty cell |
| Medium     | 50% chance of playing optimally (win/block), 50% random |
| Hard       | Full [Minimax](https://en.wikipedia.org/wiki/Minimax) — never loses |

---

## Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, CSS Grid, keyframe animations
- **Vanilla JavaScript** — No frameworks or libraries
- **Google Fonts** — [Syne](https://fonts.google.com/specimen/Syne) + [Space Mono](https://fonts.google.com/specimen/Space+Mono)

---

## Recommended VS Code Extensions

- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) — Auto-refresh on save
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) — Code formatting

---

## License

This project is open source and free to use.