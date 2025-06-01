# SMS Spam Detection

This project implements a simple **SMS Spam Detection** system using a machine learning model.

## Project Overview

- This project builds a machine learning model to classify SMS messages as **spam** or **ham** (not spam).

- The dataset `spam.csv` contains 5572 rows and 5 columns.  
- The first few columns are: `v1`, `v2`, `Unnamed: 2`.

## Files

- `main.ipynb` — Jupyter notebook containing data exploration, preprocessing, model training, and evaluation.  
- `spam.csv` — Dataset of SMS messages labeled as spam or ham.

## How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/kamrul28890/SpamBot.git
    cd SpamBot
    ```

2. Install required packages (you can use `pip` or `conda`):
    ```bash
    pip install -r requirements.txt
    ```

3. Open the notebook:
    ```bash
    jupyter notebook main.ipynb
    ```

4. Run all cells to train the spam detection model and view the results.

## Dataset Information

The `spam.csv` file is a labeled dataset where each message is marked as:
- `spam` — unwanted/advertising content.
- `ham` — legitimate message.

## License

This project is for educational purposes.
