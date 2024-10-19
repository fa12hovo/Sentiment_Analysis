# Examining the 'Mass Shooting in the USA' Using Media Discourse

### Can we identify any religious or racial bias? Analyzing media discourse: Frequency Distribution and Sentiment Analysis

This project aims to analyze the media discourse surrounding **mass shootings in the USA** using natural language processing (NLP) techniques. We explore **frequency distributions**, **sentiment analysis**, and **bias detection** in news articles to see if any racial or religious bias is present.

---

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Project Structure](#project-structure)
- [Sentiment Analysis Methods](#sentiment-analysis-methods)
- [Contributing](#contributing)
- [License](#license)

---

## Description

This project uses **Natural Language Processing (NLP)** techniques to investigate potential bias in media coverage of mass shootings. We focus on sentiment analysis, identifying recurring patterns in the language used, and visualizing data using **bigrams** and **word clouds**.

In addition to the code, it is highly recommended to read the associated paper for a more comprehensive understanding of the methodology and findings.

## Features

- **Text Preprocessing**: Tokenization, removal of stopwords, and punctuation filtering.
- **Bigram Frequency Distribution**: Analyzes common word pairs (bigrams) from the text.
- **Word Cloud Generation**: Visual representation of the most frequent words used in media articles.
- **Sentiment Analysis**: Performed using multiple techniques, including:
  - **TextBlob**: For polarity (positive/negative/neutral sentiment) analysis.
  - **VADER**: A lexicon-based method suited for social media and short text.
  - **Naive Bayes**: For a more structured sentiment classification.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/discourse-analysis-mass-shooting.git
   cd discourse-analysis-mass-shooting
   ```

2. **Set up a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Windows: venv\Scripts\activate
   ```

3. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Discourse_Analysis_Project.ipynb
   ```

2. Follow the cells in the notebook for:
   - Tokenizing and cleaning the text.
   - Analyzing bigrams and visualizing them.
   - Generating word clouds.
   - Performing sentiment analysis using different techniques (TextBlob, VADER, etc.).
  
3. The results, including bigram frequencies, word cloud visualizations, and sentiment analysis scores, will be displayed in the notebook or saved in the project directory.

---

## Dependencies

- **Python 3.x**
- **NLTK**: For text preprocessing and tokenization.
- **TextBlob**: For sentiment analysis and NLP tasks.
- **VADER**: For sentiment analysis using a lexicon-based approach.
- **StyleCloud**: For generating word clouds.
- **Matplotlib/Seaborn**: For data visualization.
- **Pandas/Numpy**: For data manipulation.
- **Scikit-learn**: For machine learning models.

You can install all dependencies by running:
```bash
pip install -r requirements.txt
```

## Project Structure

```bash
.
├── Discourse_Analysis_Project.ipynb  # Main Jupyter notebook for the project
├── Bigdata.txt                       # Input data for analysis
├── stylecloudsake.txt                # Text file used to generate the word cloud
├── visuals/                          # Directory for storing generated visuals (word clouds, plots)
├── requirements.txt                  # File containing necessary dependencies
└── README.md                         # This README file
```

---

## Sentiment Analysis Methods

### TextBlob:
- **TextBlob** is used to compute the sentiment polarity of the text, ranging from -1 (negative) to 1 (positive).
- We also use it to calculate the counts of positive and negative words.

### VADER:
- **VADER (Valence Aware Dictionary for Sentiment Reasoning)** is used for analyzing sentiment, particularly suitable for social media text.
- It provides a compound score, classifying the overall sentiment as positive, negative, or neutral.

### Naive Bayes:
- **Naive Bayes Analyzer** within TextBlob helps classify sentiment based on probabilistic techniques.
  
---

## Contributing

We welcome contributions! If you would like to contribute to this project, feel free to fork the repository and submit a pull request with improvements or suggestions.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact

For any questions or issues, feel free to contact:
- **Faroque Ahmed** - Faroqueazad.jnu13@gmail.com
