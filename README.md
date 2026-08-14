Search Insert Position

📌 Problem

Given a sorted array of distinct integers and a target value, return the index if the target is found.

If the target is not found, return the index where it would be inserted in order.

💡 Example

Input: nums = [1,3,5,6]
Target: 5

Output: 2

Input: nums = [1,3,5,6]
Target: 2

Output: 1

💻 Language

Java

📂 File

"SearchInsertPosition.java"

🧠 Approach

1. Use binary search.
2. Set "left" to the first index and "right" to the last index.
3. Find the middle element.
4. If the target is greater, search the right half.
5. Otherwise, search the left half.
6. If the target is not found, "left" gives the correct insertion position.

⏱️ Complexity

- Time Complexity: O(log n)
- Space Complexity: O(1)

🎯 Goal

To practice binary search and improve problem-solving skills using Java.

👨‍💻 Author

K. Leela Sri# Search--Insert--Position