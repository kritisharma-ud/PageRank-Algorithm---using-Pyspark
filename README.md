# PageRank-Algorithm-using-Pyspark
Implementing Google Pagerank Algorithm in Pyspark
The file contains the python script that implements the PageRank Algorithm in PySpark. This method used distributed and parallel programming for the implementation.
Below are the details and instructions for the same:

Files:
cps534_pagerank.ipynb 

Input Files: nodes_input.txt nodes_dang.txt

Requirements:
The code can be run in any environment with the respective installations.
Python, spark, Apache spark. If you are trying locally, you must be Apache spark installed and configured.
The provided code is created on Google collab. Each cell needs to be executed one by one to download the packages and created the instant runtime.

Input :
The input provided are two in the zip file.
The way to read the input can vary according to the OS or the file used.
Program:
Running the cells one by one and execute the code in one manner. There are 2 functions that are called at the last code snippet:
def dangling_nodemass(linkRDD, pagerankRDD): return dangling_node_m
def updatepangerank(pagerankRDD, dangling_node_m, num): return updated_pagerankRDD

Output:
Since it is parallel programming, it takes take to run the code. Each iteration with prev and updated pagerank is printed.
In the last the FinalPageRank is printed.
