# NodeClassification-GCN

In this work, we concentrate on the problem of classifying nodes (research paper in this case) in a
graph (a citation network), where labels are only available for a small subset of nodes.
To find out the labels for remaining samples(data points) we are using this semi-supervised learning approach.

In this we reproduce an approach for semi-supervised learning on graph-data that is based on a very efficient variant of
graph-convolutional neural networks(GCN).
We train mainly on a supervised target for all nodes with labels, by using f(·)a neural network model, the model propagates gradient information from the supervised loss and will enable it to learn representations of nodes both with and without labels.

Main tasks that we dealt in are:

-->Firstly,we introduce a simple and well-behaved layer-wise propagation rule for neural network models which operate directly on graphs.
-->Secondly, we demonstrate how this form of a graph-based neural network model can be used for fast and scalable semisupervised classification of nodes in a graph.

I thank my team memebers for their support, S.Sai Vikas & M.Rahul.
