# Data-Structure-and-Algorithms
Heap Sort using C++
In this project, heap sorting is done.In heap sort we have created a complete binary tree (ordered set of nodes where left children are less than or equal to 
current node,which is less than all right nodes) because after creating it we can sort it. Initially on receiving an unsorted list, the first step in heap sort is 
to create a Heap data structure (Max-Heap or Min-Heap). Once heap is built, the first element of the Heap is either largest or smallest (depending upon Max-Heap 
or Min-Heap). If the heap is min then the first element will be smallest and in max the first element is the largest element. Since the tree satisfies Max-Heap 
property, then the largest item is stored at the root node. 

Swap: Remove the root element and put at the end of the array (nth position) Put the last item of the tree (heap) at the...
Remove: Reduce the size of the heap by 1.
Heapify: Heapify the root element again so that we have the highest element at root. The process is repeated until all the items of the list are sorted.

There are 3 traversals. First is the in-order traversal, in this First Left element is displayed then Root element and then Right element. Second is pre-order 
traversal, in this first Root element then Left element and at the end Right element. Third is post-order traversal in which first Left element then Right element
and at the end Root element will be displayed.

BINARY SEARCH TREE:

Binary Search Tree (BST) is a tree in which all the nodes follow the below mentioned properties:

The left sub-tree of a node has a value less than or equal to its parent node's value.
The right sub-tree of a node has a value greater than to its parent node's value.

Thus, BST divides all its sub-trees into two segments; the left sub-tree and the right sub-tree and can be defined as:

left_subtree (value) ≤   parent_node (value) ≤ right_subtree (value) 

All elements stored in the left subtree of any node x are less than the element stored at x and all elements stored in the right subtree of x are greater than the 
element at x. Heap is almost a complete binary tree.
