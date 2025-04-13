# Irish Political Manifestos Analysis (2024)

## Project Overview
This repository contains a text analysis of Irish political party manifestos published in 2024. The analysis uses the `quanteda` package in R to process and analyze the textual content of political manifestos, with a focus on sentiment analysis and policy themes.

## Dataset
The analysis uses the "Ireland_Corpus2.0.csv" dataset, which contains:
- 17,212 sentences from Irish political manifestos
- Metadata including party names, publication dates, and country information
- Sentence-level segmentation for detailed analysis

## Requirements
- R (version 4.4.0 or higher)
- Required R packages:
  - quanteda (v4.2.0)
  - dplyr
  - ggplot2

## Analysis Workflow
The analysis follows these key steps:
1. Loading and preprocessing the manifesto data
2. Creating a quanteda corpus with document IDs based on text_id
3. Filtering manifestos published in 2024
4. Tokenizing the text data
5. Applying dictionaries for thematic analysis
6. Performing sentiment analysis
7. Visualizing results with ggplot2

## File Structure
- `Ireland_Corpus2.0.csv`: Raw dataset containing manifesto sentences
- `2025_qta_erkilic_irem_homework01.html`: HTML output of the analysis
- `2025_qta_erkilic_irem_homework01.qmd`: Quarto script containing the analysis code

## Key Findings
The analysis examines how different Irish political parties discuss key policy areas in their 2024 manifestos, with particular attention to:
- Housing policy mentions
- Sentiment patterns across parties
- Sentence-level linguistic features

## Usage
To reproduce this analysis:
1. Clone this repository
2. Ensure you have R and the required packages installed
3. Run the analysis script with the dataset in the same directory

## Acknowledgments
This analysis uses the Ireland Corpus 2.0 dataset available at: https://doi.org/10.34894/VKQSPO


