# LLM-Demos-and-Experiments

A collection of Jupyter notebooks demonstrating NLP tasks with Large Language Models (LLMs), covering everything from sentiment analysis to retrieval-augmented generation (RAG) pipelines using **Hugging Face**, **LlamaIndex**, and **OpenAI**.

---

## Table of Contents

1. [Overview](#overview)
2. [Setup](#setup)
3. [Notebooks](#notebooks)
4. [Usage](#usage)
5. [References](#references)

---

## Overview

- **Sentiment Analysis**: Classify text polarity using Hugging Face pipelines.  
- **Named Entity Recognition**: Identify named entities in text.  
- **Text Summarization**: Generate concise summaries of longer texts.  
- **Translation**: Translate text between languages.  
- **RAG System**: Build a retrieval-augmented generation pipeline with LlamaIndex.  
- **Local LLM Querying**: Use a locally hosted Hugging Face model to query indexed documents.  
- **OpenAI Integration**: Swap in GPT models from OpenAI for query responses.

This repository demonstrates how to leverage modern NLP libraries and frameworks to build end-to-end solutions.

---

## Setup

**Clone the repository**:
   ```bash
   git clone https://github.com/shraddhapiparia/LLM-Demos-and-Experiments.git
   cd LLM-Demos-and-Experiments 
   ```

---

## Notebooks

1_Sentiment_Analysis.ipynb	Demonstration of text classification using Hugging Face pipelines.
2_NER.ipynb	Named Entity Recognition.
3_Summarization.ipynb	Summarizing long passages of text.
4_Translation.ipynb	Translating text (English to French or Chinese) with transformers.
5_Basic_RAG_with_LlamaIndex.ipynb	Setting up a simple RAG system with LlamaIndex.
6_Querying_Index_HFLLM.ipynb	Querying the index with a locally hosted HuggingFace LLM.
7_Querying_Index_OpenAI.ipynb	Replacing the local LLM with OpenAI's GPT for queries.

## Usage

Data Preparation:
Place your PDF or text documents inside the contents/ folder for indexing.

Running the Notebooks:

Open the Jupyter notebook in your browser.
Run each cell step by step.
Modify the code or data paths according to your setup.
Customization:

Feel free to swap out models in transformers (e.g., distilbert-base-uncased for sentiment analysis).
Adjust LlamaIndex parameters (e.g., chunk sizes, retrieval strategies) as needed.


## References

https://github.com/huggingface/transformers
https://github.com/run-llama/llama_index
https://platform.openai.com/docs/concepts
