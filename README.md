# simple-hdfs-du

Simple Virtual disk usage utility for HDFS. Shows disk usage of directories in console and virtually on a Pie Chart.

### Dependencies

"/etc/hadoop/conf/core-site.xml"
"/etc/hadoop/conf/hdfs-site.xml"

Use App in Hadoop Client node or simply copy those configuration files from a node into a machine which you would
like to run app.

 - Xwindow
 - JFree Charts 1.0.13
 - Jcommons 1.0.16
 
###  Compile
mvn package

### Usage
java -jar  target/hdfsdu-0.0.1-SNAPSHOT-jar-with-dependencies.jar <hdfs username> <hdfs directory>

ex:
java -jar  target/hdfsdu-0.0.1-SNAPSHOT-jar-with-dependencies.jar hdfs /tmp


Note: tested on Hadoop 1.X

