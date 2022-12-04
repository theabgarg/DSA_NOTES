# Data Structures

## Arrays

- To store data in a linear fashion, when you are having the idea of the size of the array.

### Time Complexity

| Operation | Time Complexity |
| --------- | --------------- |
| Access    | O(1)            |
| Search    | O(n)            |
| Insertion | O(1)            |
| Deletion  | --              |

## Vector

- To store data in a linear fashion, when you are not having the idea of the size of the array, and you want to add or remove elements dynamically.
- better than arrays, because they can grow and shrink dynamically, gives ability to delete and insert elements in the at any index of arrray.

### Time Complexity

| Operation | Time Complexity |
| --------- | --------------- |
| Access    | O(1)            |
| Search    | O(n)            |
| Insertion | O(n)            |
| Deletion  | O(n)            |


## Linked Lists
- It's beneifical when access elements on time is required and and also you space limits, also if you want to insert or delete elements in O(1) time, this is better than arrays.
- The reason for the time complexity for insertion is O(1) becuase if you have the address of the previous node, you can insert the new node in O(1) time.
- However with arrays it's not possible, because you have to shift all the elements to the right, which takes O(n) time if you have to shift at the beginning elements.

### Time Complexity

| Operation | Time Complexity |
| --------- | --------------- |
| Access    | O(n)            |
| Search    | O(n)            |
| Insertion | O(1)            |
| Deletion  | O(1)            |

## Stacks

### Time Complexity

| Operation | Time Complexity |
| --------- | --------------- |
| Access    | O(n)            |
| Search    | O(n)            |
| Insertion | O(1)            |
| Deletion  | O(1)            |


## Queues
- When you want to perform operations in a order, without removing the elements, you can use queues.

### Time Complexity

| Operation | Time Complexity |
| --------- | --------------- |
| Access    | O(n)            |
| Search    | O(n)            |
| Insertion | O(1)            |
| Deletion  | O(1)            |

## Trees

## BST 🌲 (Binary Search Tree)
- When wanted to array data in sorted and fast way, you can use BST.
- Also in hierarchical data, you can use BST.

### Time Complexity

| Operation | Time Complexity |
| --------- | --------------- |
| Access    | O(log n)        |
| Search    | O(log n)        |
| Insertion | O(log n)        |
| Deletion  | O(log n)        |

## Hash Tables
- When you want to store data in key-value pairs, you can use hash tables.

### Time Complexity

| Operation | Time Complexity |
| --------- | --------------- |
| Access    | O(1)            |
| Search    | O(1)            |
| Insertion | O(1)            |
| Deletion  | O(1)            |

worst case is O(n) for all operations.

<!-- write a hashfunction -->
<!-- 
## Graphs

### Time Complexity -->
