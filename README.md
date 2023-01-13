# Mountain Number
Given an array of integers arr, return true if and only if it is a valid mountain array. Please include at least one automated test, and provide the code as an artifact at the end of the interview.
Recall that arr is a mountain array if,  and only if (constraints):
- arr.length >= 3
There exists some i with 0 < i < arr.length - 1 such that:
- arr[0] < arr[1] < ... < arr[i - 1] < arr[i]
- arr[i] > arr[i + 1] > ... > arr[arr.length - 1]:
- 1 <= arr.length <= 10^4
- 0 <= arr[i] <= 10^4

# Unit test
- Example 1:
Input: arr = [2,1]
Output: false
- Example 2:
Input: arr = [0,3,2,1]
Output: true
