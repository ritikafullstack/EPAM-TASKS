# Task 1: Instruction Reordering & Memory Barriers

## Overview
This task explores how compilers and modern CPUs reorder instructions for performance, and how improper synchronization can cause data races in multithreaded applications.

## Topics Covered
- CPU instruction reordering and out-of-order execution
- Multithreading and data races
- Store buffers and cache coherence
- Invalidate queues
- Memory fences and memory barriers
- Acquire-release vs. sequential consistency
- x86 vs. ARM memory ordering
- C++ atomic operations and synchronization

## Objective
Understand how memory ordering affects concurrent execution and how synchronization mechanisms help ensure data consistency and thread safety.

## Key Takeaway
Correct synchronization is essential for reliable multithreaded programming. Memory barriers establish the ordering guarantees needed for safe communication between threads.
