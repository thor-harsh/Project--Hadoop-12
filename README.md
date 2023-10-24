# Project--Hadoop-12


<table>
 
  **In this project we will use Spark Streaming for doing analysis of data in real time with the help of Flume which is gonna be an amazing stuff to have in your toolkit.**

 Lets dive into learning about Spark and Flume first before jumping to the code..

 **What is Apache Spark and What is Spark Streaming?**

 Apache Spark is an open-source unified analytics engine for large-scale data processing. Spark provides an interface for programming clusters with implicit data parallelism and fault tolerance.

Apache Spark Streaming is a scalable fault-tolerant streaming processing system that natively supports both batch and streaming workloads.

**What is Flume?**

Apache Flume is a distributed, reliable, and available software for efficiently collecting, aggregating, and moving large amounts of log data. It has a simple and flexible architecture based on streaming data flows.


**Layout of Project**

Initially we will set up a log directory.We will keep track of data movement on real time for that directory using Flume Source which is Spool used here.

Then we will pass that data through memory to Sink and from then it will go into Avro which is the communication interface where Spark Streaming will be applied to do the 
analysis in real time.


</table>
