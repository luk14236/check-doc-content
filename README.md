# check-doc-content.py

This Python script checks the content of documents for specific patterns such as CPF, CNH, CNPJ, PIS, TituloEleitoral, CEP, and cellphone numbers.

## Usage

1. **Install Dependencies:**
   - Install the required libraries and packages by running the provided command.

2. **Run the Script:**
   - Call the `verificar_diretorio` function to check the content of files in the current directory.
   - The script checks each document for patterns such as CPF, CNH, CNPJ, PIS, TituloEleitoral, CEP, and cellphone numbers.
   - It prints the detected patterns for each document.

## Requirements

- Python 3.x
- Libraries:
  - validate-docbr
  - pycep-correios
  - phonenumbers
  - textract
  - docx2txt

## Overview

This script checks the content of documents (TXT, DOCX, PDF) for specific patterns using various Python libraries and packages.

## Supported Patterns

- **CPF**: Brazilian Individual Taxpayer Registry
- **CNH**: Brazilian Driver's License
- **CNPJ**: Brazilian National Registry of Legal Entities
- **PIS**: Brazilian Social Integration Program
- **TituloEleitoral**: Brazilian Voter ID Card
- **CEP**: Brazilian ZIP Code
- **Cellphone Numbers**: Brazilian cellphone numbers

## How it Works

- The script defines several functions to validate different types of documents and patterns.
- It reads the content of each document and splits it into lines.
- For each line, it splits the words and checks each word for the supported patterns.
- If a pattern is detected, it prints a message indicating the detected pattern.
