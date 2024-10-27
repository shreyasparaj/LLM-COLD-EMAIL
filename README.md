# 📧 Cold Mail Generator

A cold email generator for service companies using Groq, Langchain, and Streamlit. This tool allows users to input the URL of a company's careers page, extracting job listings and generating personalized cold emails that include relevant portfolio links sourced from a vector database based on specific job descriptions.

## Features

- Input the URL of a company's careers page.
- Extract job listings to generate personalized cold emails.
- Include relevant portfolio links based on job descriptions.
- Manual Edit, Save as Draft, Copy, Download features

## Usage Example

Imagine a scenario where a software development company can provide dedicated engineers to a major company. This tool facilitates outreach via personalized cold emails.


## Set-up

1. **API Key**: Get an API key from [Groq Console](https://console.groq.com/keys) and update the value of `GROQ_API_KEY` in `app/.env` with your created API key.

2. **Install Dependencies**: Install the required Python packages:
    ```bash
    pip install -r app/requirements.txt
    ```

3. **Run the Application**: Start the Streamlit app:
    ```bash
    streamlit run app/app.py
    ```

