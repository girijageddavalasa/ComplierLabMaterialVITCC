# CompilerLabMaterialVITCC

Compiler Lab assessments and practice materials for VIT Compiler Design Laboratory.

## Note

* Folders named `Assessment-*` contain the actual assessment codes.
* Other folders contain practice materials, repeated implementations, and additional example programs for learning purposes.

---

# Assessment-1

## Experiment-1

Implementation of Deterministic Finite Automaton (DFA) from Regular Grammar using C language.

**Input:**
Set of states (Q), input alphabet (T), final states (F), transitions (Δ), and terminal string (w).

**Output:**
Transition table and sequence of transitions to accept `w`.

---

## Experiment-2

Implement a C program to derive Regular Grammar from a Deterministic Finite Automaton (DFA).

**Input:**
Set of states (Q), input alphabet (T), final states (F), and transition table.

**Output:**
Grammar `G = (N, T, P, S)`.

---

## Experiment-3

Implementation of DFA from Non-Deterministic Finite Automata (NFA) without ε-transitions using C language.

---

## Experiment-4

### (a)

Implement a DFA in LEX code to accept:

* Odd number of `a`
* Even number of `b`
* Followed by `ccc`

### (b)

Implement a DFA in LEX code that accepts strings over `{a, b, c}` having `bca` as substring.

---

# Assessment-2

## Experiment-5

Construct a lexical analyzer.

Tasks:

* Identify tokens from a simple statement stored in a linear array.
* Identify tokens from a small program (≤ 5 lines) stored in a text file.
* Identify tokens from user input and store them in a text file.

---

## Experiment-6

Construct a lexical analyzer using the LEX tool.

---

## Experiment-7

Using LEX tool:

* Count frequency of a given word in a file.
* Replace a word with another word from file input.
* Find the length of the longest word.
* Construct a lexical analyzer using LEX tool.

---

# Assessment-3 (Part-1)

## Experiment-8(a)

Construct Predictive Parse Table using C language.

**Hint:**
Use grammar without left recursion, find FIRST and FOLLOW sets, then construct parse table.

---

## Experiment-8(b)

Implement Predictive Parsing Algorithm using:

* Parse table
* Input string

Implementation language: C

---

## Experiment-9(a)

Construct precedence table for a given operator grammar.

---

## Experiment-9(b)

Perform operator precedence parsing using the precedence table.

---

# Assessment-3 (Part-2)

## Experiment-10(a)

Construct Simple LR (SLR) Parse Table using C language.

---

## Experiment-10(b)

Implement LR Parsing Algorithm using:

* Parse table
* Input string

Implementation language: C

---

## Experiment-11(a)

Construct Canonical LR (CLR) Parse Table using C language.

---

## Experiment-11(b)

Implement LR Parsing Algorithm using:

* Parse table
* Input string

Implementation language: C

---

## Experiment-12(a)

Construct Look-Ahead LR (LALR) Parse Table using C language.

---

## Experiment-12(b)

Implement LR Parsing Algorithm using:

* Parse table
* Input string

Implementation language: C

---

# Assessment-4

## Experiment-13

Implementation of a simple calculator using LEX and YACC tools.

---

## Experiment-14

Implementation of Abstract Syntax Tree (AST) – Infix to Postfix using LEX and YACC tools.

---

## Experiment-15

Using LEX and YACC tools to recognize strings of the following Context-Free Languages (CFL):

1. `L(G) = { aⁿbᵐ | m ≠ n }`

2. `L(G) = { ab(bbaa)ⁿbba(ba)ⁿ | n ≥ 0 }`

---

# Assessment-5

## Experiment-16

Implementation of Three Address Code (TAC) generation for a simple program using LEX and YACC tools.

---

## Experiment-17

Implement simple code optimization techniques:

* Constant Folding
* Strength Reduction
* Algebraic Transformation

---

## Experiment-18

Implement the Back-End of a compiler where:

* Three Address Code is given as input
* 8086 Assembly Language is generated as output
