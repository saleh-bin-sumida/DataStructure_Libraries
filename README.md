# DataStructure_Libraries

This project contains four libraries: clsDblLinkedList provides functionality for storing and manipulating data in a doubly linked list structure,
 clsDynamicArr provides dynamic array functionality for storing a collection of elements,
 clsMyStack offers a LIFO data structure with push and pop operations,
 and clsMyQueue offers a FIFO data structure with enqueue and dequeue operations.
 Collectively, these libraries provide a range of data storage solutions for developers.
 
 # clsDblLinkedList
This is a C++ template class library for a doubly linked list data structure. It provides various functionality including methods for insertion,
 deletion, and finding of elements, as well as features to print the entire list, reverse its order, clear its elements, and update existing items.
 The library can be used with any data type specified as a template argument by the user. The class contains an internal class called Node which represents
 a single node in the list and stores the value, next and previous pointers of the node. The head pointer, which points to the first element of the list,
 is a public member of the class. The size of the list is automatically updated with each operation, and this value can be retrieved with the Size() function.
 The methods to insert a new node take care of updating pointers and shifting the list, while methods to delete a node ensure that the chain of pointers is properly
 maintained.
 Overall, this library provides a flexible and powerful implementation of a doubly linked list which can be used in a wide range of applications.
 
 # clsMyQueue
This is a template class library called "clsMyQueue" that provides an implementation of a queue data structure using the functionality
 of a doubly linked list provided by the "clsDblLinkedList" class. The code contains functions for adding items to the back of the queue with "Push" and
 removing items from the front of the queue with "Pop". It also provides features to access the front and back elements with "Front" and "Back" respectively.
 Additionally, it includes functions to get specific elements, insert elements at the beginning or end of the list, and update or reverse the entire queue.
 The library is defined as a template class that enables the use of any data type specified as the template argument by the user.
 It inherits the size functionality from the "clsDblLinkedList" class to determine the number of elements currently in the queue.
 The class provides an intuitive and easy-to-use interface for implementing queues in C++ using a doubly linked list,
 with convenient functions for managing the list such as insertion, deletion, updating, and reordering.
 
 # clsMyStack
This is a template class library called "clsMyStack" that defines a stack data structure that is implemented using the functionality provided by the "clsMyQueue" class. It is a child class of "clsMyQueue" and inherits all of its functions. The code contains functions to push elements onto the stack with "Push",
 getting the top element of the stack with "Top", and getting the bottom element of the stack with "Bottom". The "Push" function internally calls
 the "InsertAtBeginning" function of the parent class, effectively reversing the order of the elements for a stack behavior.
 The "Top" function provides access to the front element of the queue, which in turn is the top element of the stack. The "Bottom" function similarly
 returns the back element of the queue, which is the bottom element of the stack. The class is also a template class and makes use of the same datatype
 as that of the parent class, making it highly versatile and customizable for different datatypes. This class provides an easy-to-use
 stack interface that is implemented using the functionality of the doubly linked list-based queue data structure. Overall,
 this library provides an efficient and simple way to handle the stack data structure in C++.
 
 # clsDynamicArr
This is a template class library called "clsDaynamicArray" that provides an implementation of
 a dynamic array data structure in C++. It contains functions for creating, deleting, resizing, and manipulating the array,
 as well as for accessing and modifying its elements. The class contains an internal array pointer called "OriginalArray" which allocates memory
 to the data elements of the list. The class constructor allows for the user to specify the initial size of the array. The size can be modified
 using the "ReSize" function, which can also shrink or grow the array based on a new size parameter. The functions "InsertAt" and "DeleteItemAt"
 allow for the insertion and deletion of elements at a specified index of the array. Other functions
 such as "InsertAtBeginning", "InsertBefore", "InsertAfter", "InsertAtEnd", "DeleteFirstItem", "DeleteLastItem", and "DeleteItem" provide convenient 
 ways of manipulating the array.

Copyright ©saleh-bin-sumida. All rights reserved. 
