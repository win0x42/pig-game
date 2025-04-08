# 🎲 Pig Game

Pig Game is a fun two-player dice game built using HTML, CSS, and JavaScript. It's a great beginner-friendly project to practice DOM manipulation and game logic.

## 🧩 Game Rules

1. The game has two players, taking turns.
2. On a player’s turn, they can **roll the dice**:
   - If the roll is not `1`, the number is added to their **current score**.
   - If the player rolls a `1`, their **current score is lost**, and it’s the next player’s turn.
3. The player can choose to **“Hold”**:
   - Their current score is added to their **total score**, and it becomes the next player's turn.
4. The first player to reach or exceed **100 points** wins the game.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)

## 🚀 Getting Started

To play the game locally:

```bash
git clone https://github.com/your-username/pig-game.git
cd pig-game
open index.html
```

## 📁 Project Structure

```
pig-game/
├── /image  
├── dice-1.png
├── dice-2.png
├── dice-3.png
├── dice-4.png
├── dice-5.png
├── dice-6.png
├── image.png
├── index.html       
├── style.css        
├── script.js  
└── README.md
```

## 🎮 Features

- Dice rolling animation and result display
- Turn-based score tracking
- Player switching logic
- Win detection and message display
- New game/reset functionality

## 💡 Possible Improvements

- Add sound effects or background music
- Allow setting a custom winning score
- Limit the number of dice rolls per turn
- Add a single-player mode vs. AI

## 👨‍💻 Developer

- Name: Simon Cheong
- GitHub: https://github.com/win0x42

> 🧠 This is a project made for learning purposes.
