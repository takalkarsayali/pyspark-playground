# pyspark-playground
PySpark Notes

***
<details>
<summary><strong>PySpark Interview Preparation Guide</strong></summary>

# PySpark Interview Preparation Guide

A curated list of important PySpark topics frequently asked in Data Engineer and PySpark Developer interviews.

---

# 1. Spark Fundamentals

## Topics

* What is Apache Spark?
* Why Spark over Hadoop/MapReduce?
* Features of Spark
* Spark Architecture
* Driver, Executor, Cluster Manager
* Jobs, Stages, Tasks
* DAG (Directed Acyclic Graph)
* Lazy Evaluation

## Common Interview Questions

* What happens internally when a Spark job runs?
* Difference between Driver and Executor?
* Why is Spark faster than Hadoop?

---

# 2. RDD vs DataFrame vs Dataset

## Topics

* Differences between RDD, DataFrame, and Dataset
* Advantages and disadvantages
* Schema support
* Optimization differences
* Why DataFrames are preferred

## Important Concepts

* Catalyst Optimizer
* Tungsten Engine

---

# 3. Transformations vs Actions

## Transformations

* map()
* filter()
* flatMap()
* select()
* withColumn()
* groupBy()
* join()

## Actions

* collect()
* show()
* count()
* take()
* write()

## Interview Questions

* Why are transformations lazy?
* Which operation triggers execution?

---

# 4. Narrow vs Wide Transformations

## Narrow Transformations

* map
* filter

## Wide Transformations

* groupBy
* join
* distinct

## Important Concepts

* Shuffling
* Performance impact

---

# 5. DataFrame Operations

## Important Operations

* select
* filter
* where
* withColumn
* drop
* alias
* orderBy
* distinct
* union
* explode

---

# 6. Joins in PySpark

## Types of Joins

* Inner Join
* Left Join
* Right Join
* Full Join
* Cross Join
* Self Join

## Important Concepts

* Broadcast Join
* Shuffle Join
* Join Optimization

---

# 7. Window Functions

## Important Functions

* row_number()
* rank()
* dense_rank()
* lead()
* lag()

## Practice Scenarios

* Top N records
* Deduplication
* Running totals

---

# 8. Partitioning

## Topics

* What is partitioning?
* Why partition data?
* repartition()
* coalesce()
* Partition pruning

## Interview Questions

* Difference between repartition and coalesce?
* How does partitioning improve performance?

---

# 9. Caching & Persistence

## Topics

* cache()
* persist()
* Storage levels

## Interview Questions

* When should caching be used?
* Difference between cache and persist?

---

# 10. Spark SQL

## Topics

* Temporary Views
* SQL queries on DataFrames
* spark.sql()

## Interview Questions

* Spark SQL vs Traditional SQL
* Advantages of Spark SQL

---

# 11. File Formats

## Important File Formats

* CSV
* JSON
* Parquet
* ORC
* Iceberg (Basics)

## Why Parquet?

* Columnar storage
* Compression
* Faster analytics queries

---

# 12. Hive Concepts

## Topics

* Hive Metastore
* Managed vs External Tables
* Partitioning
* Bucketing

---

# 13. ETL Pipelines

## Topics

* Extract → Transform → Load
* Batch vs Streaming
* Incremental Loads
* Error Handling

## Interview Questions

* How do you design ETL pipelines?
* How do you handle bad records?

---

# 14. Performance Optimization

## Important Optimization Techniques

* Avoid collect()
* Reduce shuffling
* Use partitioning
* Broadcast joins
* Predicate pushdown
* Caching
* Proper file sizing

## Interview Questions

* How do you optimize slow Spark jobs?

---

# 15. Handling Skewed Data

## Topics

* What is data skew?
* Causes of skew
* Salting concept

---

# 16. Scenario-Based Questions

## Common Scenarios

* Spark job is slow — how will you debug?
* One executor failed — what happens?
* Huge dataset join optimization?
* Millions of small files issue?
* Why is the job causing excessive shuffle?

---

# Coding Topics to Practice

## Beginner

* Read CSV files
* Filter rows
* GroupBy and Aggregations
* Basic joins

## Intermediate

* Window functions
* Deduplication
* Null handling
* Date transformations

## Advanced

* Repartitioning
* Writing Parquet files
* Performance optimization logic

---

# Most Important Topics for Data Engineer Interviews

## High Priority

1. DataFrames
2. Transformations vs Actions
3. Lazy Evaluation
4. Joins
5. Window Functions
6. Partitioning
7. Parquet
8. Spark Architecture
9. Repartition vs Coalesce
10. Broadcast Joins
11. ETL Pipelines
12. Spark SQL
13. Hive Concepts
14. Performance Optimization
15. Caching

---

# Recommended Practice

* Build mini ETL projects using PySpark
* Practice SQL daily
* Solve transformation-based problems
* Explain concepts aloud as if teaching someone
* Focus on understanding execution flow and optimization

---

# Suggested Tools & Technologies

* PySpark
* Apache Spark
* Hive
* Airflow
* AWS S3
* Athena
* Parquet
* Iceberg
* SQL
* Python

</details>
