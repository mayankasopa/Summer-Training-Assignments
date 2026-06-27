# 📚 GATE CSE — Previous Year Questions: Stack & Linked List

> **Source:** GeeksforGeeks GATE Archives & ExamSIDE (GATE CSE Official PYQs)
> **Coverage:** GATE CSE 1991 – 2023
> **Total Questions:** 50 (26 Stack | 17 Linked List | 7 Mixed)

---

## 📌 Table of Contents

- [Stack Questions (1–30)](#-stack-questions)
- [Linked List Questions (31–47)](#-linked-list-questions)
- [Mixed / Both (48–50)](#-mixed--both-topics)
- [Quick Reference](#-quick-reference)

---

## 🟦 Stack Questions

| # | Year | Marks | Question |
|---|------|-------|----------|
| 1 | GATE CSE 1991 | 1 | The following sequence of operations is performed on a stack: `PUSH(10), PUSH(20), POP, PUSH(10), PUSH(20), POP, POP, POP, PUSH(20), POP`. What is the sequence of values popped out? |
| 2 | GATE CSE 1994 | 1 | Which of the following permutations can be obtained in the output (in the same order) using a stack, assuming that the input is the sequence `1, 2, 3, 4, 5` in that order? |
| 3 | GATE CSE 1994 | 1 | A stack is used to pass parameters to procedures in a procedure call. If an error occurs within a procedure and it needs to be unrolled, how many times does the stack need to be popped? |
| 4 | GATE CSE 1995 | 1 | The postfix expression for the infix expression `A + B * (C + D) / F + D * E` is: |
| 5 | GATE CSE 1997 | 1 | Which of the following is **essential** for converting an infix expression to the postfix form efficiently? |
| 6 | GATE CSE 1997 | 2 | A priority queue Q is used to implement a stack that stores characters. `PUSH(C)` is implemented as `INSERT(Q, C, K)` where K is the priority assigned to C. Which of the following is a valid choice of priorities that ensures the correct implementation of the stack? |
| 7 | GATE CSE 1998 | 2 | Compute the postfix equivalent of the following infix expression: `3 * log(x+1) - a/2` |
| 8 | GATE CSE 1998 | 2 | What value would the following recursive function return for input `x = 95`? (Function computes via stack-based recursion.) |
| 9 | GATE CSE 2003 | 2 | Let S be a stack of size `n ≥ 1`. Starting with the empty stack, suppose we push the first n natural numbers in sequence, and then perform n pop operations. What sequence of pops is produced? |
| 10 | GATE CSE 2003 | 1 | Assume you have a stack and a queue. Which of the following is TRUE? **(A)** Stack using queue: Yes, Queue using stack: Yes **(B)** Stack using queue: Yes, Queue using stack: No **(C)** Stack using queue: No, Queue using stack: Yes **(D)** Neither can simulate the other. |
| 11 | GATE CSE 2004 | 1 | The best data structure to check whether an arithmetic expression has **balanced parentheses** is a: |
| 12 | GATE CSE 2004 | 2 | A program attempts to generate permutations of string `'abcd'` by pushing characters a, b, c, d in order onto a stack and popping them. How many distinct permutations can be generated? |
| 13 | GATE CSE 2004 | 2 | Assume operators `+, -, ×` are left-associative and `^` is right-associative. Order of precedence (high to low): `^, ×, +, -`. Convert `A - B ^ C ^ D × E + F` to postfix. |
| 14 | GATE CSE 2005 | 1 | A function `f` defined on stacks of integers satisfies: `f(∅) = 0` and `f(push(S, i)) = max(f(S), 0) + i` for all stacks S and integers i. What does f compute? |
| 15 | GATE CSE 2006 | 2 | The following function computes the value of `mCn` correctly for all legal values m and n (m ≥ 1, n ≥ 0 and m > n). What is the missing code in the recursive implementation? |
| 16 | GATE CSE 2006 | 2 | An implementation of a queue Q using two stacks S1 and S2: `void insert(Q,X){push(S1,X);}` `void delete(Q){if(isEmpty(S2)) while(!isEmpty(S1)) push(S2,pop(S1)); return pop(S2);}` — What are the time complexities of insert and delete? |
| 17 | GATE CSE 2007 | 1 | Consider the following statements: **S1:** A queue can be implemented using two stacks. **S2:** A stack can be implemented using two queues. Which is TRUE? |
| 18 | GATE CSE 2007 | 2 | The following postfix expression with single digit operands is evaluated using a stack: `8 2 3 ^ / 2 3 * + 5 1 * -`. What is the result? |
| 19 | GATE CSE 2007 | 2 | Suppose you are given a queue of integers. Using only a constant number of stacks as auxiliary, can you sort the elements of the queue in O(n log n) time? |
| 20 | GATE CSE 2007 | 2 | Consider the C program that uses push and pop to evaluate an arithmetic expression. The program implements _______ parsing strategy. |
| 21 | GATE CSE 2009 | 1 | A program P calls a subprogram S. The relative address of S from P — when is it determined? |
| 22 | GATE CSE 2012 | 2 | Suppose a circular queue of capacity `(n–1)` elements is implemented with an array of n elements. Assume insertions and deletions use modulo. Which of the following correctly tracks queue size? |
| 23 | GATE CSE 2013 | 1 | In a stack with PUSH and POP operations, the worst-case time complexity for n operations is: |
| 24 | GATE CSE 2014 Set 2 | 2 | Suppose a stack supports an instruction `REVERSE` that reverses the order of elements on the stack, in addition to PUSH and POP. What is the time complexity to perform k operations including REVERSE? |
| 25 | GATE CSE 2015 Set 3 | 1 | The result of evaluating the postfix expression: `10 5 + 60 6 / * 8 -` is: |
| 26 | GATE CSE 2016 Set 1 | 1 | A queue is implemented using an array such that ENQUEUE and DEQUEUE operations are performed efficiently. Which one of the following statements is TRUE about such implementation? |
| 27 | GATE CSE 2021 Set 1 | 2 | Consider the following sequence on an empty stack: `push(54), push(52), pop(), push(55), push(62), s = pop(), push(s-2)`. What is the final top element? |
| 28 | GATE CSE 2022 | 1 | Consider two stacks S1 and S2. S1 has capacity 4 and contains `100, 200, 300, 400`; S2 is empty with capacity 2. Using only PushToS2, PushToS1, GenerateOutput — what is the minimum number of operations to output 400 first? |
| 29 | GATE CSE 2023 | 1 | A sequence `a0=1, a1=5, a2=7, a3=8, a4=9, a5=2` is pushed into stack S and enqueued into queue Q. After a series of mixed push/pop/enqueue/dequeue operations, what is the top element of S? |
| 30 | GATE CSE 2015 | 1 | Consider a stack data structure into which we can PUSH and POP records. Assume each record has a positive integer key and all keys are distinct. We wish to augment the stack with an O(1) time `MIN` operation that returns a pointer to the record with smallest key. Which augmentation achieves this? |

---

## 🟪 Linked List Questions

| # | Year | Marks | Question |
|---|------|-------|----------|
| 31 | GATE CSE 1994 | 1 | Which of the following operations is performed more efficiently by a **doubly linked list** than by a singly linked list? |
| 32 | GATE CSE 1996 | 1 | Where `Fwd` and `Bwd` represent forward and backward links. Which code segment correctly deletes the node pointed to by X from a doubly linked list, given X is neither first nor last? |
| 33 | GATE CSE 2000 | 1 | What is the worst-case time complexity of inserting n elements into an empty linked list, if the linked list must be maintained in **sorted order**? |
| 34 | GATE CSE 2001 | 1 | N items are stored in a sorted doubly linked list. For a delete operation, a pointer is provided to the node to be deleted. What is the time complexity? |
| 35 | GATE CSE 2004 | 2 | Consider an implementation of unsorted singly linked list with head and tail pointers. What is the time complexity of inserting at the end vs. beginning? |
| 36 | GATE CSE 2006 | 2 | The following C function takes a singly-linked list as argument and modifies it by **moving the last element to the front**. Fill in the missing code. |
| 37 | GATE CSE 2008 | 1 | `struct item { int data; struct item *next; }; int f(struct item *p)` returns 1 iff the linked list `p` is _________ (based on comparing `p->data` with `p->next->data` recursively). |
| 38 | GATE CSE 2012 | 1 | Let `SLLdel` delete a node from singly linked list given a pointer to the node and head; `DLLdel` deletes from doubly linked list. What is the worst-case time complexity of `SLLdel` vs `DLLdel`? |
| 39 | GATE CSE 2014 Set 1 | 2 | Consider the problem of **reversing a singly linked list**. Which one of the following statements is TRUE about the time complexity of algorithms that solve this in O(1) space? |
| 40 | GATE CSE 2015 Set 1 | 2 | A queue is implemented using a non-circular singly linked list with head and tail pointers. enqueue inserts at head, dequeue deletes from tail. What is the time complexity of the most time-efficient implementation? |
| 41 | GATE CSE 2016 Set 2 | 2 | `typedef struct list{int data; struct list *next;} LIST;` Given L1 (9 nodes) and L2 (7 nodes), after executing a C program segment that modifies L1, how many nodes does L1 contain? |
| 42 | GATE CSE 2018 | 2 | Consider the code snippet in C that computes the number of nodes in a non-empty singly linked list. Fill in `E1` and `E2` in the recursive function `getListSize()`. |
| 43 | GATE CSE 2019 | 1 | N distinct integers are stored in a sorted doubly linked list. What is the minimum number of element comparisons required to find an integer in the list that is **NOT the largest**? |
| 44 | GATE CSE 2021 Set 2 | 1 | A circular doubly linked list is used to implement a queue. Given that the rear pointer is maintained, what is the time complexity of enqueue and dequeue operations? |
| 45 | GATE CSE 2022 | 1 | Which of the following is the correct statement about time complexity of deletion in singly vs. doubly linked list when only a pointer to the node is given (no head pointer)? |
| 46 | GATE CSE 2023 | 2 | A program inserts keys 1 to n into a linked list in order such that the list remains sorted. If the list is singly linked and has a tail pointer, what is the worst-case time to insert the n-th element? |
| 47 | GATE CSE 2005 | 1 | Consider an implementation of unsorted single linked list. Suppose it has its representation with a head and a tail pointer (i.e., both the first and last elements of the list are tracked). What is the complexity of each operation: insert at head, insert at tail, delete from head, delete from tail? |

---

## 🟩 Mixed / Both Topics

| # | Year | Marks | Question |
|---|------|-------|----------|
| 48 | GATE CSE 1996 | 1 | Which of the following statements is TRUE? (i) FIFO computations are efficiently supported by STACKS; (ii) Implementing LISTS on linked lists is more efficient than on arrays for almost all basic LIST operations; (iii) Implementing QUEUES on circular array is more efficient than on linear array; (iv) LIFO computations are efficiently supported by QUEUES. |
| 49 | GATE CSE 2003 | 1 | Consider a linked list implementation of a stack. What is the time complexity of push and pop operations? |
| 50 | GATE CSE 2010 | 2 | Which of the following data structures can be used to implement both a **stack** and a **queue** efficiently? |

---

## 📖 Quick Reference

### Stack — Key Concepts

| Concept | Detail |
|---------|--------|
| **LIFO** | Last In, First Out |
| **Push (array)** | O(1) amortized |
| **Pop (array)** | O(1) |
| **Push (linked list)** | O(1) |
| **Pop (linked list)** | O(1) |
| **Infix → Postfix** | Uses a stack; operators pop based on precedence |
| **Balanced parentheses** | Best solved using a stack |
| **Stack overflow** | Occurs when stack exceeds its capacity (array-based) |
| **Linked list advantage** | Dynamic size, no overflow |

### Linked List — Key Concepts

| Concept | Detail |
|---------|--------|
| **Singly LL** | Each node has `data` + `next` pointer |
| **Doubly LL** | Each node has `data` + `next` + `prev` pointer |
| **Circular LL** | Last node points back to the first node |
| **Insertion at head** | O(1) |
| **Insertion at tail** | O(n) for singly; O(1) if tail pointer maintained |
| **Deletion (with pointer to node)** | O(n) for singly; O(1) for doubly |
| **Search** | O(n) |
| **Reverse (in-place)** | O(n) time, O(1) space using 3 pointers |
| **Sorted insertion (n elements)** | O(n²) worst case |

---

## 🔗 Resources

| Resource | Link |
|----------|------|
| GeeksforGeeks — Stack Notes for GATE | https://www.geeksforgeeks.org/dsa/stack-notes-for-gate-exam/ |
| GeeksforGeeks — Linked List Notes for GATE | https://www.geeksforgeeks.org/dsa/linked-list-notes-for-gate-exam/ |
| ExamSIDE — GATE CSE Stacks & Queues PYQs | https://questions.examside.com/past-years/gate/gate-cse/data-structures/stacks-and-queues |
| ExamSIDE — GATE CSE Linked List PYQs | https://questions.examside.com/past-years/gate/gate-cse/data-structures/linked-list |
| PracticePaper — GATE CSE Linked List PYQs | https://practicepaper.in/gate-cse/link-list |

---

*Questions sourced from official GATE CSE papers (1991–2023). Compiled for exam preparation purposes.*
