# AI-Powered-Career-Advisor-LinkedIn-Profile-Analysis-and-Job-Matching

# An LLM-Powered Algorithm for LinkedIn Profile-Based Job Matching and Salary Insights 🚀

**Authors**: Ali CHERIFI ALAOUI, Fodié NIAKATE

---

## Overview

This project leverages **Large Language Models (LLMs)**, specifically OpenAI’s GPT-4 via the OpenAI API, combined with multiple APIs from **RapidAPI**, to analyze LinkedIn profiles, recommend suitable jobs, and provide salary benchmarks. The tool empowers users to identify tailored career opportunities, negotiate salaries confidently, and avoid undervaluation during interviews.

---

## Table of Contents

1. [Features](#features)
2. [How It Works](#how-it-works)
3. [Setup Instructions](#setup-instructions)
4. [Future Enhancements](#future-enhancements)
5. [License](#license)

---

## Features

- **LinkedIn Profile Scraping**: Retrieves detailed user profiles using the LinkedIn Scraper API (via RapidAPI).
- **LLM-Driven Analysis**: Uses GPT-4 through OpenAI’s API to analyze profiles and suggest tailored job titles, roles, and skills based on the extracted data.
- **Real-Time Job Matching**: Searches for recently published job postings that closely match the user’s profile and suggested roles, using the Job Search API (via RapidAPI).
- **Salary Benchmarking**: Provides salary insights based on the job title, location, and industry using the Glassdoor Salary API (via RapidAPI).

---

## How It Works

1. **Profile Scraping**
   - The user provides their LinkedIn profile URL.
   - The tool scrapes the profile data using the LinkedIn Scraper API (via RapidAPI).

2. **Profile Analysis with LLM**
   - The scraped profile data is processed via OpenAI’s GPT-4 API to identify key skills, experiences, and potential job matches.
   - Suggestions include tailored job titles, relevant keywords for job searches, and actionable insights.

3. **Job Matching**
   - The tool searches for available job opportunities using the Job Search API (via RapidAPI).
   - Matches are based on the roles suggested by GPT-4, as well as the user’s preferences for location, industry, and keywords.

4. **Salary Insights**
   - The Glassdoor Salary API (via RapidAPI) is used to fetch expected salaries for the suggested roles, factoring in the location and industry.
   - This helps users negotiate confidently and avoid undervaluation.

---

## Setup Instructions

### Prerequisites

- Python 3.8 or higher
- API Keys:
  - OpenAI API Key
  - LinkedIn Scraper API Key (via RapidAPI)
  - Job Search API Key (via RapidAPI)
  - Glassdoor Salary API Key (via RapidAPI)

### Installation and Execution

1. Clone the repository:
   ```bash
   git clone https://github.com/Ali75020/AI-Powered-Career-Advisor-LinkedIn-Profile-Analysis-and-Job-Matching.git
   ```
   Or use:
   ```bash
   gh repo clone Ali75020/AI-Powered-Career-Advisor-LinkedIn-Profile-Analysis-and-Job-Matching
   ```

2. Navigate to the project directory:
   ```bash
   cd AI-Powered-Career-Advisor-LinkedIn-Profile-Analysis-and-Job-Matching
   ```

3. Install the required libraries:
   ```bash
   pip install openai requests pandas
   ```

4. Set your API keys as environment variables:
   ```bash
   export OPENAI_API_KEY=<your_openai_api_key>
   export LINKEDIN_API_KEY=<your_linkedin_api_key>
   export JOB_SEARCH_API_KEY=<your_job_search_api_key>
   export SALARY_API_KEY=<your_salary_api_key>
   ```

5. Run the notebook:
   - Open and execute `[Final_Version]_AI_Powered_Career_Advisor.ipynb` using Jupyter Notebook or Google Colab.

---

## Future Enhancements

- Integrate additional salary APIs to improve accuracy and reliability of benchmarks.
- Add a user-friendly web interface for non-technical users.

---

## License

This repository is intended to demonstrate technical proficiency in AI, LLMs, and API integration. It is shared for professional review only and is not intended for replication or commercial use.
