# Movie analysis and recommendation system

Nowadays, the use of online services to watch movies has become familiar for people. The development of movies platforms makes it easier for users to access movies. However, too many choices also make it difficult for users to find the right movie. A Recommendation system could solve this problem.

## File
- 1 readme file
- 1 ipynb include code for analysis and visuzlation data
- 2 PDF report export from 2 ipynb file. (one not show in here)

## Dataset: https://grouplens.org/datasets/movielens/20m/

- MovieLens 20M : Contains 20000263 ratings and 465564 tag applications across 27278 movies. These data were created by 138493 users between January 09, 1995 and March 31, 2015. 

- File data used: movies.cvs, ratings.cvs, tags.csv, links.csv


## Procedure

- Store data in hadoop File system

- Utilized PySpark to load movielens data and used SQL to query and analyze data 

- Get more movie detail through ImdbPy

- Applied Collaborative Filtering and Matrix Factorization methods to construct a recommendation system with PySpark
## System architecture

![System](https://github.com/uyentt99/Movielen/blob/main/Picture/SystemArchitecture.png) 

## Data stored in HDFS

![Data](https://github.com/uyentt99/Movielen/blob/main/Picture/DataHDFS.png)

