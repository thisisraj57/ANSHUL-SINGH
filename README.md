Medical Research GenAI Processor
A powerful AI-driven application that processes, analyzes, and summarizes complex medical research papers, extracting essential information on drugs, genes, proteins, and medical efficacy/safety metrics. The application is built with Streamlit and leverages Google’s Generative AI model to empower medical research.

Features
Data Preprocessing: Secure data ingestion and preprocessing to tokenize, clean, and standardize medical research text.
Generative AI Query Processing: Answers user queries based on processed medical documents.
Entity Extraction: Extracts key medical entities such as drugs, genes, and proteins, using regular expressions.
Privacy Guardrails: Redacts patient identifiers and dates to ensure compliance with privacy standards.
Evaluation Metrics: Calculates Entity Linking Accuracy, Summary Coherence, and Readability Score for assessing query results.
Data Export: Provides functionality to download session data for offline access.
Getting Started
Prerequisites
Python 3.8 or higher
Streamlit
LangChain
Google Generative AI
NLTK for tokenization and BLEU score calculation
Plotly for visualizing extracted entity counts
