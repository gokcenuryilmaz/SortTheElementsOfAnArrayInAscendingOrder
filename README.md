# Sorting Elements of an Array in Ascending Order

This project provides an example of sorting an array from small to large using the Bubble Sort algorithm.
<br>

## Setup

<img width="139" alt="Ekran Resmi 2024-02-27 01 26 54" src="https://github.com/gokcenuryilmaz/SortTheElementsOfAnArrayInAscendingOrder/assets/128600199/e6f90668-f18b-4923-9c25-eb5b0b3e592d">
- JDK 19 or later

<br>

## Usage

1. Save the code as `SortAscending.java`.
2. Compile the code using the following command in the command line: javac SortAscending.java
3. Run the code using the following command: java SortAscending
<br>

## Example Output

Sorted array:
11 12 22 25 34 64 90

<br>

## Code Description
### Key Classes and Methods:
SortAscending: Contains the sort method for sorting an array.
<br>
sort method:
Takes an integer array as input.
Uses nested loops to compare and swap elements until the array is sorted.
<br>
main method:
Creates a sample array.
Calls the sort method to sort the array.
Prints the sorted array.
<br>
### Algorithm
The code implements the Bubble Sort algorithm, which works as follows: <br>
1. Iterates through the array multiple times. <br>
2. In each iteration, compares adjacent elements. <br>
3. Swaps elements if they are in the wrong order (descending). <br>
4. Repeat until no more swaps are needed (array is sorted). <br>

### Time Complexity

Bubble Sort has a time complexity of O(n^2), which means its performance degrades as the array size increases. For larger arrays, consider using more efficient sorting algorithms like Merge Sort or Quick Sort.
