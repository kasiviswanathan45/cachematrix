# cachematrix
Caching the inverse of a matrix
The programming assignment 2 is to write a funcion to cache the inverse of a matrix.It may take too long to create the inverse of a matrix.To find the cache of the inverse of the matrix a special matrix needs to be written and the cache of inverse of the matrix can be used in some other environment.This should essentially consists of two functions 
1.makeCacheMatrix
2.cacheSolve

makeCacheMatrix:
This function is a list which primarily constitng of the following 4 operations to store the inverse of the matrix:

set the value of the matrix                                                                                         
get the value of the matrix
set the value of the inverse
get the value of the inverse

cacheSolve:
This function calculates the inverse of the special "matrix" created with the above function. However, it first checks to see if the inverse has already been calculated. If so, it gets the inverse from the cache and skips the computation. Otherwise, it calculates the inverse of the matrix and sets the value of the inverse of the matrix in the cache via the solve function.

