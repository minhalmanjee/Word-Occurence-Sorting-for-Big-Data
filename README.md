# Parallel and Distributed Computing Project

## Author
**Muhammad Minhal**  
**Roll No: 20K-0467**  
**Course: Parallel and Distributed Computing (PDC)**  
**Institution: FAST NUCES, Karachi**

---

## Overview

This project demonstrates practical applications of parallel and distributed computing using **MPI** (Message Passing Interface) and **Docker**. It covers:

- MPI code execution within Docker containers  
- Parallel approximation of Pi using numerical integration  
- Distributed Merge Sort using MPI  
- Trie-based Parallel Word Count using OpenMP  

---

## Technologies Used

- C/C++
- MPI (OpenMPI)
- OpenMP
- Docker
- Linux (Ubuntu)
- GCC

---

## Components

### 🐳 MPI with Docker

Implemented and tested MPI programs inside Docker containers to showcase containerization benefits in distributed systems.

> **Why Docker?**  
> Docker ensures a consistent environment for development and deployment. It offers OS-level virtualization, making it lightweight compared to traditional VMs.

---

### 🧮 Pi Estimation using Numerical Integration (MPI)

Calculated the value of π using parallel numerical integration.

**Run:**
```bash
mpirun -n <num_processes> ./pi_mpi
