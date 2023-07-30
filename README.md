# Multi-files Chat App
This application provides a chat-like interface to extract and communicate information from multiple uploaded PDF files. The app uses **Streamlit** for the web interface, **PyPDF2** for PDF processing, **FAISS** for information retrieval, and **langchain** with **OpenAI** models for language understanding and generation.

## Features
**1- Upload Multiple PDFs:** You can upload multiple PDFs to the application.

**2- Chat Interface:** Ask questions related to the contents of the PDFs in a chat-like interface.

**3- Powered by AI:** The application uses OpenAI models to understand the text and generate responses.

## Installation
First, clone this repository:

```bash
git clone https://github.com/ktchandama/multi_files_chat_app.git
cd multi_files_chat_app
```

Then, install the required dependencies:

```bash
pip install -r requirements.txt
```

You'll need Python 3.6 or later to run the app.

## Usage
Start the application by running:

```bash
streamlit run app.py
```

Navigate to the URL printed in the console (usually http://localhost:8501), and you'll see the application interface. Upload your PDF files in the sidebar and click on "Process". Then, ask questions about your documents in the provided text input field.

## Technologies Used
- **Streamlit:** An open-source Python library used to make custom web apps for machine learning and data science.
- **langchain:** An NLP library that provides text processing and retrieval utilities.
- **OpenAI:** A set of AI models used for understanding and generating natural language.
- **FAISS:** A library for efficient similarity search and clustering of dense vectors, developed by Facebook AI Research (FAIR).

## Contributing
Contributions, issues, and feature requests are welcome.

License
This project is licensed under the terms of the MIT license.
