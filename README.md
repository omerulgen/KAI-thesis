#README KAI-Thesis 
This repository contains all necessary resources for the replication of the research conducted in the thesis - "Harnessing Large Language Models for Automatic Ontology Generation: A Novel Approach". The thesis explores the application of Latent Dirichlet Allocation (LDA) and OpenAI's Large Language Models (LLMs) in the field of automated ontology engineering.

The key files in this repository are as follows:

BOW.owl and TF-IDF.owl: These are the output ontology files generated from the Bag of Words (BOW) and Term Frequency-Inverse Document Frequency (TF-IDF) automated methods, respectively.

data_expanded.csv: This is the data file, consisting of data gathered from clinical trials via the NIH website. This file serves as the primary data source for the ontology generation process.

golden_ontology.owx: This file is the "golden standard" ontology, manually engineered at the commencement of this thesis. It provides a benchmark for comparison of the ontologies generated through automated methods.

thesis_paper.pdf: This is the comprehensive thesis report detailing the objectives, methodology, experiments, and results of the research.

thesis_code_omer_ulgen.ipynb: This Jupyter notebook contains all the code used in the thesis. In order to rerun this code, users must modify the local file paths according to their system's directory structure and acquire a working API key for OpenAI's GPT-3 model.

Please note: To use OpenAI's API, ensure that you abide by their usage policy and you have an appropriate key. Without the correct setup, the code in the notebook may not execute as expected.

If you have any questions or need further clarification, feel free to raise an issue in this repository.
