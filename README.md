# Government Document Processor

A Streamlit application that processes government documents using AI and OCR technology.

## Features

- **Document Upload**: Support for PDF, PNG, JPG, JPEG files
- **OCR Processing**: Text extraction from scanned documents using EasyOCR
- **AI Analysis**: Structured data extraction using Google Gemini API
- **Multiple Document Types**: Aadhaar Card, PAN Card, Passport, Driving License, Marksheets, Invoices, Contracts, and more

## Setup

1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Create a `.env` file with your Gemini API key:
   ```
   GEMINI_API_KEY=your_api_key_here
   ```
4. Run the app: `streamlit run app1.py`

## Deployment

This app is configured for deployment on Streamlit Cloud. Simply connect your GitHub repository to Streamlit Cloud for automatic deployment.

## Environment Variables

- `GEMINI_API_KEY`: Your Google Gemini API key (required for AI features)
