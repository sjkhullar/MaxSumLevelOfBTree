Let us define the problem statement:

What is level in binary tree? 

As per the definition of binary tree is one, where each node has, at most, 2 children. Each node can have left and right child. The root of the tree, is at level 0. Root's children are at level 1, etc.


As an example, consider the tree:

			   A   ------Level 0
			  /  \
			 B    C -----Level 1
		
At level 1, the tree has the nodes B and C.

We can go through the complete code. We have created 2 packages

1.) org.learn.Question: Under this question package, we will have MaxSumLevelclass which is responsible for finding the level in binary tree, which is having maximum sum

2.) org.learn.Client: Under this package we have main function, where we are constructing the tree and then we are traversing the whole tree using level order traversal for finding the level in binary tree, which is having maximum sum.
