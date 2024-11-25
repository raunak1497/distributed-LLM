# distributed-LLM
**Building a Large Language Model (LLM) using Distributed Systems**

## Project Overview
The project is divided into three stages.

### 1. The first stage uses a dataset of **10,000 IMDB reviews**, split into five text shards for optimal performance, though tests with 3, 7, and 10 shards were also conducted.  

## MapReduce Pipeline

The pipeline is implemented with three **MapReduce jobs**, each addressing a specific task:
### a) Tokenization  
### b) Word2Vec Embedding Generation  
### c) Cosine Similarity Calculation  

This implementation processes text data to efficiently analyze and classify word semantics.
### 2. This step leverages Apache Spark to create and train the large language model (LLM) on distributed cloud infrastructure. Utilizing Word2Vec embeddings from previous stage, we aim to predict the next word embedding in a sequence through a neural network trained with sliding window sequences.
### 3.