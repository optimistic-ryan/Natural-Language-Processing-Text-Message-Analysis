# Natural Language Processing Text Message Analysis

This Python script performs sentiment analysis and key phrase extraction on the National University of Singapore (NUS) Corpus dataset to gain insights into sentiment distribution and prominent phrases.

## Features

- Text preprocessing: lowercasing, punctuation removal, stopword removal, stemming
- Tokenization and POS tagging using nltk
- Sentiment analysis using Naive Bayes Classifier (70% accuracy)
- Key phrase extraction using POS tag patterns (JJ+NN, RB+JJ)
- Data visualization using seaborn and matplotlib

## Usage

This project is useful for researchers and developers working on text analysis, sentiment analysis, and natural language processing tasks. The techniques demonstrated can be applied to other similar datasets or adapted for different NLP tasks.

## Installation

1. Clone the repository or download the source code.
2. Install the required dependencies using `pip` or `conda`:
```
pip install pandas numpy nltk seaborn matplotlib bs4
```
    or
```
conda install pandas numpy nltk seaborn matplotlib beautifulsoup4
```
3. Run the Python script to perform sentiment analysis and key phrase extraction on the NUS Corpus dataset.

## Dependencies

- pandas
- numpy
- nltk
- seaborn
- matplotlib
- bs4

## Quick Start
1. Make sure you have Python 3.x installed. You can check your Python version by running `python --version` in your command prompt or terminal.
2. Clone the repository or download the source code.
3. Navigate to the project directory in your command prompt or terminal.
4. Install the required dependencies using `pip` or `conda`:
```
pip install pandas numpy nltk seaborn matplotlib bs4
```
    or
```
conda install pandas numpy nltk seaborn matplotlib beautifulsoup4
```
5. Download the NUS Corpus dataset and place it in the project directory.
6. Update the file path in the Python script, if necessary.
7. Run the Python script:
```
python Natural Language Processing Text Message Analysis.py
```
8. The script will perform sentiment analysis and key phrase extraction on the dataset, and generate visualizations for sentiment score distributions and prominent phrases.

## Contributing
Contributions are welcome! If you'd like to improve the project or add new features, please fork the repository and submit a pull request with your changes.

## License
This project is released under the MIT License - see the LICENSE file for details.

