# corejava
Core Java Code Snippets 


# Array Operations

## Introduction
This document provides an overview of various operations that can be performed on arrays, both sorted and unsorted. The operations include insertion, deletion, searching, rotation, and various advanced algorithms for specific tasks.

## Table of Contents
1. [Insert in an Unsorted Array](#insert-in-an-unsorted-array)
2. [Delete in an Unsorted Array](#delete-in-an-unsorted-array)
3. [Search in an Unsorted Array](#search-in-an-unsorted-array)
4. [Insert in a Sorted Array](#insert-in-a-sorted-array)
5. [Delete in a Sorted Array](#delete-in-a-sorted-array)
6. [Search in a Sorted Array](#search-in-a-sorted-array)
7. [Reverse an Array](#reverse-an-array)
8. [Leaders in an Array](#leaders-in-an-array)
9. [Majority Element](#majority-element)
10. [Find the Number Occurring Odd Number of Times](#find-the-number-occurring-odd-number-of-times)
11. [Largest Sum Contiguous Subarray](#largest-sum-contiguous-subarray)
12. [Find the Missing Number](#find-the-missing-number)
13. [Search an Element in a Sorted and Pivoted Array](#search-an-element-in-a-sorted-and-pivoted-array)
14. [Merge an Array of Size n into Another Array of Size m+n](#merge-an-array-of-size-n-into-another-array-of-size-m+n)
15. [Median of Two Sorted Arrays](#median-of-two-sorted-arrays)
16. [Program for Array Rotation](#program-for-array-rotation)
17. [Reversal Algorithm for Array Rotation](#reversal-algorithm-for-array-rotation)
18. [Block Swap Algorithm for Array Rotation](#block-swap-algorithm-for-array-rotation)
19. [Maximum Sum Such That No Two Elements Are Adjacent](#maximum-sum-such-that-no-two-elements-are-adjacent)
20. [Sort Elements by Frequency | Set 1](#sort-elements-by-frequency--set-1)
21. [Count Inversions in an Array](#count-inversions-in-an-array)

## 1. Insert in an Unsorted Array

- **Description**: In an unsorted array, the insert operation is faster as compared to a sorted array because we don’t have to care about the position at which the element is to be placed.
- **Details**: 

- **Description**: The insert operation in an array at any position can be performed by shifting elements to the right, which are on the right side of the required position.
- **Details**: 


## 2. Delete in an Unsorted Array
- **Description**: In the delete operation, the element to be deleted is searched using the linear search, and then the delete operation is performed.
- **Details**: After locating the element, the delete operation is followed by shifting the subsequent elements to fill the gap created by the deleted element.

## 3. Search in an Unsorted Array
- **Description**: Searching in an unsorted array typically requires a linear search.
- **Details**: The array is traversed from the beginning to the end to find the desired element.

## 4. Insert in a Sorted Array
- **Description**: Insertion in a sorted array requires finding the correct position to maintain the sorted order.
- **Details**: Once the correct position is identified, elements to the right are shifted to make space for the new element.

## 5. Delete in a Sorted Array
- **Description**: Deletion in a sorted array involves finding the element and removing it while maintaining the sorted order.
- **Details**: After deletion, elements are shifted left to fill the gap, preserving the array's sorted nature.

## 6. Search in a Sorted Array
- **Description**: Searching in a sorted array can be more efficient using algorithms like binary search.
- **Details**: Binary search divides the array into halves, significantly reducing the time complexity compared to a linear search.

## 7. Reverse an Array
- **Description**: Reversing an array involves swapping the elements from the two ends of the array until the middle is reached.
- **Details**: This operation can be performed in place with a time complexity of O(n).

## 8. Leaders in an Array
- **Description**: A leader in an array is an element that is greater than all the elements to its right.
- **Details**: This can be identified by iterating through the array from right to left.

## 9. Majority Element
- **Description**: The majority element in an array is an element that appears more than half the time.
- **Details**: Algorithms like Moore’s Voting Algorithm can be used to find the majority element in linear time.

## 10. Find the Number Occurring Odd Number of Times
- **Description**: Identifying the number that occurs an odd number of times in an array.
- **Details**: XOR operation is a common technique to solve this problem efficiently.

## 11. Largest Sum Contiguous Subarray
- **Description**: Finding the contiguous subarray with the maximum sum within a one-dimensional numeric array.
- **Details**: Kadane’s Algorithm is commonly used for this problem, with a time complexity of O(n).

## 12. Find the Missing Number
- **Description**: Determining the missing number in a given sequence of integers.
- **Details**: The sum formula or XOR approach can be applied to find the missing number efficiently.

## 13. Search an Element in a Sorted and Pivoted Array
- **Description**: Searching in a sorted and pivoted array involves modified binary search.
- **Details**: The array is divided into subarrays, and the search is performed in the relevant subarray.

## 14. Merge an Array of Size n into Another Array of Size m+n
- **Description**: Merging two arrays where one has enough space to accommodate the other.
- **Details**: The merge operation is performed by comparing and placing elements in their correct positions.

## 15. Median of Two Sorted Arrays
- **Description**: Finding the median of two sorted arrays of possibly different sizes.
- **Details**: A divide-and-conquer approach or binary search can be used to solve this efficiently.

## 16. Program for Array Rotation
- **Description**: Rotating the elements of an array by a given number of positions.
- **Details**: Various algorithms can be employed to perform the rotation with minimal time complexity.

## 17. Reversal Algorithm for Array Rotation
- **Description**: This algorithm rotates an array by first reversing parts of the array.
- **Details**: The array is divided and reversed in parts, followed by a reversal of the whole array to achieve the rotation.

## 18. Block Swap Algorithm for Array Rotation
- **Description**: An efficient algorithm to rotate an array by swapping blocks of elements.
- **Details**: This algorithm divides the array into blocks and swaps them to achieve the rotation.

## 19. Maximum Sum Such That No Two Elements Are Adjacent
- **Description**: Finding the maximum sum of non-adjacent elements in an array.
- **Details**: Dynamic programming is typically used to solve this problem efficiently.

## 20. Sort Elements by Frequency | Set 1
- **Description**: Sorting elements of an array based on their frequency of occurrence.
- **Details**: Hashing or a frequency array can be used to achieve the sorting.

## 21. Count Inversions in an Array
- **Description**: Counting inversions in an array, where an inversion is when a pair of elements is out of order.
- **Details**: This problem can be solved using merge sort with a time complexity of O(n log n).
