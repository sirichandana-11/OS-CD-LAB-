# 💻 Operating Systems & Compiler Design Lab

A collection of **C programs and Lex programs** implemented as part of the **R23CSE-PC3104 – Operating Systems & Compiler Design Lab**.

This repository contains practical implementations of **CPU scheduling, deadlock handling, memory management, paging, page replacement, system calls, lexical analysis, parsing techniques, and code optimization**.

---

## 📚 Course Information

| Details          | Information                             |
| ---------------- | --------------------------------------- |
| **Subject Code** | R23CSE-PC3104                           |
| **Subject**      | Operating Systems & Compiler Design Lab |
| **Language**     | C                                       |
| **Tools**        | GCC, Flex/Lex                           |
| **IDE**          | VS Code / Code::Blocks                  |
| **Platform**     | Windows / Linux                         |

---

## 🎯 Course Objectives

* Simulate various **CPU scheduling algorithms**
* Implement **deadlock avoidance and detection**
* Understand **memory management techniques**
* Implement **paging and page replacement algorithms**
* Understand and implement **lexical analyzers**
* Implement **top-down and bottom-up parsers**
* Work with **Lex/Flex tools**
* Understand basic **code optimization techniques**

---

# 🖥️ Operating Systems

### 1. CPU Scheduling Algorithms

| Program         | Description                       |
| --------------- | --------------------------------- |
| **FCFS**        | First Come First Serve scheduling |
| **SJF**         | Shortest Job First scheduling     |
| **Priority**    | Priority-based CPU scheduling     |
| **Round Robin** | Time-quantum based scheduling     |

### 2. Deadlock Handling

* **Banker's Algorithm** – Deadlock avoidance
* **Deadlock Detection Algorithm**

### 3. Memory Management

* **MFT** – Multiprogramming with a Fixed number of Tasks
* **MVT** – Multiprogramming with a Variable number of Tasks

### 4. Paging

* Paging technique implementation

### 5. Page Replacement Algorithms

* **FIFO** – First In First Out
* **LRU** – Least Recently Used
* **Optimal Page Replacement**

### 6. System Calls

Implementation and demonstration of:

* `fork()`
* `wait()`
* `exec()`
* `exit()`

---

# ⚙️ Compiler Design

### 7. Lexical Analysis

Implementation of a lexical analyzer to identify:

* Keywords
* Identifiers
* Constants
* Operators
* Punctuation/Special symbols

### 8. FIRST & FOLLOW

* Calculation of **FIRST sets**
* Calculation of **FOLLOW sets**

### 9. LL(1) Parser

Construction and implementation of a **top-down LL(1) parser** for a given grammar.

### 10. SLR Parser

Implementation of a **bottom-up SLR parser** for a given language/grammar.

### 11. Lex/Flex

Implementation of a lexical analyzer using **Lex/Flex tools**.

### 12. Code Optimization

Implementation of basic compiler optimization techniques:

* **Loop Unrolling**
* **Strength Reduction**

---

## 📂 Repository Structure

```text
OS-CD-Lab/
│
├── OS/
│   ├── 01_CPU_Scheduling/
│   │   ├── FCFS.c
│   │   ├── SJF.c
│   │   ├── Priority.c
│   │   └── RoundRobin.c
│   │
│   ├── 02_Bankers_Algorithm/
│   │   └── Bankers.c
│   │
│   ├── 03_Deadlock_Detection/
│   │   └── DeadlockDetection.c
│   │
│   ├── 04_Memory_Management/
│   │   ├── MFT.c
│   │   └── MVT.c
│   │
│   ├── 05_Paging/
│   │   └── Paging.c
│   │
│   ├── 06_Page_Replacement/
│   │   ├── FIFO.c
│   │   ├── LRU.c
│   │   └── Optimal.c
│   │
│   └── 07_System_Calls/
│       └── SystemCalls.c
│
├── CD/
│   ├── 08_Lexical_Analyzer/
│   │   └── LexicalAnalyzer.c
│   │
│   ├── 09_First_Follow/
│   │   └── FirstFollow.c
│   │
│   ├── 10_LL1_Parser/
│   │   └── LL1Parser.c
│   │
│   ├── 11_SLR_Parser/
│   │   └── SLRParser.c
│   │
│   ├── 12_Lex_Tool/
│   │   └── lexer.l
│   │
│   ├── 13_Loop_Unrolling/
│   │   └── LoopUnrolling.c
│   │
│   └── 14_Strength_Reduction/
│       └── StrengthReduction.c
│
└── README.md
```

---

## 🛠️ Technologies Used

* **C** – Operating Systems and Compiler Design implementations
* **GCC** – C compiler
* **Lex/Flex** – Lexical analyzer implementation
* **VS Code** – Development environment
* **Code::Blocks** – Alternative C IDE
* **Linux / Windows** – Supported platforms

---

## ▶️ How to Run C Programs

### 1. Clone the repository

```bash
git clone https://github.com/your-username/OS-CD-Lab.git
cd OS-CD-Lab
```

### 2. Compile a C program

```bash
gcc FCFS.c -o FCFS
```

### 3. Run the program

**Windows:**

```bash
FCFS.exe
```

**Linux:**

```bash
./FCFS
```

---

## 🔧 Running Lex/Flex Programs

For Linux:

```bash
flex lexer.l
gcc lex.yy.c -o lexer
./lexer
```

---

## 🎓 Course Outcomes

After completing these programs, the laboratory provides practical understanding of:

* Process scheduling
* Deadlock avoidance and detection
* Memory management
* Paging and page replacement
* Linux system calls
* Lexical analysis
* FIRST and FOLLOW computation
* LL(1) parsing
* SLR parsing
* Lex/Flex
* Compiler code optimization

---

## 📖 References

1. **Abraham Silberschatz, Peter B. Galvin & Greg Gagne** – *Operating System Concepts*, 7th Edition, Wiley.
2. **Leland L. Beck** – *System Software: An Introduction to Systems Programming*, 3rd Edition.
3. **Alfred V. Aho, Monica S. Lam, Ravi Sethi & Jeffrey D. Ullman** – *Compilers: Principles, Techniques, and Tools*, 2nd Edition.
4. **Brian W. Kernighan & Dennis M. Ritchie** – *The C Programming Language*.

---

## 👩‍💻 Author

**Siri Chandana**

B.Tech – Computer Science Engineering
