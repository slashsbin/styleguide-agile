
Agile
=====

Story Points
------------

Steps/Levels
------------
Ten Levels:

> 1 > 2 > 3 > 4 > 5 > 6 > 7 > 8 > 9 > 10

Fibonacci Numbers
-----------------
```
F(n) = F(n-1) + F(n-2)
Seed:
F0 = 0
F1 = 1
```

Points are based on [Fibonacci Numbers](https://en.wikipedia.org/wiki/Fibonacci_number):

> 1 > 3 > 5 > 8 > 13 > 21 > 34 > 55 > 89 > 144

  - Numbers `1`, `2` were removed from Original Sequence:
    - `F(2)`: Additional Number `1` were Removed due to Conflicting with 1st Step(Aka `F(1)`)
    - `F(3)`: Number `2` were Removed due to Closeness to Siblings
  - It's a [Complete Sequence](https://en.wikipedia.org/wiki/Complete_sequence) which means Points can be Merged Disgustingly to Construct New Points.
  - Has Same Natural Meaning for Complexity Increase of Points for Tasks: Each subsequent number is the sum of the previous two, which Means every Task with Higher Point is Complex as Two Tasks with Previous Points!

Choose Points: How hard is to Implement a Task?
-----------------------------------------------

=== Included Factors: ===
  1. *Complexity*
  2. *Unknowns*
  3. *Effort*

=== Non-Included Factors: ===
  1. *Time*
  2. *Assignee*

Ground Rules
------------
  - `F(6)`: Number `8` is the Common/Middle Point:
    - Everyone in a [Cross-Functional](https://en.wikipedia.org/wiki/Cross-functional_team) Team can Do this!
    - Other Tasks Points are Calculated Compared to this Point.
