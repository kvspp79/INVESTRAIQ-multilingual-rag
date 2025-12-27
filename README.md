# INVESTRAIQ – Multilingual RAG-based Startup Funding Intelligence System

INVESTRAIQ is a trust-first Generative AI system designed to help Indian startup founders and investors access accurate startup funding insights in Indic languages. The system uses Retrieval-Augmented Generation (RAG) to ensure that all responses are grounded in verified data and include clear source citations.

## Problem Statement
Startup funding information in India is fragmented across reports, PDFs, portals, and policy documents, and is predominantly available in English. This limits access for founders who prefer Indic languages, leading to uninformed funding decisions. INVESTRAIQ addresses this challenge by providing multilingual, explainable, and source-grounded funding intelligence.

## Objective
To build a multilingual RAG-based startup funding intelligence system that retrieves, reasons over, and explains real startup funding data in Indic languages.

## Key Features
- Multilingual query support (Indic languages)
- RAG-based retrieval to minimize hallucinations
- Explainable investor recommendations
- Source citation and provenance tracking
- Supports structured and unstructured data ingestion

## System Architecture
1. Data ingestion from CSV, PDF, and reports
2. Text cleaning and chunking
3. Embedding generation using language models
4. Vector database using FAISS
5. Retrieval-Augmented Generation pipeline
6. Multilingual input/output handling
7. Source-grounded response generation

## Tech Stack
- Python
- LangChain
- FAISS
- OpenAI / Gemini
- Streamlit
- Multilingual embeddings / translation pipeline

## Usage Example
Users can ask questions like:
"Suggest seed-stage investors for an AI healthcare startup in India"

The system returns investor recommendations along with explanations and data sources.

## Future Scope
- Real-time funding data integration
- Policy-aware funding recommendations
- Advanced investor-startup matching algorithms

