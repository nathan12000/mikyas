# Compiler

# Introduction
A compiler is a special type of system software that translates a program written in a high-level programming language (such as C, C++, or Java) into machine-level language that a computer can understand and execute. This translation process allows programmers to write code using human-readable instructions instead of complex binary codes.

The compiler works by analyzing the source code for errors, checking its syntax and semantics, and then converting it into an optimized form of machine code or intermediate code. By doing so, it helps improve program efficiency and ensures that the code runs correctly on the target system. Compilers play a crucial role in software development, acting as a bridge between human thinking and computer hardware.
# Left Factoring

Left factoring is a grammar transformation technique used in compiler design, especially in top-down parsing. It is applied when two or more production rules of a non-terminal start with the same prefix. This common prefix is factored out to avoid ambiguity and make the grammar suitable for predictive parsing (LL parsers).

## Example:
Before left factoring:
A → ab | ac

After left factoring:
A → aA′
A′ → b | c

Left factoring helps the parser decide which production to use by looking ahead at the input symbols.

---

### **Parse Tree**

**Introduction:**
A parse tree is a hierarchical, tree-like representation of the grammatical structure of a string according to a given grammar. It shows how the start symbol of the grammar derives the string using production rules.

**Key Points:**

* The root node represents the start symbol.
* Internal nodes represent non-terminals.
* Leaf nodes represent terminals or tokens.

Parse trees are useful for understanding syntax structure and are widely used in syntax analysis during compilation.

---

### **Syntax Rule**

**Introduction:**
Syntax rules define the structure of a programming language. They specify how symbols, keywords, and expressions are combined to form valid statements and programs. These rules are usually written using formal grammars such as Context-Free Grammar (CFG).

**Example:**
Statement → if (Expression) Statement

Syntax rules help the compiler check whether a program follows the correct grammatical structure of the language. Violating syntax rules results in syntax errors during compilation.

---

If you want, I can also simplify these notes further or format them for exam writing.
