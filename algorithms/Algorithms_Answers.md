Add your answers to the Algorithms exercises here.

## Exercise I

a) O(n^3)
b) O(log n)
c) O(n^3)
d) O(n^2)
e) O(n^4)
f) O(n)
g) O(n)

## Exercise II

a) Assuming array is sorted from largest to smallest:

```function findMax(a) {
  return a[0] - a[a.length - 1];
}```

b) Start from the bottom floor and work your way up, dropping an egg at each level. As soon as the egg breaks, you've found f.

## Exercise III

a) O(n), because every list element will be greater, meaning that you will only have to run the sort algorithm once and iterate through the list.

b) O(n log(n)), as you will need to split the array into two lists.
