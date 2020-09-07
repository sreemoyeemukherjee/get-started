# Quality Standards

## Simplicity

Simple code makes its intent obvious.
Decomposition and Naming help a developer
to understand without ambiguity.

Low duplication yields a single source of truth, reducing surprises
during maintenance.

Low function-complexity helps in testability as well.
Towards this, the cyclomatic complexity-limit for a method is 3.
[This workflow](https://github.com/Engin-Boot/get-started/tree/master/workflow-files/complexity)
implements such a limit.

## KPI

- Zero compiler warnings
- Zero findings from static analysis
- High test coverage

## Workflows

These workflows are starting points to gate according to
the above list of KPI.

[C++ starter workflow](https://github.com/Engin-Boot/get-started/tree/master/workflow-files/cpp)
[C# starter workflow](https://github.com/Engin-Boot/get-started/tree/master/workflow-files/cs)