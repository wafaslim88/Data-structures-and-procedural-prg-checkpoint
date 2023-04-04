# Data-structures-and-procedural-prg-checkpoint
     problem1: sum_of_distinct_elements
Given two sets of elements, we are asked to find the sum of all distinct elements from the set. In other words, 
find the sum of all elements which are present in either of the given set.
we will go with the solution with an array,so:
 a) we will begin with Initializing: sum = 0. 
 b) we Compare each element of set one with the second set and if element is not present then we add that element to sum. 
 c) do the vice versa to add elements from the second set.
 
    problem2: Dot product
we are asked to write an algorithm that fulfill the following: 
1) Write a procedure, called dot_product which calculates in the variable ps, the dot(scalar) product of v1 and v2 (v1 and v2 are vectors of IR)
2)Write an algorithm which determines, for n pairs of given vectors, whether two vectors of given IR are orthogonal, by calling the procedure defined previously knowing that the dot product of two orthogonal vectors is zero.
3)Modify the previous algorithm if you use a dot_product function instead of a procedure.
so, we will compare the two vectors lengh because if the vectors have different sizes we cannot calculate dot product.then we calculate the dot product. the same work for the function but in this case we will return the value of dot. finally we write the algorithm orthogonal vectors.
