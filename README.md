## 💻 Computer Science Fundamentals: Concepts & Comparisons

This document provides a concise overview of core concepts in Computer Science, focusing on **Programming, Data Structures, Algorithms, and Object-Oriented Programming (OOP) Principles**.

***

### Core Concepts

#### 1. Programming
**Definition:** The process of designing and writing computer programs (sets of instructions) to solve problems or automate tasks.
* **Paradigms:**
    * **Procedural:** Uses procedures/routines (e.g., C).
    * **Object-Oriented (OOP):** Organizes code into objects/classes (e.g., C++, Java).
    * **Functional:** Emphasizes pure functions and immutability (e.g., Haskell, Scala).
    * **Logic:** Based on formal logic (e.g., Prolog).
* **Usage:** Writing applications, websites, operating systems, data processing scripts.

#### 2. Variable
**Definition:** A named storage that holds data values which can change during program execution.
* **Types:** **Local** (inside functions), **Global** (program-wide), **Static** (retains value between function calls).
* **Example (Python):** `age = 25` (integer variable).

#### 3. Data Types
**Definition:** Specifies the type of data a variable can hold, enforcing proper usage and optimizing memory.
* **Common Types:**
    * **Primitive:** `int`, `float`, `char`, `bool`.
    * **Composite:** `array`, `struct`, `tuple`.
    * **Abstract:** `class`, `interface`.
* **Example (C):** `int age = 30;` // integer type

#### 4. Array
**Definition:** A collection of elements stored at contiguous memory locations, all of the same data type.
* **Types:** **One-dimensional** (list) and **Multi-dimensional** (matrices).
* **Advantage:** Fast access via **index**.
* **Example (C):** `int numbers[5] = {1, 2, 3, 4, 5};`

#### 5. String
**Definition:** A sequence of characters used to represent text.
* **Types:** **Immutable** (e.g., Python) or **Mutable** (e.g., C++ `std::string`).
* **Usage:** Essential for user input, output, and file processing.

#### 6. Pointer
**Definition:** A variable that stores the **memory address** of another variable.
* **Usage:** Dynamic memory management, efficient handling of arrays and complex data structures (C/C++).
* **Example (C):** `int *ptr = &x;` // `ptr` stores address of `x`.

#### 7. Variadic Functions
**Definition:** Functions that accept a **variable number of arguments**.
* **Advantage:** Flexibility in input parameters; avoids writing multiple overloaded functions.
* **Usage:** Standard functions like `printf()` in C.

#### 8. Loop
**Definition:** A control structure that repeats a block of code while a condition is true.
* **Types:** **For**, **While**, **Do-while**.
* **Advantage:** Automates repetitive tasks and reduces code duplication.

#### 9. Constructor
**Definition:** A special function in a class that **initializes objects** when created.
* **Usage:** Automatically sets up the object's initial state in OOP languages (C++, Java).

#### 10. Stack (Data Structure)
**Definition:** A linear data structure following **Last-In-First-Out (LIFO)**.
* **Operations:** **Push** (add), **Pop** (remove), **Peek** (view top).
* **Usage:** Recursion management, undo mechanisms, expression evaluation.

#### 11. Queue (Data Structure)
**Definition:** A linear data structure following **First-In-First-Out (FIFO)**.
* **Operations:** **Enqueue** (add), **Dequeue** (remove).
* **Usage:** Task scheduling (CPU), buffering, print spooling.

***

### Object-Oriented Programming (OOP)

#### 12. Class
**Definition:** A **blueprint** defining data members (variables) and member functions (methods).
* **Advantage:** Organizes code; supports OOP principles.

#### 13. Object
**Definition:** An **instance** of a class with actual values (attributes) and behavior.
* **Usage:** Used in OOP to model real-world or conceptual entities.

#### 14. Abstraction
**Definition:** **Hiding complex implementation details** while exposing only necessary features.
* **Example:** Using a remote control hides the internal electronics of a TV.

#### 15. Encapsulation
**Definition:** **Wrapping data and methods into a single unit** (class) and restricting access using access modifiers.
* **Advantage:** Protects the internal object state from unauthorized modification.

#### 16. Polymorphism
**Definition:** The ability of **different objects to respond to the same method call in different ways**.
* **Types:** **Compile-time** (method overloading) and **Runtime** (method overriding).
* **Advantage:** Flexibility and extensibility.

***

### Algorithms

#### 17. Greedy Search Algorithm
**Definition:** An algorithm that makes the **locally optimal choice at each step** hoping to find a global optimum.
* **Advantages:** Simple and fast.
* **Usage:** Coin change problem, minimum spanning trees (Prim's, Kruskal's).

***

### Concept Comparisons

| Concept | Definition | Key Difference / Purpose |
| :--- | :--- | :--- |
| **Programming** | Writing instructions for computers. | Create software & solve problems. |
| **Variable** | Named storage location for data. | Store and manipulate data during execution. |
| **Data Types** | Defines the type of data a variable can hold. | Ensure correct interpretation and operations on data. |
|---|---|---|
| **Array** | Collection of elements of same type. | General purpose collection (numbers, chars, objects). |
| **String** | Sequence of characters. | Specialized array for textual data only. |
|---|---|---|
| **Variable** | Holds actual data value. | Stores the data value directly. |
| **Pointer** | Holds memory address of a variable. | Stores **location** of data, not data itself. |
|---|---|---|
| **Stack** | LIFO data structure (Last In, First Out). | Elements removed in **reverse order** of insertion. |
| **Queue** | FIFO data structure (First In, First Out). | Elements removed in the **order** of insertion. |
|---|---|---|
| **Class** | Blueprint/Template for objects. | Abstract definition of data and behavior. |
| **Object** | Instance of a class. | Concrete entity created from the class. |
|---|---|---|
| **Abstraction** | Hiding complex details, showing only essentials. | Focuses on **what** an object does. |
| **Encapsulation** | Bundling data & methods and restricting access. | Focuses on **how** the data is protected and accessed. |
|---|---|---|
| **Greedy Algorithm** | Makes locally optimal choices hoping for a global optimum. | Chooses immediate best choice **without backtracking**. |
| **Other Algorithms** | May use exhaustive or backtracking approaches. | May explore multiple paths, not just locally optimal. |
