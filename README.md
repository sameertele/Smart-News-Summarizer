# Smart News Summarizer

**A web application powered by Large Language Models (LLMs) to fetch and summarize news headlines from various categories and countries.**

## Features

* **Fetch Latest News:** Retrieves top news headlines based on user-selected category and country using the NewsAPI.
* **Intelligent Summarization:** Employs the OpenAI API (GPT-3.5 Turbo) to generate concise summaries of the fetched headlines.
* **User-Friendly Interface:** Built with Streamlit for an intuitive and easy-to-use web experience.
* **Customizable Parameters:** Allows users to select news categories, countries, and the number of headlines to summarize.
* **Secure API Key Input:** Prompts users to enter their API keys directly in the application, keeping them private.

## Technologies Used

* **Python:** The primary programming language.
* **Streamlit:** For creating the interactive web interface.
* **NewsAPI:** To fetch news headlines from a wide range of sources.
* **OpenAI API:** To leverage powerful LLMs for text summarization.
* **Requests:** For making HTTP requests to the NewsAPI.

## Prerequisites

Before you can run the Smart News Summarizer, you need to have the following:

* **Python 3.6 or higher:** Ensure you have Python installed on your system.
* **pip:** The Python package installer (usually comes with Python).
* **NewsAPI API Key:**
    * Sign up for a free account at [https://newsapi.org/](https://newsapi.org/).
    * Obtain your API key from your account dashboard.
* **OpenAI API Key:**
    * Sign up or log in to the OpenAI Platform at [https://platform.openai.com/](https://platform.openai.com/).
    * Navigate to the API keys section and create a new API key.
