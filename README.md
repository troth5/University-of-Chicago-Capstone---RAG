# University-of-Chicago-Capstone---RAG

### Overview
##### This project serves as my capstone for graduation at The University of Chicago. Here we create and assess a RAG QA architecture on news articles scraped dating back to 2021. 


### The Data
#####The entire corpus of articles is more than 2 million, however for testing purposes we limited the number of articles to roughly 200. These articles are scraped from news websites in India, USA, and other languages to assess the generalizability of this framework. For each article scraped associated metadata includes the article: text, author, date, url, etc. This data is contained within the Cleaned Data folder. 

### Notebooks (Code)
##### Build_VS.ipynb - In this notebook we demonstrate how to create the RAG architecture with llamaindex. This was ran locally on a mac by using a docker image of Qdrant as a vector store, Ollama to connect to the LLM's, and a voyage api as an embedding model. 
##### RAG_Evaluation.ipynb - In this notebook we evaluate the performance of RAG using Faithfulness (Hallucination rate) and Relevancy. We tested these metrics across various LLM's including Mistral, Llama, and Dolphin-Phi.

