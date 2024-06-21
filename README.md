# Simple Chat Bot
## Project Overview
This project provided through Hyperskill, implements an interactive quiz bot. 
The bot engages with the user by asking for their name, guessing their age, counting numbers, and providing a programming knowledge quiz. 
This bot is designed to demonstrate basic JavaScript functionalities such as user input handling, loops, conditionals, and functions.

## Features
- Greeting: The bot introduces itself and states its creation year. This can be changed in the `greet(bot_name, birth_year)` function.
- Name Reminder: The bot asks for the user's name and compliments it.
- Age Guessing: The bot guesses the user's age based on the remainder of the division by 3, 5, and 7.
- Counting: The bot counts up to a number specified by the user.
- Quiz: The bot quizzes the user with a multiple-choice question about programming knowledge.
- Completion: The bot congratulates the user upon completing the quiz and ends the interaction.

## Getting Started
### Prerequisites
- Node.js installed on your machine.
- sync-input package for synchronous user input.

```bash
npm install https://github.com/hyperskill/sync-input/archive/v1.tar.gz
```

### Usage
Run the script using Node.js:

```bash
node index.js
```

## Example Interaction
```bash
Hello! My name is Aid.
I was created in 2024.
Please, remind me your name.
James
What a great name you have, James!
Let me guess your age.
Enter remainders of dividing your age by 3, 5 and 7.
1  
1
3
Your age is 31; that's a good time to start programming!
Now I will prove to you that I can count to any number you want.
10
0 !
1 !
2 !
3 !
4 !
5 !
6 !
7 !
8 !
9 !
10 !
Let's test your programming knowledge.
Why do we use methods?
1. To repeat a statement multiple times.
2. To decompose a program into several small subroutines.
3. To determine the execution time of a program.
4. To interrupt the execution of a program.
Your answer: 1
Please, try again.
Your answer: 6
Please pick a number from 1-4.
Your answer: 2
Correct!
Congratulations, have a nice day!
```

## Conclusion
This was a simple project to get accustomed to the JavaScript language. There was nothing too complicated involved.
