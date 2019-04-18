# ProbsharpSAT- model counter
ProbsharpSAT is a probabilistic exact model counter. It takes in a CNF formula `F` and a confidence `delta` as input and returns `count` such that `count` is the number of solutions of `F` with confidence at least `1 - delta`.

## Installation
The static binary of ProbsharpSAT and MIS is given in bin directory.

## Running ProbsharpSAT
You can run ProbsharpSAT by using 'probsharpsat.py' Python script present in bin directory. A simple invocation looks as follows:
```bash
python3 probsharpsat.py <cnffile>
```

The usage instructions and default values to arguments can be found by running:
```bash
python3 probsharpsat.py -h
```

## Benchmarks
Few toy benchmarks are given in benchmarks directory.

## Issues, questions, bugs, etc.
Please click on "issues" at the top and [create a new issue](https://github.com/probsharpsat/ProbsharpSAT/issues). All issues are responded to promptly.

