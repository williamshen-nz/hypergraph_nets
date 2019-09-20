# Hypergraph Networks
Hypergraph Networks is an extension of [Graph Nets](https://github.com/deepmind/graph_nets) 
by Google DeepMind to hypergraphs, implemented in PyTorch.

Hypergraph Networks allow you to build powerful hypergraph neural networks by using core blocks
that take hypergraphs as input and return hypergraphs as output. Existing deep learning approaches,
including [Hypergraph Neural Networks](https://github.com/iMoonLab/HGNN) and 
[Dynamic Hypergraph Neural Networks](https://www.ijcai.org/proceedings/2019/0366.pdf), can be
formulated using Hypergraph Networks.

## Progress
The Hypergraph Networks library is currently under testing and will be released in the near
future (by the end of 2019).

For any queries, please contact 
[william.shen@anu.edu.au](mailto:william.shen@anu.edu.au).

### What is a hypergraph?
A [hypergraph](https://en.wikipedia.org/wiki/Hypergraph) is a graph where there are 
hyperedges that can join any number of vertices. It is easy to observe that a hypergraph
is a generalisation of a normal graph, as a hypergraph where each hyperedge is of size
2 is just a normal graph.
