

******************Map Reduce on Distributed Grep********************

1. Start 4 Nodes
2. NameNode and JobTracker  10.0.0.1 mask 255.255.255.0
3. DataNode and TaskTracker 10.0.0.2-3 mask 255.255.255.0
4. Start HDFS first by starting NameNode javac *.java then java NameNode
5. Start DataNode by java DataNode
6. STart Client on any node and put get list

7. Start JobTracker by running bash JobTracker
8. Start TaskTracker by bash TaskTracker
9. Start JobClient on any Node and enter Name of file.
10. Word to find is stored in file searchString.txt
11. output and all intermediate files are uploaded in HDFS by map*.fileName and outputFile

Java RMI tutorial
https://www.youtube.com/watch?v=GKIwu6XyqPI&list=PLGwb7xZHg-oMR0e6TSHKbc2SKOn_HJ-DR
