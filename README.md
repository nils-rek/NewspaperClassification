# NewspaperClassification

This project includes a proof-of-concept classification of the two major German newspapers "SZ" and "Welt" based on title data.

It includes three main jupyter notebooks:

1. **ETL**: Title data is scraped from newspaper websites, concatenated, updated with historical data (collected and saved daily using the same procedure), cleaned for duplicates, and loaded onto IBM Watson Studio server.
2. **Feature Engineering**: Includes natural language processing (NLP) functionalities to extract features from title data.
3. **Classification**: Includes machine learning pipeline for newspaper classification.
