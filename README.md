# World Capital Quiz

This is a simple quiz application that tests your knowledge of world capitals.

## Features

- Randomized question order
- Score tracking

## Installation

1. Clone the repository: `git clone https://github.com/your-username/world-capital-quiz.git`
2. Navigate to the project directory: `cd world-capital-quiz`
3. Install dependencies: `npm i`
4. Set up the PostgreSQL database:
     - Create a database named "world".
        - Create a table named "capitals" with the following fields:
            - id (integer)
            - country (varchar(45))
            - capital (varchar(45))
        - Import the data from the `capitals.csv` file into the "capitals" table (make sure to include the header row)

## Usage

1. Start the quiz: `nodemon index.js`
2. Answer the questions by writing the correct answer.
3. Once you answer the qution wrong, your score will be displayed and you can restart the quiz.

