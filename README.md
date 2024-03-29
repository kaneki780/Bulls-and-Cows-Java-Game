Bulls and Cows Game Documentation

Introduction

Bulls and Cows is a classic code-breaking game where the player attempts to guess a secret code generated by the computer. The game provides feedback in the form of "bulls" and "cows" to guide the player towards the correct answer.

Code Structure

The Bulls and Cows game is implemented in Java with the following classes:

Grade: Represents the feedback given to the player after each guess, containing the count of bulls and cows.

Game: Manages the gameplay logic, including generating the secret code, accepting guesses from the player, and providing feedback.

Main: Entry point of the application, creates an instance of the Game class and starts the game.

Gameplay Flow

Initialization: The game prompts the player to input the length of the secret code and the number of possible symbols that can be used.

Secret Generation: The game generates a random secret code based on the specified length and symbol range. The secret code is not revealed to the player.

Game Start: The game begins, and the player starts guessing the secret code.

Guessing: In each turn, the player inputs a guess. The game evaluates the guess and provides feedback in terms of bulls and cows.

A "bull" indicates a correct digit in the correct position.

A "cow" indicates a correct digit in the wrong position.

Feedback: After each guess, the game prints the grade (number of bulls and cows) to the player.

Win Condition: The game continues until the player guesses the correct code (all bulls). Upon winning, a congratulatory message is displayed.

Error Handling

The game validates user inputs to ensure they are within acceptable ranges.

Error messages are displayed for invalid inputs, and the game exits if critical errors occur.

Assertions are used to ensure the correctness of internal logic.

Running the Game

To run the Bulls and Cows game, execute the Main class. Follow the prompts to input the length of the secret code and the number of possible symbols. Then, start guessing the secret code until you win the game.

Conclusion

The Bulls and Cows game provides an engaging challenge where players can test their code-breaking skills. With its simple yet addictive gameplay, it offers hours of entertainment.
