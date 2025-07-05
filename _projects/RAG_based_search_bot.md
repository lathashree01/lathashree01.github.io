---
layout: page
title: Research papers search agent
description: RAG based application to search for research papers and summarise them.
img: assets/img/projects/search_bot.jpg
importance: 1
category: nlp
related_publications: true
---

## Project description

A simple RAG based application that loads research papers from a csv file and allows users to search for papers based on their queries. The application uses a vector database to store the embeddings of the papers and provides a search interface for users to find relevant papers.

## Current State

- Link to the [Research papers search agent - GitHub repository](https://github.com/lathashree01/research_papers_search_bot)
- The application is built using Python and uses the `langchain` library for RAG.
- It uses FAISS vector database to store the embeddings of the papers.
- Loads papers from a CSV file and creates embeddings using Sentence Transformers model `all-MiniLM-L6-v2`.
- Provides a simple search streamlit interface to find papers based on user queries.
- Currently, it does not support dynamic loading of papers from external sources like ArXiv or other APIs, uses a static CSV file for demonstration purposes.

## How to Run

1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the application using `streamlit run app.py`.
4. Open the application in your browser at `http://localhost:8501`.

## Future Improvements

- Add dynamic loading of papers from ArXiv API or other sources.
