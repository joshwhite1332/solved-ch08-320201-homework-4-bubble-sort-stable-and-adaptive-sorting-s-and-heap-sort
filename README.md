Download Link: https://assignmentchef.com/product/solved-ch08-320201-homework-4-bubble-sort-stable-and-adaptive-sorting-s-and-heap-sort
<br>
<strong>Problem 1: Bubble Sort &amp; Stable and Adaptive Sorting.s                                                                              </strong>

<ul>

 <li>Bubble Sort is a comparison sorting algorithm that works by repeatedly stepping through the list to be sorted, comparing each pair of adjacent items, and swapping them if they are in the wrong order. This is repeated until no swaps are needed, which indicates that the list is sorted. Write the Bubble Sort algorithm in pseudocode including comments to explain the steps.</li>

 <li>Derive the asymptotic worst-case, average-case, and best-case running time of Bubble Sort.</li>

 <li>Stable sorting algorithms maintain the relative order of records with equal keys (i.e., values). Thus, a sorting algorithm is stable if whenever there are two records <em>R </em>and <em>S </em>with the same key and with <em>R </em>appearing before <em>S </em>in the original list, <em>R </em>will appear before <em>S </em>in the sorted list. Which of the sorting algorithms Insertion Sort, Merge Sort, Heapsort, and Bubble Sort are stable? Explain your answer.</li>

 <li>A sorting algorithm is adaptive, if it takes advantage of existing order in its input. Thus, it benefits from the pre-sortedness in the input sequence and sorts faster. Which of the sorting algorithms Insertion Sort, Merge Sort, Heapsort, and Bubble Sort are adaptive? Explain your answer.</li>

</ul>

<strong>Problem 2: Heap Sort</strong>

<ul>

 <li><em>Implement </em>the Heap Sort algorithm as presented in class.</li>

 <li><em>Implement </em>a variant of the Heap Sort that works as follows: In the first step it also builds a max-heap. In the second step, it also proceeds as the Heap Sort does, but instead of calling MAX-HEAPIFY, it always floats the new root all the way down to a leaf level. Then, it checks whether that was actually correct and if not fixes the max-heap by moving the element up again. This strategy makes sense when considering that the element that was swapped to become the new root is typically small and thus would float down to a leaf level in most cases. Hence, one would save the additional tests when floating down the element. And, the fixing step (moving the element upwards again) would be a rare case.</li>

 <li>Compare the original Heap Sort and its variant in (b) for input sequences of different lengths (including larger input sequences). What can you observe?</li>

</ul>