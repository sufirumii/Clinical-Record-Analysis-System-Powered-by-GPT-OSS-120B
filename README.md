# Clinical Record Analysis System
Powered by GPT-OSS-120B

A browser-based tool that extracts text from medical PDFs to generate structured clinical summaries and visual health data.

# Clinical Record Analysis System
This project provides a professional interface for interpreting unstructured medical documents. It uses browser-side PDF parsing and high-parameter language models to transform dense clinical text into organized reports and visual dashboards.

# Overview
The system allows users to upload patient records in PDF format and receive an immediate synthesis of the document contents. It identifies key diagnostic markers, explains specialized terminology, and maps potential data points across a ten-point visualization grid.

# Core Features
Local PDF Processing: Uses PDF.js to extract text directly in the browser for analysis.

Intelligent Summarization: Leverages the GPT-OSS-120B model to interpret medical nomenclature and clinical observations.

Interactive Analytics: Generates ten distinct charts using Chart.js to represent data such as recovery indices and risk profiles.

Automated Glossary: Scans the document for complex medical terms and provides real-time definitions.

# Technical Requirements
To run this project, you will need a valid Hugging Face API token to access the inference endpoints.

Important: You must add your own Hugging Face token to the KEY variable in the code to enable the analysis features.

# Installation and Use
Clone this repository or download the HTML file.

Open the file in a code editor.

Locate the const KEY = "..." line in the script section.

Replace the existing string with your personal Hugging Face API token.

Save and open the file in any modern web browser.

Upload a clinical PDF to begin the analysis.
