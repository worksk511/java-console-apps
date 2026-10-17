# Java Console Apps

Three small interactive Java programs covering menus, input handling, collections and game logic.

![Java](https://img.shields.io/badge/Java-22d3ee?style=flat-square&logo=openjdk&logoColor=white&labelColor=0b1220)

| Program | What it does | Concepts |
|---|---|---|
| **ATM Interface** (`Atminterface.java`) | Menu-driven ATM: withdraw, deposit and check balance, with validation for negative amounts and insufficient funds | Classes and encapsulation, menu loop, input validation |
| **Number Game** (`Numbergame.java`) | Guess a random number from 1–100 in 5 attempts with higher/lower hints, across multiple rounds with a running score | Random numbers, loops, game state |
| **Word Counter** (`Wordcounter.java`) | Counts the words in a line of text, ignoring punctuation and common stop words, and prints how often each word appears | String splitting with regex, `HashMap` frequency counting |

## Run

Requires Java 8 or later.

```bash
javac Atminterface.java && java Atminterface
javac Numbergame.java && java Numbergame
javac Wordcounter.java && java Wordcounter
```

## Background

Built in 2023 as tasks for the CodSoft Java programming internship.

---

Built by [Jahnvi Singh](https://jahnvi-singh.netlify.app) · Software Engineering @ ANU
