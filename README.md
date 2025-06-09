Note: 
    UV was used to manage the env.

# Coding Assignment

 From HR

Dataset: IEDGAR SEC filings (public data) -

https://huggingface.co/datasets/eloukas/edgar-corpus

Language: Python

Implementation: Pyspark

Submission: Github repository containing code + plots (jpeg).

Expected Maximum Duration: 3 hours

 

Task #1 - Engineering

Given a set of documents: create a solution that allows the end user to understand

the documents in a two dimensional space and to identify outliers.

Dataset

( Year: 2020

( Filing type: 10K

( Sections: All

( Companies: Limit to 10.

Steps

( Convert the documents to chunks,

( Convert the chunks into embeddings,

( Standard scale the embeddings,

( Perform principal components analysis,

( Apply dimensionality reduction,

( Perform Kmeans clustering and assign chunks an cluster number.

( Create an outlier flag.

( Plot(s)

○ Embeddings in 2 dimensions

○ Colored by assigned clusters.

○ Colored by outlier flag

○ Colored by section number.

 

Task #2 – Gen AI

Dataset

( Year: 2018-2020

( Filing type: 10K

( Sections: All

( Company: Choose 1.

( Choose 5 data attributes to extract from a single year.

Steps

( Convert documents to chunks

( Covert chunks to embeddings

( Create a query

( Create a prompt to extract data from chunks from a specific year.

( Create a validation dataset (5 true values from chunks).

( Demonstrate that your LLM can retrieve the correct chunks from your

embedding object for the correct year