# Clustering
clustering algorithm for computing max-spacing 

## algorithm 1  
Given number of clusters k, computing max-spacing  

The input file describes a distance function (equivalently, a complete graph with edge costs).  It has the following format:  

[number_of_nodes]  
[edge 1 node 1] [edge 1 node 2] [edge 1 cost]  
[edge 2 node 1] [edge 2 node 2] [edge 2 cost]  
...  

There is one edge (i,j)(i,j) for each choice of 1 <= i < j <= n, where n is the number of nodes.  

## algorithm 2  
Compute the largest value of k such that there is a k-clustering with spacing at least 3

The distances (i.e., edge costs) are only defined implicitly, rather than being provided as an explicit list.  

 The format is:  
[# of nodes] [# of bits for each node's label]  
[first bit of node 1] ... [last bit of node 1]  
[first bit of node 2] ... [last bit of node 2]  
...  
  
The distance between two nodes uu and vv in this problem is defined as the Hamming distance--- the number of differing bits --- between the two nodes' labels.  
