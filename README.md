# Binary trees

- Binary Tree:
A binary tree is a hierarchical data structure composed of nodes, where each node has at most two child nodes, referred to as the left child and the right child.

- Difference between Binary Tree and Binary Search Tree (BST):
A binary tree is a general tree structure where the value of each node can be anything. In contrast, a Binary Search Tree (BST) is a specific type of binary tree where the left child node has a value less than or equal to the parent node, and the right child node has a value greater than the parent node. This property enables efficient searching, insertion, and deletion operations.

- Possible Gain in Time Complexity Compared to Linked Lists:
The time complexity for searching, insertion, and deletion in a balanced Binary Search Tree is O(log n), which is more efficient than the O(n) time complexity of these operations in a singly linked list. This gain in time complexity is due to the binary tree's ability to maintain a sorted order for faster search operations.

- Depth, Height, and Size of a Binary Tree:
    - The "depth" of a node is the distance from the root node to that particular node.
    - The "height" of a binary tree is the maximum depth among all the nodes in the tree, i.e., the longest path from the root to a leaf node.
    - The "size" of a binary tree refers to the total number of nodes in the tree.

- Traversal Methods for Binary Trees:
    - In-order traversal: Left subtree, current node, right subtree.
    - Pre-order traversal: Current node, left subtree, right subtree.
    - Post-order traversal: Left subtree, right subtree, current node.

- Complete, Full, Perfect, and Balanced Binary Tree:
    - A "complete binary tree" is a binary tree in which all levels are fully filled, except possibly the last level, and nodes are as left as possible.
    - A "full binary tree" is a binary tree in which every node has either 0 or 2 children.
    - A "perfect binary tree" is a binary tree in which all internal nodes have exactly two children, and all leaves are at the same level.
    - A "balanced binary tree" is a binary tree where the difference in the heights of the left and right subtrees of every node is at most one, ensuring efficient search and traversal operations.
