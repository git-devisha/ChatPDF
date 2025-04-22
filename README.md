# ChatPDF

ChatPDF is a Python-based tool that enables users to interact with PDF documents through natural language queries. By leveraging Retrieval-Augmented Generation (RAG) techniques, it facilitates question-and-answer sessions within PDF files.

## Features

- Pose questions directly related to the content of PDF documents.
- Utilizes RAG architecture for accurate and context-aware responses.
- Designed for local execution, ensuring data privacy and control.

## Getting Started

### Prerequisites

- Python 3.10 
- Required Python packages (to be specified in `requirements.txt`)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/git-devisha/ChatPDF.git
   cd ChatPDF
   ```
2. **Create and activate a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables:**

   Create a `.env` file in the project root directory and add necessary environment variables.

   ```bash
   # .env
   # Example:
   # API_KEY=your_api_key_here
   ```
## Usage

To start interacting with your PDF documents:


```bash
python chatpdf.py
```
Follow the on-screen prompts to upload a PDF and begin your Q&A session.

## Project Structure


```plaintext
ChatPDF/
├── .devcontainer/       # Development container configurations
├── chat_pdf.py          # Core script for PDF interaction
├── chatpdf.py           # Alternative or additional script
├── chatpdf.env          # Environment variable definitions
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.
