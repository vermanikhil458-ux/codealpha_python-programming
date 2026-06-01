Hangman Game - README.md
# Hangman Game

A simple text-based Hangman game written in Python. The player must guess a randomly selected word one letter at a time before running out of attempts.

## Features

- Random word selection from a predefined list
- Maximum of 6 incorrect guesses allowed
- Displays guessed letters and remaining blanks
- Input validation for user entries
- Win and lose conditions
- Console-based gameplay

## Technologies Used

- Python
- random module
- Lists
- Strings
- Loops (while, for)
- Conditional statements (if-else)

## How to Run

### Prerequisites

Make sure Python 3 is installed on your system.

Download Python from:
https://www.python.org/downloads/

### Steps

1. Save the program as `hangman.py`.
2. Open a terminal or command prompt.
3. Navigate to the folder containing the file.
4. Run the program using:

```bash
python hangman.py
or

python3 hangman.py
How to Play
The game randomly selects a word from a predefined list.

The word is displayed as underscores (_) representing hidden letters.

Enter one letter at a time when prompted.

If the letter exists in the word, it will be revealed.

If the letter is incorrect, one attempt is deducted.

The game ends when:

The player correctly guesses the entire word, or

The player reaches 6 incorrect guesses.

Example
Welcome to Hangman!

Word: _ _ _ _ _ _

Guess a letter: p
Correct!

Word: p _ _ _ _ _
Predefined Words
python

computer

hangman

programming

keyboard

Project Structure
hangman.py
README.md
Learning Concepts Demonstrated
Random selection using random.choice()

String manipulation

List operations

User input handling

Loop control

Conditional logic

Author
Created as a beginner-friendly Python project for learning programming fundamentals.

nikhil

