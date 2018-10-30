# node_tree

An unbalanced tree of arbitrary but limitable breadth and depth. Supports random and asynchronous generation.

Node children are kept in a HashMap instead of a list to support arbitrary placement.

"Breadth" (`maxBreadth`) here refers to the number of children per node, not to the tree itself.