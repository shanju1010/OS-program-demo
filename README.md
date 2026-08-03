# OS Program Demo

A collection of Operating System laboratory programs implemented in C. This repository contains implementations of important OS concepts such as CPU scheduling algorithms and process synchronization techniques.

## 📌 Topics Covered

### CPU Scheduling Algorithms

### 1. First Come First Serve (FCFS)

* Non-preemptive scheduling algorithm
* Executes processes according to arrival order
* Calculates:

  * Waiting Time
  * Turnaround Time
  * Average Waiting Time
  * Average Turnaround Time

### 2. Shortest Job First (SJF)

* Non-preemptive scheduling algorithm
* Selects the process with the shortest burst time first
* Calculates scheduling performance metrics

### 3. Round Robin Scheduling

* Preemptive scheduling algorithm
* Uses time quantum for process execution
* Implements queue-based CPU scheduling

### 4. Priority Scheduling

* Executes processes based on priority value
* Supports process prioritization and scheduling calculations

## 🔄 Process Synchronization

### Producer Consumer Problem Using Semaphores

Implementation using:

* POSIX Threads (`pthread`)
* Semaphores (`sem_t`)
* Mutex Locks

Concepts demonstrated:

* Critical section handling
* Mutual exclusion
* Synchronization between producer and consumer
* Buffer management

## 📂 Repository Structure

```
OS-program-demo/
│
├── CPU Scheduling/
│   ├── fcfs.c
│   ├── sjf.c
│   ├── round_robin.c
│   └── priority.c
│
└── Synchronization/
    └── producer-consumer-semaphores.c
```

## ⚙️ Compilation and Execution

### CPU Scheduling Programs

Compile:

```bash
gcc filename.c -o output
```

Run:

```bash
./output
```

### Producer Consumer Program

Compile with pthread support:

```bash
gcc producer-consumer-semaphores.c -o producer -pthread
```

Run:

```bash
./producer
```

## 🛠️ Technologies Used

* Programming Language: C
* Operating System Concepts:

  * CPU Scheduling
  * Threads
  * Semaphores
  * Mutex Synchronization

## 🎯 Purpose

This repository is created for learning and demonstrating Operating System concepts through practical implementations.

## 👨‍💻 Author

**Shanjayram**

GitHub:
https://github.com/shanju1010
