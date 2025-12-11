# Binary Search Implementation in Python

A clean and simple implementation of the **Binary Search** algorithm in Python.  
This project includes a custom binary search function that also records the **path taken** during the search, making it useful for learning and debugging.

---

## 🚀 Features

- Implemented completely from scratch
- Tracks the values visited during the search
- Returns both the search path and a success/failure message
- Works on any sorted list of numbers
- Beginner-friendly and clean code

---

## 📌 How Binary Search Works

Binary Search follows a divide-and-conquer approach:

1. Look at the middle element of the sorted list  
2. If it matches the target → return its index  
3. If the target is greater → search the right half  
4. If smaller → search the left half  
5. Continue until the target is found or search space becomes empty  

**Time Complexity:** `O(log n)`  
**Space Complexity:** `O(1)`

---

