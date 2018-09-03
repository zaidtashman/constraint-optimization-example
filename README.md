# constraint-optimization

This [notebook](https://github.com/zaidtashman/constraint-optimization-example/blob/master/worker-group-notebook.ipynb) shows how to solve an assignment problem using constraint optimization.

Assuming we have *N* workers that need to be assigned to *M* groups. Each worker *i* in *1...N* must be assigned to one group only. Each group *j in 1...M* must have a minimum of *K* workers and a maximum of *N - M + 1* workers. In addition, user can input one more constraint that prohibits certain workers from being assigned to the same group.
