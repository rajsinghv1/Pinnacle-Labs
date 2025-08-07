# 📝 Resume Parser AI  
**Internship Project @ Pinnacle Labs Pvt Ltd**

This project is a Python-based Resume Parser designed to automatically extract key information from resumes in PDF or DOCX formats using **Natural Language Processing** techniques. Built during my internship at **Pinnacle Labs**, it demonstrates practical application of **NLP**, **regex**, and **document parsing**, with a modular design for easy customization and extension.

---

## 🚀 Features

- ✅ Extracts **Name**, **Email**, and **Phone Number**
- ✅ Identifies **Skills** from a predefined database
- ✅ Detects **Education** and **Experience** sections
- ✅ Supports `.pdf` and `.docx` resume formats
- ✅ CLI-driven interface for quick usage
- ✅ Modular, beginner-friendly **Python** code

---

## 🧰 Tech Stack

| Tool           | Purpose                                      |
|----------------|----------------------------------------------|
| `pdfplumber`   | Extracts text from PDF files                 |
| `python-docx`  | Reads content from DOCX documents            |
| `spaCy`        | NLP processing (tokenization, POS, NER)      |
| `regex (re)`   | Pattern matching for emails and phone numbers|
| `pathlib`      | Validates file paths and extensions          |

---

## 📦 Installation

Install required libraries before running the script:

```bash
pip install pdfplumber python-docx spacy
python -m spacy download en_core_web_sm
