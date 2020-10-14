# Extra Assignment: Merge Sort

There are many different sorting algorithms as you may have noticed. One of them
is merge sort. It is one of the more efficient algorithms (Quicksort is another)
for sorting but it is a bit more tricky than the previous bubble sort and selection
sort. In this extra task, your goal is to implement merge sort. In short, it works by
dividing the array into smaller arrays and then dividing those arrays into even smaller
arrays until there are arrays of only 1 element. It then merges these arrays back
and putting the elements in order.

#### Recommended reading
- [Merge Sort (Toptal)](https://www.toptal.com/developers/sorting-algorithms/merge-sort)
- [Merge sort in 3 minutes](https://www.youtube.com/watch?v=4VqmGXwpLqc)

#### Exercise 1

Implement the merge sort. It could be advantageous to use [recursion](https://www.baeldung.com/java-recursion).
Make sure you write tests to confirm that your implementation is working. For fun,
you could revisit the timing exercise in the previous sort assignment (selection/bubble/Arrays sort) and
see how your implementation of merge sort holds up to them in regards to time taken.
> **Assistant's Note:**
> If you want to dive in even deeper you could take a look at the time complexity analysis.
> It is not so trivial for merge sort but [here is a video](https://www.youtube.com/watch?v=alJswNJ4P3U)
> giving a detailed explanation as to why merge sort has the time complexity it has.