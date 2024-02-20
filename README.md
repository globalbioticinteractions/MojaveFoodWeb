# MojaveFoodWeb
The files in this repository are paired with the paper _Potential extinction cascades in a desert ecosystem: linking food web interactions to community viability_.

There are several files in this repository. The R Markdown file demonstrates how we performed the secondary network extinction cascade analysis and the subgraph enumeration (where we test the number of motifs in our food web against null graphs). The prey_importance_adjacency.RData file contains our adjacency matrix, which can be loaded directly into R and turned into a network with the iGraph package. We also include two csv files (FoodewbEdgelist and Foodwebnodelist). The edge list is a data frame where each row represents a link between two species (species are in different columns) and the nodelist shows information about every species in the food web. Using both together is an alternate way of constructing a food web. With this method, metadata that would not otherwise appear in the web from the adjacency matrix (such as taxon) will be input into the network.

The other files were used in the analysis process. The vector.RData file has the 6 letter bird species codes that are considered yearlong residents of the Mojave Desert across the majority of the region. The speciesorder.RData file allows us to translate the vector.RData file from species codes to the names of the species themselves. And the vertices1.RData file is similar to the Foodwebnodelist.csv file, but was created earlier in the analysis and is therefore included for the sake of completeness.

## Indexing

This dataset has been configured to be indexed by Global Biotic Interactions (https://globalbioticinteractions.org). 

[![GloBI Review by Elton](../../actions/workflows/review.yml/badge.svg)](../../actions/workflows/review.yml) [![GloBI](https://api.globalbioticinteractions.org/interaction.svg?accordingTo=globi:aeiche01/MojaveFoodWeb&refutes=true&refutes=false)](https://globalbioticinteractions.org/?accordingTo=globi:aeiche01/MojaveFoodWeb)

