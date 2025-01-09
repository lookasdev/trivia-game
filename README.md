
# Trivia Game App

This is a simple Trivia Game application built using Streamlit. The app fetches trivia questions from the OpenTDB API and allows users to test their knowledge in various categories, difficulties, and question types.

## Features
- Select from a wide range of categories, difficulties, and question types.
- Answer multiple-choice or true/false questions.
- Track your progress and score during the game.
- Responsive user interface built with Streamlit.

## Requirements
To run the application, you need the following:
- Python 3.7 or higher installed on your machine.
- `streamlit` and `requests` libraries installed.

## Installation

1. Clone this repository or download the source code.
2. Install the required Python libraries using the following command:
   ```bash
   pip install streamlit requests
   ```

## Usage

1. Open the terminal in the directory containing the script.
2. Run the application with the following command:
   ```bash
   streamlit run trivia_app.py
   ```
   > Replace `trivia_app.py` with the filename you used in your PyCharm project.

3. The app will launch in your default web browser. If it doesn’t open automatically, navigate to the URL shown in the terminal (e.g., `http://localhost:8501`).

## How to Play

1. Select the number of questions, category, difficulty, and question type.
2. Click the "Start Game" button to begin.
3. Answer each question by selecting an option and clicking "Submit Answer."
4. Click "Next Question" to proceed to the next question.
5. At the end of the game, view your final score and restart if desired.

## Debugging

- If the app doesn't fetch questions, ensure you have an active internet connection.
- You can view the API request URL in the app (displayed for debugging purposes) to verify the request parameters.

## License
This project is open-source and free to use. Modify and adapt it as needed.

Enjoy the game!
