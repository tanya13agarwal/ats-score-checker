# Free ATS Score Checker

## Overview

Welcome to the Free ATS Score Checker, a tool designed to evaluate your resume against a job description and provide an ATS (Applicant Tracking System) score. This application aims to assist job seekers in enhancing their chances of getting shortlisted in the competitive job market.

## Features

- **ATS Evaluation:** Evaluate your resume against a provided job description.
- **Guidance Points:** Check your resume against 16 crucial points for ATS optimization.
- **Gemini AI Integration:** Leverage Google Gemini AI for content generation and analysis.

## Installation

To use this tool, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/tanya13agarwal/ats-score-checker.git
   cd ats-score-checker
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Configure environment variables:

   Create a `.env` file and add your Google Gemini API key:

   ```env
   GOOGLE_GEMINI_KEY=your_api_key
   ```

## Usage

Run the Streamlit app:

```bash
streamlit run ats_score_checker.py
```

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your purposes.
