# Time-Complexity-Sorting-Python
This Python code implements three sorting algorithms: Merge Sort, Quick Sort, and Selection Sort. It also plots the time complexity of these algorithms for lists of different sizes.

The code starts by defining the Merge Sort algorithm, which recursively divides the input array into smaller subarrays, sorts them individually, and then merges them to obtain the sorted array.

Next, the Quick Sort algorithm is implemented. It chooses a pivot element and partitions the array such that elements smaller than the pivot are on the left, and elements greater than the pivot are on the right. The algorithm then recursively applies the same process to the left and right subarrays.

The Selection Sort algorithm is also implemented, which repeatedly selects the minimum element from the unsorted part of the array and places it at the correct position.

The code then prompts the user to choose which sorting algorithm to run: Merge Sort, Quick Sort, or Selection Sort. Depending on the choice, the code either reads input from the user or generates random arrays. The chosen sorting algorithm is then applied to the array, and the sorted array is printed.

After sorting a sample array, the code performs a running time analysis. It generates arrays of different sizes and measures the time taken to sort each array using the chosen algorithm. The sizes and corresponding running times are stored in the elements and times lists, respectively.

Finally, the code plots the time complexity by using matplotlib.pyplot. The x-axis represents the list length, and the y-axis represents the time complexity. The label for the plotted line corresponds to the chosen sorting algorithm.

This code can be used to study and compare the time complexity of Merge Sort, Quick Sort, and Selection Sort for different list sizes.
