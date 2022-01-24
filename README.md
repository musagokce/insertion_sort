# data_structures_and_algorithms


[22,27,16,2,18,6] -> Insertion Sort

1. Write the stages of the above given sequence according to the sort type.

  1. step = [ 2 , 27 , 16 , 22 , 18 , 6 ]
  2. step = [ 2 , 6 , 16 , 22 , 18 , 27 ]
  3. step = [ 2 , 6 , 16 , 18 , 22 , 27 ]

2.Write the Big-O notation.

  1. step = [ 2 , 27 , 16 , 22 , 18 , 6 ] (n)
  2. step = [ 2 , 6 , 16 , 22 , 18 , 27 ] (n-1)
  3. step = [ 2 , 6 , 16 , 18 , 22 , 27 ] (1)

  O = (n²)

3. Time Complexity: 

  Average case: The number we are looking for is in the middle>> O(n²)
  Worst case: The number we're looking for is at the end>> O(n²)
  Best case: The number we're looking for is at the top of the array>> O(n)
 
4. What case does the number 18 fall into after the array is sorted? Write.

  3. step = [ 2 , 6 , 16 , 18 , 22 , 27 ]

Since 18 is in the middle, it called as average case.

5. Write the first 4 steps of [7,3,5,8,2,9,4,15.6] according to Insertion Sort.

  1.step = [ 2 , 3 , 5 , 8 , 7 , 9 , 4 , 15 , 6 ]
  2.step = [ 2 , 3 , 4 , 8 , 7 , 9 , 5 , 15 , 6 ]
  3.step = [ 2 , 3 , 4 , 5 , 7 , 9 , 8 , 15 , 6 ]
  4.step = [ 2 , 3 , 4 , 5 , 6 , 9 , 8 , 15 , 7 ]
