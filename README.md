# Project: 2026 Budget Speech NLP Analysis (Lawrence Wong)

This notebook analyzes a transcript of Prime Minister Lawrence Wong’s 2026 Budget Speech using basic NLP techniques. It cleans and tokenizes the text, calculates word frequencies, visualizes the top 20 keywords, and uses dispersion-style plots to examine when key terms appear throughout the speech (e.g., “singapore”, “support”, “ai”) as well as comparisons like business vs family keywords.

## What it does
Cleans raw transcript text

lowercasing, removing punctuation, digits, and English stopwords

custom stopwords added: also, 's, us, must, many

Tokenizes the speech into words (NLTK)

Computes word frequency distribution (Top 20 keywords)

## Visualizes:

Top 20 keyword bar chart (Lets-Plot)

Keyword dispersion plots (token index vs selected keywords)

Compares keyword themes (example: companies/workers/families)

Tech stack

## Python

NLTK (tokenization, stopwords, frequency distribution)

pandas / numpy

lets-plot (ggplot-style charts)

## Input

Lawrence Wong Speech.txt (speech transcript text file)

## Output examples

Top-20 keyword frequency chart

Dispersion plots showing the “timeline” of selected keywords across the speech

# How to run

Install dependencies:

nltk, pandas, numpy, lets-plot

Make sure Lawrence Wong Speech.txt is in the same folder as the notebook

Run all cells in 2026 Budget Speech Analysis_EDITED.ipynb
