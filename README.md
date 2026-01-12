# Word2Vec-Visualiser

# Word2Vec Embedding Visualiser

This project was developed during my AI/ML Research Internship at Carnegie Mellon University (USA).  
It focuses on visualizing and analyzing Word2Vec word embeddings to understand how natural language models learn semantic relationships between words.

The goal is to make NLP representations more interpretable by projecting high-dimensional word vectors into visual space.

---

## What this project does

This system:
- Trains or loads a Word2Vec model
- Extracts vector representations of words
- Computes semantic similarity between words
- Projects embeddings into 2D/3D space
- Visualizes clusters and relationships between words

It helps answer questions such as:
- Which words are semantically close?
- How does the model group similar meanings?
- How does training data affect word relationships?

---

## Why this matters

Word embeddings are the foundation of modern NLP systems including:
- Chatbots
- Search engines
- Recommendation systems
- Large language models

This project makes those embeddings:
- Visual
- Interpretable
- Debuggable

It is particularly useful for:
- NLP research
- Model debugging
- Education and demonstration
- Understanding bias and relationships in language data

---

## Core AI concepts used

- Word2Vec
- Vector embeddings
- Cosine similarity
- Dimensionality reduction
- Semantic clustering
- Natural Language Processing (NLP)

---

## Tech stack

- Python  
- Gensim  
- NumPy  
- Matplotlib / Plotly  
- Scikit-learn  

---

## How to run

Install dependencies:

```bash
pip install gensim numpy matplotlib scikit-learn
Run the visualiser:

bash
Copy code
python main.py
This will generate interactive or static plots showing word relationships.

Research context
This project was completed as part of my AI/ML Research Internship at Carnegie Mellon University, where I worked on making machine learning models more explainable and interpretable, especially in natural language processing.

Example use cases
Visualizing how Word2Vec understands “king – man + woman = queen”

Studying semantic bias in embeddings

Comparing embeddings trained on different datasets
