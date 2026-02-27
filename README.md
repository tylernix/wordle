# Wordle

A Wordle clone built as part of a team building event — putting on our product hats and using AI to create delightful customer experiences.

## Game Modes

- **Daily** — Everyone gets the same word each day. Come back tomorrow for a new one.
- **Free Play** — Random words, unlimited games.
- **Challenge A Friend** — Generates a shareable link with a hidden word. Neither the creator nor the recipient knows the word in advance, so everyone can play.

## Difficulty

All modes give you 6 guesses. Difficulty changes the word pool and rules:

- **Easy** — Common, everyday words.
- **Medium** — Less common words. Must reuse hints from previous guesses (green/yellow letters).
- **Hard** — Obscure words. Must reuse hints.
- **Talent Mode** — Optional toggle on any difficulty. Guessed letters fade away after 5 seconds.

After solving, hit **Share** to copy your results as an emoji grid with your time and difficulty — perfect for pasting in Slack.

## Setup

Open `index.html` in a browser, with `wordle-words.js` in the same directory. 
