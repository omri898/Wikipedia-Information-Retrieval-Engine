# Wikipedia Information Retrieval Engine

This repository contains the code and documentation for a custom-built information retrieval engine designed to query and retrieve relevant Wikipedia pages from local data. Built using Python, this engine leverages information retrieval techniques, and integration with Google Cloud Platform for efficient data handling and indexing.
<p align="center">
<img src="/Logo.webp" width="400" height="400">
</p>

## Project Structure

- `Backend.py`: Core backend logic for the search engine, including query processing and result ranking algorithms.
- `inverted_index_gcp.py`: Scripts to handle the inverted index storage and retrieval from Google Cloud Platform services.
- `search_frontend.py`: The frontend interface for interacting with the search engine via the command line or potentially a web interface.
- `text_tf_index_pipeline_gcp.ipynb`: Jupyter notebook detailing the pipeline for creating and storing text term-frequency indices in GCP.
- `title_tf_index_pipeline_gcp.ipynb`: Jupyter notebook detailing the pipeline for creating and storing title term-frequency indices in GCP.
- `queries_train.json`: Sample query dataset used for training the search engine's effectiveness.
- `docid_len_dict.pkl`: Pickle file containing the document ID to document length mappings.
- `docid_title_dict.pkl`: Pickle file containing the document ID to title mappings, used for displaying search results with readable titles.

## Creators
Created by Omri Haller and Anton Dzega
