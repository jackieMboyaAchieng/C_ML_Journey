# 365 Days of C for Machine Learning

This repository outlines a comprehensive 365-day curriculum designed to build a strong foundation in C programming and progressively apply it to machine learning concepts. This journey emphasizes hands-on coding, practical application, and a deep understanding of how C can be leveraged for numerical computing and machine learning algorithms.

---

## Table of Contents

* [Overview](#overview)
* [Phase 1: C Fundamentals (Days 1-120)](#phase-1-c-fundamentals-days-1-120)
    * [Month 1: Introduction to C & Basic Syntax (Days 1-30)](#month-1-introduction-to-c--basic-syntax-days-1-30)
    * [Month 2: Pointers & Memory Management (Days 31-60)](#month-2-pointers--memory-management-days-31-60)
    * [Month 3: File I/O & Advanced Concepts (Days 61-90)](#month-3-file-io--advanced-concepts-days-61-90)
    * [Month 4: Practice & Problem Solving (Days 91-120)](#month-4-practice--problem-solving-days-91-120)
* [Phase 2: C for Numerical Computing & Algorithms (Days 121-240)](#phase-2-c-for-numerical-computing--algorithms-days-121-240)
    * [Month 5: Advanced Data Structures & Algorithms in C (Days 121-150)](#month-5-advanced-data-structures--algorithms-in-c-days-121-150)
    * [Month 6: Introduction to Numerical Computing in C (Days 151-180)](#month-6-introduction-to-numerical-computing-in-c-days-151-180)
    * [Month 7: Bridging to Machine Learning Concepts (Days 181-210)](#month-7-bridging-to-machine-learning-concepts-days-181-210)
    * [Month 8: Performance & Libraries (Days 211-240)](#month-8-performance--libraries-days-211-240)
* [Phase 3: Advanced Topics & ML Focus (Days 241-365)](#phase-3-advanced-topics--ml-focus-days-241-365)
    * [Month 9: Deeper into Machine Learning Algorithms in C (Days 241-270)](#month-9-deeper-into-machine-learning-algorithms-in-c-days-241-270)
    * [Month 10: C Interfacing & Performance Libraries (Days 271-300)](#month-10-c-interfacing--performance-libraries-days-271-300)
    * [Month 11: Case Studies & Specialization (Days 301-330)](#month-11-case-studies--specialization-days-301-330)
    * [Month 12: Consolidation & Future Steps (Days 331-365)](#month-12-consolidation--future-steps-days-331-365)
* [Learning Strategies & Tips](#learning-strategies--tips)
* [Setup and Daily Workflow](#setup-and-daily-workflow)
* [Contribution](#contribution)
* [License](#license)

---

## Overview

This 365-day program is structured into three phases, gradually moving from C fundamentals to advanced machine learning concepts implemented in C. Each day focuses on 1-2 hours of dedicated study and practice. The goal is to develop a robust understanding of C and its application in numerical and machine learning contexts.

---

## Phase 1: C Fundamentals (Days 1-120)

This phase is all about building a solid foundation in C programming.

### Month 1: Introduction to C & Basic Syntax (Days 1-30)

* **Week 1: Getting Started**
    * **Day 1-3:** What is C? Why learn C? Setting up your development environment (GCC compiler, VS Code/Code::Blocks/etc.). Your first "Hello, World!" program.
    * **Day 4-7:** Variables, data types (int, float, char, double, long), constants. Basic input/output (printf, scanf).
* **Week 2: Operators & Control Flow**
    * **Day 8-10:** Arithmetic, relational, logical, bitwise operators. Operator precedence.
    * **Day 11-14:** Conditional statements (if, else if, else, switch).
* **Week 3: Loops**
    * **Day 15-17:** `for` loops.
    * **Day 18-20:** `while` loops, `do-while` loops. `break` and `continue`.
* **Week 4: Functions & Arrays**
    * **Day 21-24:** What are functions? Declaring, defining, calling functions. Function prototypes. Pass by value.
    * **Day 25-27:** One-dimensional arrays. Accessing and manipulating array elements.
    * **Day 28-30:** Multi-dimensional arrays. Strings (character arrays). String manipulation functions (from `string.h`).

### Month 2: Pointers & Memory Management (Days 31-60)

This is where C gets powerful (and sometimes tricky). Mastering pointers is crucial.

* **Week 5: Understanding Pointers**
    * **Day 31-34:** What are pointers? Declaring and initializing pointers. The address-of operator (`&`) and dereference operator (`*`).
    * **Day 35-37:** Pointers and arrays. Pointer arithmetic.
* **Week 6: Functions & Pointers**
    * **Day 38-40:** Pass by reference using pointers. Returning pointers from functions.
    * **Day 41-44:** Pointers to pointers. Array of pointers.
* **Week 7: Dynamic Memory Allocation**
    * **Day 45-47:** `malloc()`, `calloc()`, `realloc()`, `free()`. Understanding heap vs. stack memory.
    * **Day 48-51:** Common pointer errors (dangling pointers, memory leaks, null pointer dereferencing). Best practices for memory management.
* **Week 8: Structures & Unions**
    * **Day 52-55:** Structures. Accessing members. Pointers to structures.
    * **Day 56-58:** Nested structures. Arrays of structures.
    * **Day 59-60:** Unions. Enums. `typedef`.

### Month 3: File I/O & Advanced Concepts (Days 61-90)

* **Week 9: File Handling**
    * **Day 61-64:** Opening and closing files (`fopen`, `fclose`). Reading and writing characters (`fgetc`, `fputc`).
    * **Day 65-67:** Reading and writing strings (`fgets`, `fputs`). Formatted I/O (`fprintf`, `fscanf`).
* **Week 10: Binary File I/O & Command Line Arguments**
    * **Day 68-70:** Reading and writing blocks of data (`fread`, `fwrite`).
    * **Day 71-74:** Command-line arguments (`argc`, `argv`).
* **Week 11: Preprocessor & Macros**
    * **Day 75-78:** Preprocessor directives (`#include`, `#define`, `#undef`, `#ifdef`, `#ifndef`, `#else`, `#endif`). Macros with arguments.
    * **Day 79-81:** Conditional compilation. `__LINE__`, `__FILE__`, `__DATE__`, `__TIME__`.
* **Week 12: Data Structures Introduction (Conceptual)**
    * **Day 82-85:** Introduction to basic data structures: Linked Lists (Singly Linked Lists). How to implement them in C (conceptual and simple code).
    * **Day 86-90:** Introduction to Stacks and Queues (conceptual and simple array-based implementations).

### Month 4: Practice & Problem Solving (Days 91-120)

This month is dedicated to solidifying your understanding through extensive practice.

* **Days 91-120:**
    * Solve problems on platforms like HackerRank, LeetCode (focus on easy/medium C problems), Codeforces.
    * Implement small projects: a simple calculator, a basic text editor, a contact management system using structures and file I/O.
    * Revisit challenging topics. Debug your code meticulously. Understand common error messages.
    * Start thinking about algorithm efficiency (Big O notation, even if superficially at this stage).

---

## Phase 2: C for Numerical Computing & Algorithms (Days 121-240)

Now that you have a strong C foundation, we'll shift towards topics crucial for machine learning.

### Month 5: Advanced Data Structures & Algorithms in C (Days 121-150)

* **Week 17: Linked Lists Deep Dive**
    * **Day 121-124:** Doubly Linked Lists, Circular Linked Lists.
    * **Day 125-127:** Implementing various operations: insertion, deletion, searching, traversal for different linked list types.
* **Week 18: Trees**
    * **Day 128-131:** Introduction to Trees. Binary Trees (concepts). Tree traversals (Inorder, Preorder, Postorder).
    * **Day 132-134:** Implementing a basic Binary Search Tree (insertion, searching).
* **Week 19: Heaps & Hash Tables**
    * **Day 135-138:** Introduction to Heaps (Min-Heap, Max-Heap). Priority Queues using Heaps.
    * **Day 139-141:** Hash Tables (concepts). Collision resolution techniques (chaining, open addressing).
* **Week 20: Graphs**
    * **Day 142-145:** Introduction to Graphs. Graph representations (Adjacency Matrix, Adjacency List).
    * **Day 146-150:** Graph traversals (BFS, DFS). (You don't need to implement complex graph algorithms yet, just understand the basics).

### Month 6: Introduction to Numerical Computing in C (Days 151-180)

This is where you start to bridge C with the math behind ML.

* **Week 21: Basic Linear Algebra in C (Manual Implementation)**
    * **Day 151-154:** Implementing basic vector operations (addition, subtraction, dot product).
    * **Day 155-157:** Implementing basic matrix operations (addition, subtraction, scalar multiplication, matrix-vector multiplication).
* **Week 22: Matrix Multiplication**
    * **Day 158-161:** Implementing matrix-matrix multiplication (the core of many ML algorithms).
    * **Day 162-164:** Discussing computational complexity of matrix multiplication.
* **Week 23: Basic Statistics & Probability in C (Manual Implementation)**
    * **Day 165-168:** Calculating mean, median, mode, standard deviation.
    * **Day 169-171:** Implementing simple probability calculations (e.g., combinations, permutations).
* **Week 24: Introduction to Numerical Optimization (Conceptual)**
    * **Day 172-175:** Understanding gradient descent conceptually. Simple 1D optimization examples (e.g., finding the minimum of a quadratic function).
    * **Day 176-180:** Introduction to calculus concepts relevant to ML (derivatives, partial derivatives) - conceptual understanding, not rigorous math.

### Month 7: Bridging to Machine Learning Concepts (Days 181-210)

* **Week 25: Simple Regression in C**
    * **Day 181-184:** Implement simple linear regression from scratch using direct formulas (normal equation approach).
    * **Day 185-187:** Implement simple linear regression using gradient descent.
* **Week 26: Data Preprocessing in C (Basic)**
    * **Day 188-191:** Implementing functions for data scaling (min-max normalization, standardization).
    * **Day 192-194:** Basic handling of missing values (e.g., mean imputation).
* **Week 27: K-Nearest Neighbors (KNN) in C**
    * **Day 195-198:** Understand the KNN algorithm.
    * **Day 199-201:** Implement KNN classifier from scratch for a small dataset.
* **Week 28: K-Means Clustering in C**
    * **Day 202-205:** Understand the K-Means algorithm.
    * **Day 206-210:** Implement K-Means clustering from scratch for a small dataset.

### Month 8: Performance & Libraries (Days 211-240)

* **Week 29: Profiling & Optimization**
    * **Day 211-214:** Introduction to profiling tools (e.g., `gprof` or `valgrind` for memory issues). Identifying bottlenecks.
    * **Day 215-217:** Basic optimization techniques (e.g., loop unrolling, cache-friendly code).
* **Week 30: Introduction to BLAS/LAPACK (Conceptual/Usage)**
    * **Day 218-221:** Understand what BLAS (Basic Linear Algebra Subprograms) and LAPACK (Linear Algebra Package) are. Why they are used.
    * **Day 222-224:** How to link with and use simple BLAS/LAPACK routines (e.g., matrix multiplication, solving linear systems). You won't implement them, but use them.
* **Week 31: OpenMP for Parallelism (Introduction)**
    * **Day 225-228:** Introduction to parallel programming concepts.
    * **Day 229-231:** Using OpenMP directives for basic loop parallelization in C (e.g., for matrix operations).
* **Week 32: Project & Review**
    * **Day 232-240:** Work on a slightly larger project: e.g., a more robust linear regression implementation, or a basic neural network with one hidden layer using only C and manual matrix operations. Review all topics from Phase 2.

---

## Phase 3: Advanced Topics & ML Focus (Days 241-365)

This phase will deepen your understanding and prepare you for applying C to more complex ML scenarios.

### Month 9: Deeper into Machine Learning Algorithms in C (Days 241-270)

* **Week 33: Logistic Regression in C**
    * **Day 241-244:** Understand logistic regression for binary classification.
    * **Day 245-247:** Implement logistic regression from scratch using gradient descent.
* **Week 34: Support Vector Machines (SVM) - Conceptual**
    * **Day 248-251:** Understand the core concepts of SVMs (hyperplane, margins, kernels). Implementation is very complex, so focus on conceptual understanding.
    * **Day 252-254:** Briefly explore how SVMs might be optimized or used in C environments (e.g., using LibSVM if you were to).
* **Week 35: Neural Networks - Multi-Layer Perceptron (MLP) in C**
    * **Day 255-258:** Understand the architecture of a simple MLP. Forward propagation.
    * **Day 259-261:** Backpropagation algorithm (the most challenging part).
* **Week 36: Building a Small Neural Network**
    * **Day 262-270:** Implement a basic feedforward neural network with one hidden layer from scratch in C for a simple classification task (e.g., XOR, MNIST subset). Focus on understanding the forward and backward passes.

### Month 10: C Interfacing & Performance Libraries (Days 271-300)

* **Week 37: Integrating C with Python (Conceptual)**
    * **Day 271-274:** Understand why you might want to call C code from Python (performance).
    * **Day 275-277:** Introduction to `ctypes` or Cython (conceptual understanding of how they bridge C and Python). No deep dive into implementation, just awareness.
* **Week 38: Introduction to GPGPU with CUDA (Conceptual)**
    * **Day 278-281:** What is GPGPU? Why CUDA? Basic CUDA architecture (cores, blocks, grids).
    * **Day 282-284:** Simple CUDA kernel example (e.g., vector addition). Requires an NVIDIA GPU.
* **Week 39: Understanding numpy's C underpinnings (Conceptual)**
    * **Day 285-288:** How numpy leverages C and Fortran for performance. The `ndarray` structure.
    * **Day 289-291:** Briefly look into `scipy`'s reliance on optimized numerical libraries.
* **Week 40: Review & Small Project**
    * **Day 292-300:** Review all advanced C topics. Work on a project that combines numerical methods and C, possibly optimizing a part of a previous ML algorithm using OpenMP or exploring a simple CUDA example.

### Month 11: Case Studies & Specialization (Days 301-330)

* **Week 41: Embedded ML (Conceptual)**
    * **Day 301-304:** Why C is crucial for ML on microcontrollers and edge devices.
    * **Day 305-307:** Look into libraries like TensorFlow Lite for Microcontrollers (how C is used).
* **Week 42: High-Performance Computing (HPC) for ML (Conceptual)**
    * **Day 308-311:** Role of C/C++ in HPC clusters for large-scale ML training. MPI (Message Passing Interface) for distributed computing (conceptual).
    * **Day 312-314:** Overview of optimized numerical libraries in HPC contexts.
* **Week 43: Reading Research Papers & Implementing (Simplified)**
    * **Day 315-318:** Find a simple ML research paper (e.g., an early paper on perceptrons or a specific optimization algorithm).
    * **Day 319-321:** Attempt to implement a very simplified part of the paper's algorithm in C. Focus on understanding the mathematical formulation and translating it to code.
* **Week 44: Error Handling & Robustness**
    * **Day 322-325:** Advanced error handling in C (return codes, `errno`, custom error types).
    * **Day 326-330:** Defensive programming practices. Writing robust and maintainable C code.

### Month 12: Consolidation & Future Steps (Days 331-365)

* **Days 331-340: Major Project**
    * Choose a more substantial machine learning algorithm (e.g., Decision Tree, Random Forest, or a more complex Neural Network architecture) and implement a simplified version from scratch in C.
    * Focus on modularity, clear code, and thorough testing.
    * Consider adding performance metrics and comparing with Python implementations (if possible).
* **Days 341-350: Deep Dive into Specific Areas**
    * Pick one area that excites you most (e.g., embedded ML, numerical optimization, specific data structures, or performance tuning) and spend time exploring it further.
    * Read more articles, watch advanced tutorials, or try to implement a more complex component related to your chosen area.
* **Days 351-360: Review & Portfolio Building**
    * Review all the C concepts and ML algorithms you've learned.
    * Organize your projects on GitHub. Write clear READMEs for each project, explaining what it does, how to compile, and its purpose.
    * Prepare to explain your C ML projects.
* **Days 361-365: What's Next?**
    * Consider learning C++ for ML (which offers more abstraction and libraries like Eigen, OpenCV).
    * Explore specialized ML frameworks in C/C++ (e.g., LibSVM, Shogun).
    * Dive deeper into specific machine learning research areas where C is relevant.

---

## Learning Strategies & Tips

* **Consistency is Key:** Dedicate at least 1-2 hours every day (or most days) to learning and coding. Even 30 minutes of focused effort is better than nothing.
* **Hands-on Practice:** Don't just read. Write code, compile it, run it, debug it. This is the most effective way to learn.
* **Break Down Problems:** When faced with a complex task, break it into smaller, manageable sub-problems.
* **Understand, Don't Just Memorize:** Focus on understanding why things work the way they do, especially with pointers and memory management.
* **Utilize Resources:**
    * **Books:** "The C Programming Language" by Kernighan and Ritchie (K&R) is the classic. "C in a Nutshell" is also great.
    * **Online Tutorials/Courses:** GeeksforGeeks, Tutorialspoint, freeCodeCamp, Udemy, Coursera (look for C programming courses).
    * **YouTube Channels:** TheChernoProject (for C++ but many concepts apply to C foundations), freeCodeCamp, etc.
* **Debugging is Your Friend:** Learn to use a debugger (GDB is standard for C). It's an invaluable skill for understanding your code's execution flow and finding errors.
* **Join Communities:** Online forums (Stack Overflow, Reddit's r/C_Programming, r/learnprogramming), Discord servers. Don't be afraid to ask questions.
* **Take Notes:** Summarize key concepts, syntax, and common pitfalls.
* **Regular Review:** Periodically go back and review concepts you've learned. Repetition helps solidify knowledge.
* **Balance Theory and Practice:** While understanding the math behind ML is important, for the C side, focus on implementing the algorithms efficiently.
* **Don't Get Discouraged:** C can be challenging, especially pointers. It's normal to struggle. Persistence is crucial.
* **Health and Well-being:** Don't burn out. Take breaks, get enough sleep, and maintain a healthy lifestyle.

---

## Setup and Daily Workflow

* **Operating System:** We recommend using a **Linux kernel system** for practicality, as C development tools are natively well-supported.
* **Development Environment:** Set up your preferred C IDE or text editor (e.g., VS Code with C/C++ extensions, Code::Blocks, Vim, Emacs) and ensure you have the **GCC compiler** installed.
* **Version Control:** Utilize **Git and GitHub** from Day 1.
    * Create a new repository for this 365-day challenge.
    * **Push daily** to track your progress and build a consistent commit history. This also serves as your portfolio.
    * Organize your daily work into clearly named directories or files (e.g., `day001_hello_world/`, `day002_variables/`).

---

## Contribution

This curriculum is a guide. Feel free to adapt it to your learning style and pace. If you have suggestions for improvements, additional resources, or find any errors, please open an issue or submit a pull request.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

