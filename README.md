# Compressed Search Engine and Vector-Space Model  

## Description  
This project implements a compressed search engine and vector-space model for efficient document storage and retrieval. Key features include:  

- **Dictionary and Postings Compression:**  
  - Front-coding to reduce dictionary size.  
  - Gamma encoding to compress postings lists.  
- **Boolean Query Processing:** Supports AND, OR, and NOT operations on the compressed data.  
- **Vector-Space Model:**  
  - Calculates document rankings using TF-IDF weights and cosine similarity.  
  - Retrieval with and without normalization, including visualization of document-query relationships.  
- **Term-at-a-Time Processing:**  
  - Relevance scores calculated for queries using pivot normalization.  
  - Efficient retrieval of top documents using a min-heap.  

## Features  
1. **Dictionary Compression:**  
   - Implements front-coding to store shared prefixes efficiently.  
2. **Postings Compression:**  
   - Uses delta and gamma encoding for compact representation of document IDs.  
3. **Vector-Space Model:**  
   - Computes TF-IDF weights and retrieves documents based on cosine similarity.  
   - Visualization of document-query relationships in 2D space.  
4. **Term-at-a-Time Processing:**  
   - Processes each query term individually with pivot normalization.  
   - Retrieves top-k documents using a min-heap for efficient ranking.  

