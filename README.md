# Resume Optimizer

This project is a web application designed to help job seekers optimize their resumes to increase their Applicant Tracking System (ATS) scores. By automatically extracting keywords from job descriptions, the app intelligently enhances the uploaded resume to ensure maximum relevance and compatibility with ATS filters.

## Features

- **Keyword Extraction:** Automatically identifies all relevant keywords from any pasted job description.
- **Resume Optimization:** Injects missing keywords into your resume using AI-powered rewriting to improve ATS compatibility.
- **ATS Score Estimation:** Provides a score estimating how well your resume matches the job description.
- **Side-by-Side Comparison:** View your original resume alongside the optimized version to see improvements clearly.
- **File Upload & Download:** Supports DOCX and PDF uploads, and allows downloading the optimized resume in both formats.
- **Secure API Key Management:** Uses `.streamlit/secrets.toml` to securely manage API keys (not committed to the repo).

## Tech Stack

- Python & Streamlit for frontend interface  
- OpenAI API for natural language processing and resume rewriting  
- `python-docx` and `PyPDF2` for document processing  
- SpaCy for keyword extraction and text processing

## Getting Started

1. Clone the repository  
2. Create and activate a Python virtual environment  
3. Install dependencies:  
   ```bash
   pip install -r requirements.txt
