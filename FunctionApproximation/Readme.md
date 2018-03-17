# Read section 9.8 in the textbook as well as “Linear Least-Squares Algorithms for Temporal Difference Learning” and “Technical Update: Least-Squares Temporal Difference Learning”.

1) Implement LSTD(lambda) 
-	Using the off-line formulation
-	Using the recursive formulation (and discuss the potential numerical instabilities)

2) Reproduce the five-states domain of Bradtke & Barto (1996) in Pycolab as well as Boyan’s Chain and report on the effect of changing lambda on your results

3) Read the section “Equivalence of LSTD(1) and linear regression” in the appendix of Boyan’s paper. Verify this claim empirically by computing the matrices A and b in the “supervised learning” approach. Compare the matrices with those that you would have obtained by LSTD(lambda=1) in part 1 and 2. Check if the solution (value function) found by the “supervised learning” approach matches the solution found by LSTD.

