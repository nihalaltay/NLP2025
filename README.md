# Zipf's Law in Turkish and English Song Lyrics Analysis

This repository contains the code for analyzing the validity of Zipf's Law in song lyrics from two music groups: Cage the Elephant (English) and Adamlar (Turkish).

## Overview

The project involves the following steps:
1. **Data Collection:**  
   - Song lyrics were collected manually from related websites.
2. **Data Cleaning:**  
   - Unwanted parts such as the song titles were removed using regular expressions.
   - The lyrics were converted to lowercase, punctuation was removed, and the text was tokenized.
3. **Analysis:**  
   - For each unique word, its frequency and length (in characters) were calculated.
4. **Visualization:**  
   - Scatter plots were created to visualize the relationship between word frequency and word length.

## Dependencies

To run the code, you need to have the following dependencies installed:
- **Python 3.7+**

- **Python libraries:**
  - `pandas` (for data manipulation)
  - `matplotlib` (for visualization)
  - `seaborn` (for enhanced visualizations)
  - `nltk` (for tokenization)
  - The built-in `re` module is used for regular expressions, so no installation is required for that.

You can install the necessary libraries using pip:
```bash
pip install pandas matplotlib seaborn nltk
