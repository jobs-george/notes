# Introduction

Note-taking style class. 

# Getting Started


Add the notes class as a submodule in a LaTeX project 

```sh
git submodule add https://github.com/jobs-george/notes.git
```

This will create a `.gitmodules` file in the project directory and clone the submodule as a `notes` directory.

Import the document class with `\documentclass{notes/notes}`.
An example document using the class looks like this,

```tex
\documentclass{notes/notes}
\begin{document}
Hello, world!
\end{document}
```

# Build and Test

N/A 

# Contribute

Please open a pull request to contribute.