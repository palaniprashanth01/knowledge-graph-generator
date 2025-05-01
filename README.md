# Knowledge Graph Generator from PDFs

This project extracts entities and relationships from PDF documents and builds a visual **Knowledge Graph**. It also supports **question generation** using Bloom’s Taxonomy and optional translation of content.

## ✨ Features

- 📄 Extracts text from PDF files
- 🧠 Identifies entities using spaCy and links them to Wikipedia
- 🔗 Extracts relationships using dependency parsing and rules
- 🌐 Constructs a Knowledge Graph using NetworkX and matplotlib
- ❓ Generates WH-questions based on Bloom’s Taxonomy
- 🌍 Optional translation of content to multiple languages
- 🧪 Provides a Gradio interface for user interaction

## 🔧 Technologies Used

- Python 3.10+
- `PyMuPDF (fitz)` for PDF parsing
- `spaCy` for NLP and entity recognition
- `wikipedia-api` for entity linking
- `NetworkX` and `matplotlib` for graph construction
- `deep_translator` for multilingual support
- `Gradio` for user interface

## 🚀 Installation

```bash
git clone https://github.com/palaniprashanth01/knowledge-graph-generator.git
cd knowledge-graph-generator
pip install -r requirements.txt
