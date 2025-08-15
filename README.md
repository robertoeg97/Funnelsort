# Funnel Sort: Cache-Oblivious Sorting Algorithm

Due to academic integrity, the project source code and detailed report are private. This public summary outlines the core objectives, challenges, and achievements. Code/reports cannot be shared, even on request.

## Project Overview

This project implements the *funnel sort* algorithm, a cache-oblivious sorting technique designed to minimize cache misses and optimize memory hierarchy usage. Funnel sort is notable for its theoretical efficiency on modern hardware, where memory access patterns significantly impact performance.

## Problem Statement

Traditional sorting algorithms like quicksort are not optimized for hierarchical memory systems, leading to suboptimal cache performance on large datasets. The goal of this project was to implement a sorting algorithm that is *cache-oblivious*—that is, it achieves efficient cache utilization without explicit knowledge of cache size or block size parameters.

## High-Level Approach

- **Algorithm:** Implemented the recursive funnel sort algorithm, which divides the input into subarrays, recursively sorts them, and merges them using a hierarchy of *k-funnels*.
- **Performance Focus:** Emphasized reducing data cache misses, especially for large input sizes that exceed typical cache capacities.
- **Testing:** Compared the implementation's performance and cache behavior against the standard C library quicksort, using provided benchmarking scripts and tools.

## My Contributions

- Designed and implemented the full funnel sort algorithm in C, including custom buffer management and recursive merging structures.
- Analyzed and optimized memory access patterns to reduce cache misses.
- Benchmarked and validated correctness and performance using provided test harnesses and custom scripts.

## Learning Outcomes

- Gained hands-on experience with cache-oblivious algorithm design and implementation.
- Developed a deeper understanding of memory hierarchies and their impact on algorithmic performance.
- Strengthened skills in low-level systems programming, performance profiling, and algorithmic optimization.

## Results

- Successfully implemented a cache-oblivious sorting algorithm that demonstrated significantly fewer cache misses than quicksort on large datasets.
- Achieved correct sorting results and competitive performance metrics on provided benchmarks.
