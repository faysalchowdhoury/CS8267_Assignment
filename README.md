# CS8267_Assignment1
### Assignment 1: Unsupervised Learning: K-Means Clustering Use Case: Identifying topics from articles on the same topic
Student Name: Faysal Chowdhoury
Date: 18 th September 2023

## install packages

## Step 1 Kmtest on CSV file
K means Test on CSV file both random and seeding

## Step 2 K-Means Clustering to Identifying topics from articles on the same topic 

-> Import token from hugging face
-> Import Hugging Face
-> Load Document from web
-> Load LLM from hugging face and load "bigscience/bloomz-7b1"
-> Split text
-> Store in vectorestore
-> Apply PCA on embeddings
-> Apply Kmeans on PCA
-> load closest embeddings to K means Cluster Center
-> load Document Text of closest embeddings
-> Paraphrase text.[12 types below]

* PCA 3 K means 3
* PCA 7 K means 3
* PCA 19 K means 3
* PCA for 0.9 PoV K means 3
* PCA 3 K means 5
* PCA 7 K means 5
* PCA 19 K means 5
* PCA for 0.9 PoV K means 5
* PCA 3 K means 10
* PCA 7 K means 10
* PCA 19 K means 10
* PCA for 0.9 PoV K means 10

****    1. Befor runinning this code, Please install all packages.(if packages are not installed in your system)
        2. Create account on Hugging Face and create "HuggingFace testtoken (write)" from settings. 
        3. If get RuntimeError in "#Loading a LLM from hugging face, see model_id as a reference", PLEASE RESTAT YOUR SYSTEM.              (error occurs due to insufficient memory. RESTART your system create memory to run the "bigscience/bloomz-7b1"                  without any RuntimeError)
        4. Please run whole notbook eachtime and don't run single cells except package installation.
        5. To save runtime you may comment "Sample query" cells and reduce Article from 10 to 5. 
