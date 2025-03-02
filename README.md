# Multi Language Invoice Extractor

## Overview
The **Gemini Invoice Extractor** is a Streamlit-based web application that utilizes **Google's Gemini AI** to extract and interpret data from invoices. Users can upload an image of an invoice and ask questions about the contents, receiving AI-generated responses based on the image.

## Features
- Upload an invoice image (JPG, JPEG, PNG)
- Extract information using **Google Gemini AI**
- Ask questions related to the uploaded invoice
- Display AI-generated responses in real-time

## Requirements
Ensure you have the following dependencies installed:

```bash
pip install streamlit google-generativeai pillow python-dotenv
```

## Setup
### 1. Clone the Repository (Optional)
If you're using Git:
```bash
git clone https://github.com/kushagra2503/Multi-Language-Invoice-Extractor.git
cd gemini-invoice-extractor
```

### 2. Set Up the API Key
- Create a `.env` file in the root directory
- Add your Google API Key:

```
GOOGLE_API_KEY=your_api_key_here
```

### 3. Run the Application
Start the Streamlit app with:
```bash
streamlit run app.py
```

## Usage
1. Open the **Gemini Invoice Extractor** in your browser.
2. Upload an invoice image (**JPG, JPEG, PNG**).
3. Enter a question related to the invoice (e.g., "What is the total amount?").
4. Click the **'Tell me about image'** button.
5. View the AI-generated response in real-time.

## Code Structure
- **`app.py`** - Main Streamlit application.
- **`.env`** - Stores API key (not included in the repository for security).
- **`requirements.txt`** (optional) - Lists dependencies for easy installation.

## Troubleshooting
- **API Key Error**: Ensure you have a valid **Google API Key** and it is correctly placed in the `.env` file.
- **File Upload Issue**: Only JPG, JPEG, and PNG formats are supported.
- **Slow Response**: May be due to API rate limits or network issues.

## Future Enhancements
- Add support for PDF invoices.
- Improve OCR accuracy for better text extraction.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contact
For questions or suggestions, reach out to:
📧 Email: radhikayash2@gmail.com   

