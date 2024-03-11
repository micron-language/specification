This repository harbors the specifications of the Micron programming and intermediate language. The specifications are edited and the HTML generated using [CrossLine](https://github.com/rochus-keller/crossline/).

The programming language specification can be viewed using [this link](https://htmlpreview.github.io/?https://github.com/micron-language/specification/blob/master/The_Micron_Programming_Language_Specification.html).

The intermediate language specification can be viewed using [this link](https://htmlpreview.github.io/?https://github.com/micron-language/specification/blob/master/The_Micron_Intermediate_Language_Specification.html).

The grammars are developed and the parser generated using [EbnfStudio](https://github.com/rochus-keller/EbnfStudio).

NOTE that the languages are work-in-progress.


The Micron programming language is derived from the Oberon+ programming language. The goal is to design a language well suited for systems programming with the power of C, but without its major disadvantages.

The Micron intermediate language is derived from CIL (ECMA-335), but on a higher level, preserving the original control flow, but still suited for optimisation and translation to assembler, CIL, LLVM IR or C.
