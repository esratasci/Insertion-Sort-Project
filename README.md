# Project 1 - Insertion Sort 
#### [ 22, 27, 16, 2, 18, 6 ] -> Insertion Sort
#### 1. Write the stages of the above array according to the sort type.

First Stage:  
[ 22, 27, **16**, 2, 18, 6 ]  
[ 22, **16**, 27, 2, 18, 6 ]  
[ **16**, 22, 27, 2, 18, 6 ]  
Second Stage:  
[ 16, 22, 27, **2**, 18, 6 ]  
[ 16, 22, **2**, 27, 18, 6 ]  
[ 16, **2**, 22, 27, 18, 6 ]  
[ **2**, 16, 22, 27, 18, 6 ]  
Third Stage:  
[ 2, 16, 22, 27, **18**, 6 ]  
[ 2, 16, 22, **18**, 27, 6 ]  
[ 2, 16, **18**, 22, 27, 6 ]  
Fourth Stage:  
[ 2, 16, 18, 22, 27, **6** ]  
[ 2, 16, 18, 22, **6**, 27 ]  
[ 2, 16, 18, **6**, 22, 27 ]  
[ 2, 16, **6**, 18, 22, 27 ]  
[ 2, **6**, 16, 18, 22, 27 ]  

#### 2. Write the Big-O notation.
[n*(n+1)]/2 = (n²+n)/2 => O(n²)

#### 3. Time Complexity: Average case: The number we are looking for is in the middle, Worst case: The number we are looking for is at the end, Best case: The number we are looking for is at the beginning of the array. 
Worst case: [ 27, 22, 18, 16, 6, 2 ] -> O(n²)  
Best case: [ 2, 6, 16, 18, 22, 27 ] -> O(n)
#### 4. What case does the number 18 fall into after the array is sorted? Write.
After the array is sorted, the number 18 becomes the median value. Therefore it happens in the average case.

 #### Write the  first 4 stages of [ 7, 3, 5, 8, 2, 9, 4, 15, 6 ] according to Insertion Sort.

 First Stage:  
 [ 7, **3**, 5, 8, 2, 9, 4, 15, 6 ]  
 [ **3**, 7, 5, 8, 2, 9, 4, 15, 6 ]  
 Second Stage:  
 [ 3, 7, **5**, 8, 2, 9, 4, 15, 6 ]  
 [ 3, **5**, 7, 8, 2, 9, 4, 15, 6 ]  
 Third Stage:  
 [ 3, 5, 7, **8**, 2, 9, 4, 15, 6 ]  
 Fourth Stage:  
 [ 3, 5, 7, 8, **2**, 9, 4, 15, 6 ]  
 [ 3, 5, 7, **2**, 8, 9, 4, 15, 6 ]  
 [ 3, 5, **2**, 7, 8, 9, 4, 15, 6 ]  
 [ 3, **2**, 5, 7, 8, 9, 4, 15, 6 ]  
 [ **2**, 3, 5, 7, 8, 9, 4, 15, 6 ]  

 