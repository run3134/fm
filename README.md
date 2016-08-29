# fm
This is the code based on "blebreton/spark-FM-parallelSGD"
https://github.com/blebreton/spark-FM-parallelSGD/blob/master/fm/fm_parallel_sgd.py

* improvements
    - introduce intercept and linear terms
    - mainly introduce pandas DF so that columns can be handled easily
     
* next to do
    - why sklearn need to use different solver: loglinear
    - we only need to provide: loss + grad + hess
    - to understand: why polynomial kernal in svm is comparable to FM

