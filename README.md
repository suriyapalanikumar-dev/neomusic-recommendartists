# NeoMusic : Find similar artists.

The goal of NeoMusic project is to find top k-similar artists without usage data addressing the cold-start issue as well.

Dataset stats:

1) 24270 records of Artists
2) 56 different types of embedding vectors for the following features.
    1) Music Genre(32 vectors)
    2) Country(20 vectors)
    3) Music Mood(4 vectors)
    
input/:

Input directory consists of the deezer_features .csv file

output/:

Output directory consists of the top 30 similar artists for some of the cold-artists.

NeoMusic.ipynb:

Python scripts to find the similarity using the following technique:

1) Clustering Algorithm
2) Asymmetric distance metric : Hausdorff.
3) Graph Mining using Neo4j cypher query scripts

As Neo4j DB and Cypher query files are huge in size, please find the same in the following shared drive:

https://drive.google.com/drive/u/5/folders/0AIuN7KReXPvAUk9PVA



