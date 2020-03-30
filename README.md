## Problem Description

The goal of this project was to predict missing links in a citation network of research articles. A citation network
is represented as a graph G = (V,E), where the nodes correspond to scientific articles and the existence
of a directed edge between nodes u and v, indicates that paper u cites paper v. Each node (i.e., article) is also
associated with information such as the title of the paper, publication year, author names and a short abstract.
A number of edges have been randomly removed from the original citation network.  

The goal was to accurately reconstruct the initial network using graph-theoretical and textual features, and
possibly other information.The target was to aim for the maximum F1 score.

## Dataset Description 

DATASET DESCRIPTION
The data provided includes three datasets: a train set, a
test set and an article information set. The train has three
columns, two for nodes 𝑢 and 𝑣 and one that represents
whether 𝑢 cites 𝑣. The article information dataset provides
textual information such as: title of the paper, publication
year, author names and an abstract, for each of the papers.
Overall there are 27,770 unique papers. The train set provides
information, i.e. whether nodes are connected, regarding
615,512 node pairs and the test set is composed of 32,648
node pairs.

## Pipeline

1. Data understanding 
2. Feature Engineering  
3. Predictive modelling  

The following models were compared:  
A. XGBoost (Random search for hyperparameter tuning)  
B. AdaBoost 
C. Random Forest  
D. Support Vector Classifier

## Results

![alt text](https://github.com/rvs36/Network_Science_Anlaytics/blob/master/Results.JPG)
