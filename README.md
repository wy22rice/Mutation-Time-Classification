# Mutation Time Classification

The development of cancer begins with one individual cell.  Over time, this cell grows and produces progeny, its progeny then go on to produce progeny of their own; this process repeats at given birth, death, and mutation rates, giving rise to the cell population.  At a given time t1, one cell gains a mutation that gives it an advantage over the other cells, and its progeny become known as clone 1.  After the tumor has been observed, a sample of the cells is taken and summary statistics are obtained from the data.

This section of the project will walk through various statistical models that aim to identify a relationship between these statistics and true t1, classifying the observations into low and high t1 groups using logistic regression with various penalties (none, ridge, lasso), support vector machines, and a heuristic method. It will also evaluate the performance of these models under special conditions, including small n, collinear parameters, and missing/inaccurate values.

Andrew Koval contributed to code. Datasets generated from Dr. Khanh Dinh's R cancer cell simulator.
