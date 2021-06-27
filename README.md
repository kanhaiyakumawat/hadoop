# What is Hadoop?
Its a big data platform, which enables distributed processing of data. The hadoop is Apache Open Source Framework. Hadoop Framework is written in Java and uses simple programming constructs to process large data in distributed fashion.
# Environment
## Hadoop 3.3.1
This is latest version from apache hadoop
## GCP E2 VM with Debian Linux
Created a GCP E2 VM to expermiment hadoop. Using Debian OS as that was default available in GCP
# Core of Hadoop Architecture
## Map Reduce - Computation Layer
This is processiing or execution layer of the framework. Map Reduce is programming construct of processing large set of the data in parallel on multiple nodes which are running on commodity hardwards.
## HDFS - Storage Layer
This is storgage layer of Hadoop Framework. Hadoop Destributed File System is based on Google File System and allows dividing the data in smaller parts and then allowing the processing of these small files on cluster in reliable and fault tolerant manner.
### Hadoop Common
Hadoop Common are the java libraries and utilities which are required by hadoop modules.
### Yarn
This is job scheduling framework. This is used to schedule the jobs for executing the files.

# Running Hadoop
Hadoop can run in 3 modes
## Single Node 
Only one node is running on localhost
## Pseudo Distributed Mode
This is to simulate the distributed processing on single node.
## Distributed Mode
This is actual distributed mode where 100s of nodes are running in parallel to process the files.


# How does it work?
The data is divided in smaller chunks of 128MB files
Then these files are uploaded to cluster nodes.
Each Block is replicated to make sure the fault tolerance.
HDFS monitors processing
Sorting of the data at each node
Send the sorted data to specific machines
logging etc

