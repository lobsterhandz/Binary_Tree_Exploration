# Tree Traversal Practice with Fibonacci, Spiral, and Fractal Extensions

## Overview
This project explores **tree traversal algorithms** implemented in Python, with standard traversals and **creative extensions**. It features **in-order**, **pre-order**, **post-order** traversals, and introduces **Fibonacci-based traversal**, **spiral traversal**, and **fractal traversal** for added complexity and fun.

---

## Features
- **Standard Traversals:**
  - In-order (Left, Root, Right)
  - Pre-order (Root, Left, Right)
  - Post-order (Left, Right, Root)
- **Fibonacci Traversal:** Assigns Fibonacci numbers to nodes based on levels in the tree hierarchy.
- **Spiral Traversal:** Traverses levels in a zig-zag pattern.
- **Fractal Traversal:** Generates patterns based on recursive depths, simulating fractal-like structures.
- **Dynamic Tree Creation:** Supports binary trees with nested structures.

---

## File Structure
```
Tree_Traversal_Project/
    ├── tree_traversal.py        # Core code for traversals
    ├── README.md                # Documentation
```

---

## Prerequisites
- Python 3.8 or later

---

## Installation
1. **Clone the Repository:**
```bash
git clone <repository_url>
cd Tree_Traversal_Project
```

2. **Run the Script:**
```bash
python tree_traversal.py
```

---

## Tree Structure
The binary tree used for traversal:
```
                  50
           ┌─────┴─────┐
          30           70
     ┌────┴────┐    ┌────┴────┐
    40       20   60         80
```

---

## Traversal Results
### **In-order Traversal:**
- Output: `[40, 30, 20, 50, 60, 70, 80]`

### **Pre-order Traversal:**
- Output: `[50, 30, 40, 20, 70, 60, 80]`

### **Post-order Traversal:**
- Output: `[40, 20, 30, 60, 80, 70, 50]`

### **Fibonacci Traversal:**
- Output: `[(50, 0), (30, 1), (40, 1), (20, 2), (70, 1), (60, 2), (80, 3)]`
- **Explanation:** Fibonacci values are assigned based on the level in the hierarchy.

### **Spiral Traversal:**
- Output: `[50, 70, 30, 40, 20, 60, 80]`
- **Explanation:** Traverses the levels in zig-zag order, alternating left-to-right and right-to-left.

### **Fractal Traversal:**
- Output: `[(50, 0), (30, 1), (40, 2), (20, 2), (70, 1), (60, 2), (80, 2)]`
- **Explanation:** Recursive traversal generates fractal-like patterns, representing hierarchical depth levels.

---

## Complexity Analysis
1. **Standard Traversals:**
   - **Time Complexity:** O(n) - Visits each node once.
   - **Space Complexity:** O(h) - Stack usage for recursion, where **h** is the height of the tree.

2. **Fibonacci Traversal:**
   - **Time Complexity:** O(n * F(level)), where F(level) computes Fibonacci for each level.
   - **Space Complexity:** O(h) due to recursion depth.

3. **Spiral Traversal:**
   - **Time Complexity:** O(n).
   - **Space Complexity:** O(n) for storing levels.

4. **Fractal Traversal:**
   - **Time Complexity:** O(n).
   - **Space Complexity:** O(d) where **d** is the recursion depth.

---

## Future Improvements
- **Balanced Tree Generation:** Add functions to create balanced binary trees.
- **Visualization Tools:** Integrate visualizations for traversal paths.
- **Dynamic Input Handling:** Accept trees as JSON inputs.
- **Interactive Traversal Demo:** Provide step-by-step visualizations for each traversal.

---

## Author
- **Jose Murillo**

---

## License
This project is licensed under the **MIT License**.

