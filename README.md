# HBaseWordCount Cloud computing project 4

Write an HBase WordCount program to count all unique terms’ occurrences from the clueWeb09 dataset.
Each row record of columnfamily ”frequencies” is unique; the rowkey is the unique term stored in byte
format, column name is ”count” and value is the term frequency shown in all documents. Load the result
to HBase WordCountTable. Figure 1 shows the schema of WordCountTable. You will compare the results
of your finished run to a correct version we will supply to you.

# Introduction
WordCount is a simple program which counts the number of occurrences of each word in a given text input
dataset. It fits very well with the map/reduce programming model, making WordCount a great example to
understand the Hadoop MapReduce programming style. Instead of loading the data from HDFS, we will
load our data directly from existing HBase records which store the similar content structures on HBase and
HDFS.

In this homework and the next homework (Building an Inverted Index) we use the same source code,
which can be found in: /root/MoocHomeworks/HBaseWordCount.

References
1. Clueweb09 dataset. http://lemurproject.org/clueweb09/.
2. Hadoop WordCount. http://salsahpc.indiana.edu/csci-b649-spring-2014/projects/project1.html.
3. HBase MapReduce Examples. http://hbase.apache.org/book/mapreduce.example.html.

For more details, [click here](https://github.com/prateek22sri/HBaseWordCount/blob/master/project4.pdf)
