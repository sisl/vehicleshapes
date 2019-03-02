# vehicleshapes
Vehicle shapes for use with the [PGF/TikZ](https://www.ctan.org/pkg/pgf?lang=en) LaTeX package. It currently defines shapes for `sedan top` corresponding to the top view of a sedan.

## Example

```latex
\documentclass{article}

\usepackage{tikz}
\usepackage{carshapes}

\begin{document}
    

    \begin{figure}
        \centering
        \begin{tikzpicture}
        \node [sedan top,body color=red!30,window color=black!80,minimum width=4cm] at (0,0) {};
        \node [sedan top,draw=black!,fill=black!60,minimum width=5cm,rotate=20] at (5,1) {}; 
        \end{tikzpicture}
        \caption{Sedan top.}
    \end{figure}

\end{document}
```
