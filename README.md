# Article Summarizer

## Overview

The Article Summarizer is a Python-based tool that leverages Natural Language Processing (NLP) techniques to generate concise summaries of articles. It incorporates a variety of libraries, including Spacy, BeautifulSoup, Streamlit, and others, to provide a robust solution for summarizing both external news articles and custom user-provided content.

## Features

- **NLP Summarization:** Utilizes Spacy for advanced tokenization and stop words removal, ensuring accurate and meaningful summarization.
- **Web Scraping:** Employs BeautifulSoup for web scraping to dynamically extract content from web articles.
- **Dynamic Content Retrieval:** Utilizes the `requests` library for making HTTP requests, enabling dynamic content extraction.
- **Configurable Settings:** Implements ConfigParser for handling configurations, allowing users to customize summarization parameters.
- **Interactive Web Interface:** Developed using Streamlit, providing an interactive and user-friendly web application for article summarization.

## Prerequisites

- Python 3.x
- Required Python libraries: spacy, requests, streamlit, beautifulsoup4

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/article-summarizer.git
