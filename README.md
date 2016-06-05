# GenBinTree
Generic Implementation of Binary Tree

Description:

   Created a generic class called GenBinTree.  GenBinTree will use nodes
   that store a value of the generic type to store its contents. 
   This tree will not be a search tree (no ordering of nodes by value). 

   It has the following methods.  The methods should 
   all operate on the object making the call (none are static).  

   Performed checking of the parameters and throwed exceptions where 
   appropriate.


   
   a) add
       Adds a node to the tree as described in the example below.
       Will only add leaf nodes.  Ignores duplicates.

       The add operation will work by receiving a string, as shown in the following example:

       myTree.add("100");
       myTree.add("L", "50");
       myTree.add("R", "150");
       myTree.add("LL", "40");
       myTree.add("LLR", "45");

       The resulting tree should look like this:

           100
          /   \
         50   150
        /
       40
        \ 
        45


   
   b) find
        Returns true if value passed is in the tree.

   
   c) remove
        Removes the node having the passed value.  Only leaves may be removed.  

   
   d) Swap
        Swaps children of node having the passed value.

   
   e) Mirror
        Makes the tree a mirror image of the original tree.
        For the tree above:
    
            100                 100
           /   \               /   \
          50   150    -->     150  50
         /                           \
        40                           40
         \                           /
         45                         45

   
   f) RotateRight
        Performs a single rotation on the node having the passed value.
        If a RotateRight on 100 is performed:

           100                  50
          /   \                /   \
         50   150    -->      40   100
        /                      \     \
       40                      45    150
        \ 
        45
      
   
   g) RotateLeft 
        As above but left rotation.

   
   h) CountNodes
        Recursively traverses the tree and returns the count of nodes.

   
   i) Print
        Prints node values using an inorder traversal.




