Hangman is a classic word game in which you must guess secret word before you run out of attempts!
===
This is a ruby program of the game Hangman
---
You can start the program by typing this command on the command line:
```
ruby main.rb
```
***
## How to play Hangman?
Programm thinks a word. Player try to guess what it is one letter at a time. 
Programm draws a number of underscores equivalent to the number of letters in the word. 
If a player suggests a letter that occurs in the word, the programm fills in the blanks 
with that letter in the right places. If the word does not contain the suggested letter, 
programm draws one element of a hangman’s gallows.
The game continues until the player guesses the word, or he runs out of attempts.
***
You can add your words to the program. To do this, you need to add your words in the *'data/words.txt'* file, each on a new line.
You can also change the number of guessing attempts in the *'lib/game.rb'* file, `TOTAL_ERRORS_ALLOWED` constant
