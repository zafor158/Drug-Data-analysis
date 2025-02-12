# Drug-Data-analysis
📊 Dataset Collection & Visualization: Web Scraping with Python

This project focuses on building an AI-powered drug recommendation system and medical chatbot using RAG (Retrieval-Augmented Generation). The dataset is collected from Drugs.com and other sources through web scraping, followed by data preprocessing and visualization for better insights.

# 🔍 Data Collection Process
Data Source:
* Primary Source: Drugs.com
* Other credible sources for drug-related information
* Web Scraping Methodology:

# Extracts comprehensive drug details, including:
* Drug Name, Generic Name, Drug Class,Uses, Warnings, Dosage Information (including missed doses and overdoses),Side Effects and Pre-Use Instructions
* Uses BeautifulSoup for parsing HTML and retrieving structured data.

# Data Input & Output:
* Reads drug names from an Excel file.
* Constructs URLs dynamically for each drug.
* Saves extracted data into a cleaned Excel file for further analysis.

# Error Handling & Optimization:
* Handles missing pages (404 errors) gracefully.
* Implements intelligent section extraction for relevant medical information.
* Ensures robust parsing logic for dosage details and side effects.
