# Stack-using-array
A stack is an abstract data type in computer science that represents a collection of elements. It is a Last-In-First-Out (LIFO) data structure, which means that the last element added to the stack will be the first one to be removed.

A stack has two primary operations:

1. Push: adds an element to the top of the stack
2. Pop: removes the top element from the stack

Other operations that can be performed on a stack include:

3. Peek: returns the top element of the stack without removing it
4. isEmpty: checks if the stack is empty
5. isFull: checks if the stack is full (in case of a fixed-size stack)

Stacks can be implemented using arrays or linked lists. In an array-based implementation, the elements of the stack are stored in an array and a variable called top keeps track of the index of the top element. In a linked list implementation, each node in the list contains an element and a pointer to the next node, and the top of the stack is represented by the head of the list.

Stacks have many applications in computer science, such as function call stack in programming languages, undo/redo operations in text editors, and backtracking algorithms in artificial intelligence.
# Algoritm
Here is a basic algorithm for a stack:

1. Initialize an empty stack.
2. Push an element onto the stack:
   a. Check if the stack is full (if using a fixed-size array implementation).
   b. Increment the top of the stack pointer.
   c. Assign the value to the top of the stack.
3. Pop an element from the stack:
   a. Check if the stack is empty.
   b. Get the value at the top of the stack.
   c. Decrement the top of the stack pointer.
4. Peek the top element of the stack:
   a. Check if the stack is empty.
   b. Return the value at the top of the stack.
5. Check if the stack is empty:
   a. Return true if the top of the stack pointer is -1 (for array implementation) or if the head of the list is null (for linked list implementation).
   b. Return false otherwise.
6. Check if the stack is full:
   a. Return true if the top of the stack pointer is equal to the maximum size of the stack minus one (for array implementation).
   b. Return false otherwise.
# Screenshot
![p10](https://user-images.githubusercontent.com/126184012/234300994-bfd26946-20a1-494e-aa65-136d4ad43e92.png)
# Application
Stacks have many applications in computer science, including:

1. Function call stack: When a function is called, its local variables and parameters are stored on the stack. The stack is then used to keep track of the function calls, so that when a function returns, its local variables and parameters are removed from the stack.

2. Expression evaluation: Stacks can be used to evaluate expressions, such as arithmetic expressions or boolean expressions. Each operand and operator is pushed onto the stack, and when an operator is encountered, the operands are popped from the stack and the result is pushed back onto the stack.

3. Undo/redo operations: In applications such as text editors or graphic design tools, stacks can be used to implement undo and redo operations. Each change to the document is stored as a command on the stack, and when the user requests an undo or redo, the appropriate command is popped from the stack and executed.

4. Backtracking algorithms: Stacks can be used in backtracking algorithms, which are used to solve problems by incrementally building a solution and undoing incorrect decisions. The stack is used to store the current state of the solution, and when a dead end is reached, the solution can be backed up to a previous state.

5. Parsing: Stacks are often used in parsing algorithms, which are used to analyze the syntax of a program or expression. The stack is used to keep track of the symbols and operators encountered during parsing, and to ensure that they are used in the correct order.
