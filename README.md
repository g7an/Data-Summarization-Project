# Data-Summarization-Project
This is a data repo. The data is crawled from wikipedia webpages starting from https://en.wikipedia.org/wiki/Category:Animation_by_country

'datasetgood2.csv' is used to make a hierarchical graph (tree graph). It is organized into
the format that could read by javascript, and generate the graph via functions provided 
by d3.js libraries. In all, it has 45,845 entries.

'combined.csv' is a file organizing those data. It gives each node a suquence number, and 
record the pageview of the node. In this way it serves like a catalogue to record information
of each node. It avoids the re-appearance of the nodes (as some nodes appear more than once in 
'datasetgood2.csv').

This is the data used in the visualization part of the project.
