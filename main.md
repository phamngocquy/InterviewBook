* Network:
    * TCP vs UDP
* OS
    * Concurrency vs parallel:
        * Concurrency is about dealing with lots of things at once. Parallelism is about doing lots of things at once.
        * What will happen if 2 processes read/write to the same file?
            * The only issue is if you are trying to read a block that the writer is writing at the same time. In that
              cause, the data you get is unpredictable but you should be able to read. In short, simultaneous reads and
              write would not, by themselves, cause a program to crash.
              (edited)
    * Computer Buffer
        * https://techterms.com/definition/buffer

### ByteDance Site Reliability Engineering

#### Linux

* What is load of server ?
* How to investigate in case server is overload

#### Network

* Proxy:
    - While all proxy servers give users an alternate address with which to use the internet, there are several
      kinds—each with its own features.

#### Database:

* PostgreSQL:
    - How optimize database:
        - general optimize: tuning database configuration
        - data schema optimize: index, partition
    - Scale:
        - Cluster mode

#### Big DATA

* HDFS:
    - How HDFS stored data distributed at many machine ?

### ByteDance:  Software Engineer

#### Database:

+ **MYSQL**:
    + **Indexing**:
      <details>
      <summary>B-Tree: Algorithm, indexing column, user-case, < > = </summary>

        + B-Tree is a balanced tree: all branches of the tree have the same length.
        + [B- tree’s height should lie as low as possible, All the leaf nodes of the B-tree must be at the same level](https://www.geeksforgeeks.org/difference-between-b-tree-and-b-tree/)
        + How index work in this case: WHERE age = 5 and Where age > 5? The complexity to go to the next record?
            + [The MySQL optimizer will use the indexes where it thinks it is appropriate to do so](https://stackoverflow.com/questions/6747359/do-indexes-speed-up-greater-than-comparison-in-mysql)
        + As with other indexes on columns of InnoDB tables, a multi-valued index cannot be created with USING HASH;
          attempting to do so results in a warning: This storage engine does not support the HASH index algorithm,
          storage engine default was used instead. (USING BTREE is supported as usual.)
      </details>
      <details>
          <summary>Hash: algorithm, use-case, < > =</summary>
      </details>
      <details>
          <summary>Hash vs B-Tree</summary>
      </details>
    + **Partitioning**
      <details>
      <summary>How DB partition data</summary>

      </details>

* **PostgeSQL**:
    *

#### Candidate ask interviewer

* Technical stack at ByteDance:
    * Almost using GoLang and Rust
    * System in the cloud with the hundred thousand of k8s pod
    * They have private contract with several cloud service provider

### VIN vantix: Data Engineer

### Easy Algorithm:

* merge two sorted list

#### Big DATA - experience

* Hadoop
* Minio

#### Behavioral question

* Build monitoring database system

### Hedge Fund: Data Engineer

#### Linux

* Thread
    *
* Process
    *
* Difference between thread vs process
    *

#### Programing Language

* OOP
    *
* Compiler vs Interpreter language
    * 
