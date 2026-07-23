An array is a linear data structure used to store multiple elements of the same type under a single variable name. The elements are stored in a contiguous (continuous) block of memory, and each element is identified by its index.
EXAMPLE:
arr = [10, 20, 30, 40, 50]

Arrays are used to organize and store multiple related values efficiently. Instead of creating separate variables for each value, an array stores them together, making it easier to access, modify, and process data.
Arrays are one of the most fundamental data structures because many advanced data structures are built using them.

**Characteristics of Arrays**
1. Linear Data Structure

An array is a linear data structure, meaning elements are arranged in a sequential order. Each element has one predecessor (except the first element) and one successor (except the last element).

2. Contiguous Memory Allocation

One of the defining characteristics of an array is that its elements are stored in contiguous memory locations. Since the memory locations are continuous, the computer can directly calculate the address of any element using its index.
This property makes accessing elements very efficient.

3. Indexed

Every element in an array has a unique index. Most programming languages, including Python, C, C++, Java, and JavaScript, use 0-based indexing, where the first element has an index of 0.
Example:
arr = [10, 20, 30]

arr[0] = 10
arr[1] = 20
arr[2] = 30

4. Ordered Collection
The order of elements in an array is preserved. Changing the order of elements changes the array itself.

5. Homogeneous Data (Concept)

Traditionally, arrays are designed to store elements of the same data type.
For example,
All integers
All floating-point numbers
All characters

Note: Python lists allow different data types, but when studying DSA, we generally treat them as arrays containing the same type of data.

**Array Index**

An index represents the position of an element within the array.
There are two types of indexing in Python:

**Positive Indexing**
Starts from 0.

0  1  2  3

**Negative Indexing**
Starts from -1 and moves backward from the last element.

-4  -3  -2  -1

Negative indexing is a feature specific to Python.

**Operations on Arrays**

Every array problem is built using one or more of these operations.

1. Traversal

Traversal means visiting each element of the array exactly once. Traversal is used whenever we need to process every element.
Time Complexity: O(n)

2. Access

Access means retrieving an element using its index. Since arrays use contiguous memory, the computer can directly locate the required element.
Time Complexity: O(1)

3. Search

Searching means finding whether a particular element exists in the array. For an unsorted array, every element may need to be checked until the desired element is found.
Time Complexity: O(n)
If the array is sorted, Binary Search can reduce the complexity to O(log n).

4. Update

Updating means replacing the value stored at a particular index with a new value. Only the specified element changes.
Time Complexity: O(1)

5. Insertion

Insertion means adding a new element into the array. If the new element is inserted anywhere other than the end, the remaining elements must shift to make space. Because of shifting, insertion is generally expensive.
Time Complexity: O(n)

6. Deletion

Deletion means removing an element from the array. After deletion, the remaining elements shift to fill the empty position.
Time Complexity: O(n)

**COMMON PATTERNS IN ARRAYS**
**Traversal
Two Pointers
Sliding Window
Prefix Sum
Binary Search
Hashing
Sorting
Greedy**
