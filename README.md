# Searching-Algorithms
# AIM
To study, understand, and implement various searching algorithms in C++, analyze their working principles, compare their efficiency, and conclude the best suitable algorithm under different scenarios.
# OBJECTIVES
- To implement searching algorithms in C++.
- To understand linear and binary searching techniques.
- To analyze time complexity and space complexity.
- To compare efficiency of searching algorithms.
- To conclude which algorithm works best under given conditions.
# THEORY
Searching algorithms are fundamental techniques used to locate a specific element within a collection of data such as arrays, linked lists, or databases.

There are two broad categories of searching algorithms:

- 1. Linear Search (Sequential Search):

- Scans each element of the list sequentially.
- Simple but inefficient for large datasets.
- Time Complexity: O(n)
- Space Complexity: O(1)
- Binary Search:

- 2. Works only on sorted arrays.
- Repeatedly divides the search interval in half.
- Efficient compared to Linear Search.
- Time Complexity: O(log n)
- Space Complexity: O(1) (iterative), O(log n) (recursive)
- Interpolation Search:

- 3. Improves Binary Search by predicting the position using the formula based on the key.
- Works well for uniformly distributed data.
- Time Complexity: O(log log n) (best), O(n) (worst).
- Space Complexity: O(1).
- Exponential Search:

- 4. Useful for unbounded or infinite lists.
- Involves two steps: (a) Find range by repeated doubling. (b) Apply Binary Search within the found range.
- Time Complexity: O(log n)
- Space Complexity: O(1).
- Jump Search:

- 5. Searches elements by jumping ahead fixed steps.
- Then performs linear search in identified block.
- Best step size = √n.
- Time Complexity: O(√n)
# ALGORITHM
- Example: Binary Search Algorithm

- Step 1: Start
- Step 2: Input array (sorted) and the key element.
- Step 3: Initialize low = 0, high = n-1.
- Step 4: Repeat until low <= high:
- a. Find mid = (low + high)/2
- b. If arr[mid] == key → return position.
- c. If arr[mid] > key → high = mid - 1.
- d. Else → low = mid + 1.
- Step 5: If not found, return "Element not found".
- Step 6: Stop.
# CONCLUSION
- 1.Linear Search is simple but inefficient for large data.
- 2.Binary Search is efficient and widely used on sorted data.
- 3.Jump, Interpolation, and Exponential Searches improve efficiency in specific cases.
- 4.Overall, Binary Search remains the most reliable and commonly used searching algorithm due to its logarithmic complexity.


Space Complexity: O(1).

