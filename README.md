# Multilingual PDF Document Interpreter

## Overview
This project leverages advanced AI to enhance the accessibility of information within PDF documents by enabling multilingual interpretation. It is built using the CrewAI framework, integrating specialized AI agents to process, summarize, and translate content from PDF documents into multiple languages.

## Project Description
The Multilingual PDF Document Interpreter is designed to process any PDF document and make its content accessible in several languages. This capability is crucial for educational, professional, and personal purposes where users need to access information in their native languages.

## How It Works
- **PDF Processing**: Initially, the system uses a PDFSearchTool to load and parse content from a specified PDF file.
- **Content Interpretation and Summarization**: An AI-powered agent processes the extracted content to identify key information and generate concise summaries.
- **Multilingual Translation**: Another AI agent translates the summarized content into the user's preferred language, maintaining the accuracy and context of the original information.

## Usefulness
- **Accessibility**: Makes content available in multiple languages, broadening access for non-native speakers.
- **Efficiency**: Quickly processes and summarizes complex documents, saving time and effort for users.
- **Accuracy**: Ensures that translations maintain the integrity of the original content, providing reliable information.

## Setup
1. Ensure the `.env` file is correctly configured with the necessary API keys.
2. Place the target PDF file in an accessible directory.
3. Run the script to start processing the PDF and receive outputs in the desired language.

## System Requirements
- Python 3.x
- Dependencies: `crewai`, `pandas`, `sklearn`, `dotenv`

## Conclusion
The Multilingual PDF Document Interpreter stands as a vital tool in breaking down language barriers, offering precise and accessible translations of complex PDF documents, thereby facilitating better understanding and utilization of global information resources.
