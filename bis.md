---
title: Another page
description: lambda
---

Objective bis
---------

1.  Study querying operations on graphs 
2.  Compare the data science and data mining perspective versus declarative querying on Graph Stores and ML studios (pipelines)

Infrastructure
--------------

-   [Kaggle](http://www.kaggle.com/) (create an account)
-   [AI Azure Gallery](https://studio.azureml.net/)
-   [Docker](https://www.docker.com/) container with [Neo4J](https://neo4j.com/docs/graph-algorithms/current/introduction/): available [here](https://drive.google.com/drive/folders/19tH6L7Ta3RNXJ5aJEtsv7g0q_W8WW--P?usp=sharing)

Preparing your infrastructure
-----------------------------

-   Download docker desktop and install it on your machine: [here](https://www.docker.com/products/docker-desktop)
-   Download our docker container available [here](https://drive.google.com/drive/folders/19tH6L7Ta3RNXJ5aJEtsv7g0q_W8WW--P?usp=sharing)
-   Run your docker desktop
-   Open a terminal and go to the folder where you have downloaded the container
-   Activate the docker container executing the command:

```
docker-compose up
```

-   Open [Neo4j Browser](https://neo4j.com/developer/neo4j-browser/)

```
http://localhost:7474
```

Choose **no authentication** and then click on connect.

First steps
-----------

-   Target knowledge to acquire: creating a graph
-   Research question: Compare how to build graphs on Neo4J and with Python and profile them

**Reminder data science tools with Python**
- Data science libraries of Python: Pandas, numpy and matplotlib on [Kaggle](http://vargas-solar.com/data-centric-smart-everything/hands-on/getting-started-with-the-data-science-ecosystem/) 
- Descriptive analytics for processing table formatted data on [Kaggle](http://vargas-solar.com/data-centric-smart-everything/hands-on/exploring-data-collections-using-descriptive-statistics/) 

**A first touch on Graph Databases: Neo4J**
- Create and query a graph DB first steps [link](https://neo4j.com/docs/graph-algorithms/current/projected-graph-model/) 
- Creating a synthetic graph [link](https://neo4j.com/docs/graph-algorithms/current/labs-algorithms/graph-generation/)
- First example with social networks [link](https://neo4j.com/docs/graph-algorithms/current/yelp-example/)

**Creating graphs with Python & introducing basic graph operations**
- Playing with Facebook data and applying classic graph operations [link](http://vargas-solar.com/data-centric-smart-everything/network-analysis/)
- Graph analysis with node2vec [link](https://www.kaggle.com/ferdzso/knowledge-graph-analysis-with-node2vec)
