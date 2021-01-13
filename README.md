# AoC C Executor

C executor for the [Advent of Code Solver](https://github.com/tcollier/aoc_solver).

## Signature

```c
void executor(
    char *input[],
    char *(*part1_fn)(char **),
    char *(*part2_fn)(char **),
    int argc,
    char *argv[]);
```

## Template Code

```c
// main.c
#include "../../ext/c/lib.h"

char *part1_result(char *input[])
{
  // compute part 1 solution
  return solution;
}

char *part2_result(char *input[])
{
  // compute part 2 solution
  return solution;
}

int main(int argc, char *argv[])
{
  // load challenge input
  executor(input, part1_result, part2_result, argc, argv);
}
```
