# Financial Bot RAG Pipeline

This project aims to enhance a language model's ability to answer financial queries by leveraging context from renowned financial books and implementing advanced techniques.

## Overview

Large language models (LLMs) have shown remarkable capabilities in understanding context and providing relevant responses to prompts. In the financial domain, optimizing context selection can significantly enhance the accuracy and relevance of answers. This project focuses on fine-tuning the "google/gemma-2b-it" model for financial questions.

## Methodology

1. **Data Collection**: Text was extracted from PDF documents of renowned financial books.

2. **Data Processing**: The extracted text was cleaned and organized for analysis.

3. **Text Chunking**: The text was broken down into smaller, more manageable chunks for analysis.

4. **Enhancing Text Analysis**: Techniques like splitting chunks and joining sentences were employed for better insights.

5. **Advanced Retrieval Techniques**: Vector search with dot product similarity was used to identify relevant text chunks.

6. **Hyperparameter Tuning**: Optimization of hyperparameters through grid search enhanced model performance.

7. **Response Generation**: Responses to financial queries were generated using the "google/gemma-2b-it" model and retrieved resources.

## Future Work

1. **Enhanced Context Retrieval**: Implementation of reranking algorithms to further improve context relevance and accuracy.

2. **Exploration of Advanced Models**: Investigation into the use of more advanced language models, such as "google/gemma-7b-it," for better performance.

## Conclusion

Enhancing a language model for financial question answering requires a combination of context enrichment, advanced retrieval techniques, and hyperparameter tuning. By leveraging these strategies, we have developed a powerful tool for extracting insights and answering queries in the financial domain.

---
Mediume [https://medium.com/@mrunal.mania97/context-aware-rag-pipeline-fine-tuned-on-google-gemma-2b-it-for-financial-questions-622d5d0768d0]
