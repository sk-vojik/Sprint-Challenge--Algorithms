Add your answers to the Algorithms exercises here.

Exercise I.

A). 
This algorithim is O(n^3). The while condition has n * n * n, which is n^3

B).
This algorithim is O(n^4). There are four nested for loops, so n * n * n * n

C).
This algorithim is just O(n). It is recursive, and decrease by 1 each time, so it is linear, or a 1:1 ratio of input to output.


Exercise II.

This question is more or less a binary search question. What you would want to do is first go to the mid point, so floors / 2. You'd then want to run the eggtest function here at the midpoint. If it breaks, -1 and go down. Keep trying at each floor until you find where it no longer breaks, decreasing each time by 1. If it doesn't break, then you would increase the floor by 1. Continue increasing the floor by one until you find where the egg breaks. This algorithim has a runtime of O(log n).