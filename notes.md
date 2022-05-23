# Magic

## 23 May, 2022

Resource: [https://thesephist.com/posts/pl/](https://thesephist.com/posts/pl/)

Takeaways

> Writing a programming language involves understanding the most meaty parts of the computing stack, from the CPU and memory up through the operating system, in-memory data structures, processes, threads, the stack, all the way up to libraries and applications.
> 

Design of the Language

- Designing the semantics of the language is more important than designing the syntax of the language
- Questions:
    - Types: what types? type conversion? type checking?
    - Organizing unit of programs in the language?
    - Exception Handling
    - Tail Recursion Optimization ?
    - Utility functions?
    - Memory Allocation?
- Consider Awk — “domain-specific language” that’s designed for manipulating text files & textual data.

Implementation

- Test-drive: try writing code in the language to be created and validate ideas

Interpreters and compilers are layers and layers of small transformations to your source code (a string of text) into some form executable by your computer.

TODO: check out books recommended by author

Phases of Compilation:

- Lexical analysis
- Syntax Analysis
- Semantic Analysis
- Intermediate Code Generation
- Optimization
- Target code generation

MA’s Questions

1) Design in detail or head first?

2) Compiler vs. Interpreter?

2) Which type of compiler? Should we build a source-to-source compiler?
