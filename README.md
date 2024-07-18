# Legal NLP Project - DB_COMP

## Overview

This repository is part of a personal project that aims to apply Natural Language Processing (NLP) techniques to the legal domain. The goal is to analyze Competition Law decisions using advanced text processing methods.

## Features

### DB_COMP Web Scraper
- Scrapes decision documents from the DB_COMP website.
- Extracts key information such as decision dates, titles and URLs.
- Stores the extracted data in a structured format for easy analysis.

### Downloading and Processing PDFs from DB COMP website

The code in this section:
- Downloads a set of PDFs from given URLs.
- Extracts the text content.
- Preprocesses the text for further analysis, including tokenization and cleaning.

### Extracting Outcomes of Decisions

This segment:
- Extracts the outcomes of decisions from the processed text.
- Focuses on identifying and isolating specific sections that pertain to the decisions and their outcomes.

### Text Summarization of Outcomes

The repository includes functionality for:
- Summarizing the extracted outcomes using the GPT-3.5-turbo-0125 model with a zero-shot prompt.
- The prompt guides the model to summarize whether the decision sanctioned or did not sanction the involved firms, starting with 'Sanction' or 'Not Sanction' respectively.

### Merging Data and Creating Summary Database

The final step involves:
- Merging the processed data with a scraped database.
- Adding a column indicating whether the decision sanctioned or did not sanction the involved firms.
- Resulting in a database with over 500 decisions, each with a summary of the outcome.

## Project Objective

This project aims to leverage NLP techniques to enhance the analysis of legal documents, providing valuable insights and summaries that can aid in understanding Competition Law decisions more effectively.

Contact Details:
Mail: pa.malcav@gmail.com
Linkedin: https://www.linkedin.com/in/piero-alexis-malca-vilchez-27b3b1129/ 
