# miking-latex

Defines Latex environments and macros for including syntax-highlighted Miking
code in your Latex documents.

To use, include the `mcorelisting.tex` file in the preamble of your Latex file:
```
\input{mcorelisting}
```
Please see the file `example.tex` for example usages.

Note: if you are using Beamer, your frames have to be marked `fragile` when using a verbatim environment (such as the `mcore` environment) inside it:
```
\begin{frame}[fragile]
```
