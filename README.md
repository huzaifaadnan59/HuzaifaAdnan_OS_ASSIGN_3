# Parallel Merge Sort Using Threads

## Overview
This C++ program demonstrates the implementation of the Merge Sort algorithm using multithreading. It divides the input array into smaller subarrays, sorts them in parallel using threads, and then merges them into a single sorted array. This approach showcases the potential for performance improvement in sorting large datasets using parallel processing.

## Features
- Multithreading: Utilizes multiple threads to sort subarrays concurrently.
- Merge Function: Combines two sorted subarrays into a single sorted array.
- Dynamic Input: Allows the user to input an array of any size for sorting.

## Prerequisites
- C++ Compiler: Ensure 'g++' is installed with C++11 or higher standard support.
- Multithreading Support: The program uses the standard '<thread>' library.

## How to Run
1. Clone the repository or download the file 'parallel_merge_sort.cpp':
```bash
git clone <repository-url>
cd <repository-directory>
```
2. Compile the code using 'g++' with threading support:
```bash
g++ -std=c++11 -o parallel_merge_sort parallel_merge_sort.cpp -pthread
```
3. Execute the program:
```bash
./parallel_merge_sort
```
4. Enter the size of the array and its elements when prompted.

## Sample Output
```plaintext
Enter the size of the array: 5
Enter the elements of the array: 10 2 8 6 4
Sorted array: 2 4 6 8 10
