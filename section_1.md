## pseudocode for solution of system of equation
```python
FUNCTION solution(A,B):
  Create Augmented matrix: k=[A/B]
  Reduce in Row Reduced Echelon form
  Rank=no: of non zero rows of RREF
  if Rank(K)!= Rank(A):
    print("System is inconsistent")
  ELSE IF:
    solve using back substitution
END FUNCTION
  ```
