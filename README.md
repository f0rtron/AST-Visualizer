# AST Visualizer

AST Visualizer Pro is a desktop application that visualizes the **Abstract Syntax Tree (AST)** of source code in real time.  
It is designed to help students, developers, and compiler learners understand how source code is tokenized, parsed, and structured internally by a compiler.

The application processes raw source code through lexical analysis and parsing, then renders a clear, navigable tree representation of the resulting AST.

---

## Features

- **Real-Time AST Visualization**  
  Instantly generate and view the abstract syntax tree as code is entered or updated.

- **Token Inspection**  
  Displays the output of the lexical analyzer, showing tokens and their types alongside the source code.

- **Zoom and Pan Navigation**  
  Easily explore large and complex trees using mouse-based zooming and panning.

- **Portable Executable**  
  Distributed as a standalone Windows executable. No Python or external tools required.

- **Syntax Error Feedback**  
  Highlights syntax errors and indicates where the input violates the grammar.

---

## Download & Installation

AST Visualizer is distributed as a standalone Windows executable.

1. Go to the **Releases** section of this repository.
2. Download the latest `AST Visualizer.exe`.
3. Run the executable.

> **Note:** The application includes all required dependencies.  
> No additional installation or setup is required.

---

## Usage Example

### Input Code

```python
x = 10
if (x > 5) {
    result = x + 1
}
```
### Output

The application produces a structured abstract syntax tree that includes:
- A root program block
- Assignment nodes representing variable initialization
- Conditional nodes with clearly separated condition and body branches

---

## Roadmap

- Lexer and parser implementation  
- Static AST generation (PNG output)  
- Dark mode user interface  
- Public source code release  
- Support for loop constructs and array structures  

---

## License

This project is currently distributed as closed-source software.  
Copyright © 2026. All rights reserved.
