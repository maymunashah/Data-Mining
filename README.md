# Sentiment Analysis of Car and Hotel Reviews

## OpinRank Review Dataset

This repository contains a sentiment analysis project conducted on the OpinRank Review Dataset, originally curated by Ganesan, Kavita, and Zhai, ChengXiang in 2011, available at the UCI Machine Learning Repository [https://doi.org/10.24432/C5QW4W](https://doi.org/10.24432/C5QW4W). The original dataset can be found [here](https://archive.ics.uci.edu/dataset/205/opinrank+review+dataset).

### Overview

#### Dataset Details

- **Car Reviews (Total ~42,230):**
  - **Time Period:** 2007, 2008, 2009.
  - **Data Fields:** Dates, authors, favorites, full textual reviews.
  - **Organization:** Model years (2007, 2008, 2009).

- **Hotel Reviews (Total ~259,000):**
  - **Locations:** 10 cities including Dubai, New York, London.
  - **Data Fields:** Date, review title, full review.

#### Data Processing

We have transformed the original dataset into CSV files for ease of use and accessibility. The project focuses on sentiment analysis using various machine learning models.

#### Models and Techniques Used

**Models:**
- Naive Bayes
- Logistic Regression
- Random Forest

**Feature Representation Techniques:**
- CountVectorizer
- TF-IDF

**Labeling Techniques:**
- Vader Lexicon
- Afinn Lexicon
- Text Blob Library

**Metrics:**
- Comparative Analysis based on F1-score and Accuracy.

### Getting Started

1. **Dataset Access:**
   - The original dataset can be accessed [here](https://archive.ics.uci.edu/dataset/205/opinrank+review+dataset).
   - Our processed CSV files are available in the 'data' directory.

2. **Code and Models:**
   - The 'code' directory contains Jupyter notebooks and Python scripts detailing the sentiment analysis using the specified models and techniques.

3. **Results and Analysis:**
   - Results and comparative analyses based on F1-score and accuracy are available in the 'results' directory.

Feel free to explore, contribute, or use this repository for your sentiment analysis projects! If you have any questions or suggestions, please open an issue.

**Note:** Please ensure proper attribution to the original dataset creators, Ganesan, Kavita, and Zhai, ChengXiang, as per their licensing terms.
