# PDF OCR Converter

A Python script that batch processes PDF files using OCRmyPDF to make them searchable through Optical Character Recognition (OCR).

## Description

This script automates the process of converting non-searchable PDF documents into searchable ones using OCR technology. It processes all PDF files in a specified input directory and saves the OCR-processed versions to an output directory.

## Prerequisites

- Python 3.x
- OCRmyPDF (must be installed and accessible from command line)

### Installation

1. Install OCRmyPDF:
   ```bash
   # For Ubuntu/Debian
   apt-get install ocrmypdf

   # For macOS
   brew install ocrmypdf

   # For Windows
   pip install ocrmypdf
   ```

2. Clone this repository or download the script.

## Configuration

Modify the following variables in the script to match your environment:

```python
input_folder = "C:\\root\\archive\\ocr_pend"  # Folder containing original PDFs
output_folder = "C:\\root\\archive"           # Folder for processed PDFs
```

## Usage

1. Place your PDF files in the input folder
2. Run the script:
   ```bash
   python pdf_to_ocr.py
   ```

The script will:
- Process all PDF files in the input folder
- Apply OCR to make them searchable
- Save the processed files to the output folder
- Print progress messages for each file

## Features

- Batch processing of multiple PDF files
- Automatic creation of output directory if it doesn't exist
- Error handling and progress reporting
- Maintains original file names

## Error Handling

The script includes basic error handling that will:
- Print success messages for each successfully processed file
- Print error messages if processing fails for any file
- Continue processing remaining files even if one fails

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Uses [OCRmyPDF](https://github.com/jbarlow83/OCRmyPDF) for PDF processing


---

<p align="center">
  <img src="https://media.giphy.com/media/xT9IgzoKnwFNmISR8I/giphy.gif" alt="Code is Life" width="120">
</p>

<p align="center">
  <b>⌨️ with 💻 by Raj Reddy</b><br>
  <code>// Reach out if you find bugs in the matrix</code><br>
  <a href="https://github.com/neuralnet19" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-000000?style=flat-square&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="mailto:neuralnet19@hotmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

<p align="center">
  <code>// "Hello, World!" is just the beginning 🚀</code>
</p>

---
