To use, make sure Hadoop is in your path and, optionally, HADOOP_CONF is set.

From the downloaded archive execute,

> yarn jar hadoop.jar data/apache.200.txt output

If building from source,

> gradle jar
> yarn jar ./build/libs/hadoop.jar data/apache.200.txt output

Note that if HADOOP_CONF references a cluster, the above 'output' directory will show up in HDFS.
