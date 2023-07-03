# Wordle Difficulty Analysis
**Vince Gregoric**  
**July 1, 2023**

## Overview
This project is an attempt to develop a machine learning model to predict the difficulty of solving a Wordle puzzle given the answer word. It is a personal project I started as an application of the machine learning skills I learned while completing the Data Scientist: Machine Learning career path on Codecademy.com. I really enjoy puzzles, and play Wordle regularly, so I thought it would be fun to build a machine learning model around Wordle. 

The data for this projects comes from the following sources:
- https://twitter.com/WordleStats
- https://wordfinder.yourdictionary.com/wordle/answers/
- https://github.com/IlyaSemenov/wikipedia-word-frequency/tree/master
- https://en.wikipedia.org/wiki/Letter_frequency

For more information on how the data was obtained from these sources, see the Wordle Data Scraping notebook file (`wordle_data_scraping.ipynb`).

## File Structure
This project contains the following files:
- **wordle_analysis.ipynb:** The main analysis file, written using Jupyter notebook
- **wordle_data_scraping.ipynb:** The Jupyter notebook used to scrape data from the web and generate the `wordle_data.csv` file
- **wordle_data.csv:** The data file for this project, generated from `wordle_data_scraping.ipynb`
- **summary_slides.pdf:** A slide deck summarizing the resutls of this project
- **README.md:** This file, containing an overivew of the project
- **LICENSE.md** The license for the project