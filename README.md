# Assignment4CS260


Create an array-based list or a linked-list that allows:

an add function that takes a value and inserts it into a given position into the list
(example: myList.add(someValue, somePosition) )

a remove function that takes a position and removes the value stored at that position of the list and returns it
(example: myList.remove(somePosition) )

a get function that takes a position and returns that value without removing it
(example: myList.get(somePosition) )

Be sure to include at least one test function for each piece of functionality that should verify that your code is working!  This should be at least one test per behavior, likely more.  You can make these tests in a source file with a main where your tests are either directly in the main or inside their own standalone functions (please do not neglect the importance of testing!)

(Note winter 2021: we will cover the analysis of some of this in class next week, then we will have you analyze the next ones!) Analyze the complexity of your implementation with line-by-line analysis

Note: This assignment is to get you to think about the trade-offs that we may have to weigh before using one structure over anothe



#Small Design 
- Whst is a a linked list? 
  - A linked list is 
  - ...
  - A dynamic data structure to store data items. 
  - Unlike arrays linked lists do not store data items in the contiguous 
  -   memory locations.
  -   Linked lists have nodes that contain two parts and the first part     stores the actual data and the second part has a pointer that points 
to the next node. 
- The first node of the linked list is called the head and while the last node is called the tail. 
- The last node of the linked list will have its next pointer as null since it will not have any memory address pointed toward it.
- Each nod has a pointer to the next node data items in the linked list need to not be stored in a contiguous location. They(nodes) can be scattered.
- We can access the nodes anytime as each noce will have an address of the next node.
- Can add data as well as delte it very easily.
- We can GROW and SHRINK it dynamically 
- As long as the memory is available we can have as many dtata items added to the linked list.
- To reach the node we need to traverse the linked list from the start and only when we can access the desired node. 
