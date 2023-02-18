# Leetcode-75-Study-Plan

Looking to ace your coding interviews and land your dream job? Look no further than this comprehensive study plan for practicing with LeetCode! Our GitHub repository is packed with resources to help you master the algorithms and data structures commonly found in coding interviews. With easy-to-follow guides and practice problems, you'll be able to sharpen your skills and build your confidence in no time. Whether you're a beginner or an experienced coder, this study plan is perfect for anyone looking to improve their interview performance. So why wait? Start practicing today and get one step closer to your dream job!

## Level 1
### Day 1 - Prefix Sum
#### Running Sum of 1d Array (easy)
- Time Complexity: O(n)
- Space Complexity: O(1)
```py
class Solution:
    def runningSum(self, nums: List[int]) -> List[int]:
        prefix = 0
        for i in range(len(nums)):
            prefix += nums[i]
            nums[i] = prefix
        return nums
```
#### Find Pivot Index (easy)

### Day 2 - String
- Isomorphic Strings (easy)
- Is Subsequence (easy)
### Day 3 - Linked List
- Merge Two Sorted Lists (easy)
- Reverse Linked List (easy)
### Day 4 - Linked List
- Middle of the Linked List (easy)
- Linked List Cycle II (medium)
### Day 5 - Greedy
- Best Time to Buy and Sell Stock (easy)
- Longest Palindrome (easy)
### Day 6 - Tree
- N-ary Tree Preorder Traversal (easy)
- Binary Tree Level Order Traversal (medium)
### Day 7 - Binary Search
- Binary Search (easy)
- First Bad Version (easy)
### Day 8 - Binary Search Tree
- Validate Binary Search Tree (medium)
- Lowest Common Ancestor of a Binary Search Tree (medium)
### Day 9 - Graph/BFS/DFS
- Flood Fill (medium)
- Number of Islands (medium)
### Day 10 -Dynamic Programming
- Fibonacci Number (easy)
- Climbing Stairs (easy)
### Day 11 -Dynamic Programming
- Min Cost Climbing Stairs (easy)
- Unique Paths (medium)
### Day 12 -Sliding Window/Two Pointer
- Find All Anagrams in a String (medium)
- Longest Repeating Character Replacement (medium)
### Day 13 -Hashmap
- Two Sum (easy)
- Bulls and Cows (medium)
### Day 14 -Stack
- Backspace String Compare (easy)
- Decode String (medium)
### Day 15 -Heap
- Last Stone Weight (easy)
- Top K Frequent Words (medium)

## Level 2

## Level 3
