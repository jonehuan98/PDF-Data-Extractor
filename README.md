# PDF Text Extractor and Query Tool

This repository contains a Python script for extracting text from PDF documents and performing text queries on the extracted content. The tool uses a combination of OCR (Optical Character Recognition) and NLP (Natural Language Processing) techniques to analyze documents and retrieve relevant information based on user-defined queries.

## Features

- **PDF Text Extraction**: Utilizes `langchain` and `pytesseract` for accurate OCR processing.
- **Text Query**: Leverages `VectorstoreIndexCreator` from `langchain` to create searchable indexes of the extracted text.
- **Modular Design**: Script functions are designed to be reusable and easily extendable.
- **Detectron2 Integration**: Configured to use Detectron2 for advanced layout analysis, with support for both CPU and GPU processing.

