# Distributed-Systems-Project---Elasticsearch

The aim of this project was to demonstrate undeerstanding of elasticsearch technology.
Elasticsearch is an open source search and analytics engine.
A Distributed architecture that makes use of concepts such as replication, coordination, naming and concurrency

We built a Fuzzy search enginewith elasticsearch in python

Three elasticsearch hosts were setup and deployed on unbuntu virtual machines in Virtual box

The three nodes were connected together and one of which was the master node on windows PC
The data was loaded from the IMDb Movie Review dataset in kaggle
It constitued 1 010 293 reviews (1.1GB)


Cluster: A cluster is a collection of one or more
nodes that together holds your entire data.
● Node: Single server as part of the overall
cluster. Its main role is to store data and
participate in clusters indexing and search
capabilities
● Shards: Divides an index into smaller part and
distribute across multiple nodes (primary and
replica)
● Index: Collection of document (key-value pair
attributes)
● Document: JSON object constitution specific
data belonging to an index
