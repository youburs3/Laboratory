
---

### **2. LaTeX Template** (for formal lab reports)
```latex
\documentclass{article}
\usepackage{amsmath, graphicx, hyperref}

\title{Title of the Experiment}
\author{Your Name}
\date{DD/MM/YYYY}

\begin{document}

\maketitle

\section*{Abstract}
Summary of the experiment.

\section{Introduction}
Theory and objectives.

\section{Materials and Methods}
Procedure and setup.

\section{Results}
\begin{table}[h]
\centering
\begin{tabular}{|c|c|c|}
\hline
Trial & Voltage (V) & Current (A) \\ \hline
1 & 5.0 & 0.2 \\ \hline
2 & 10.0 & 0.4 \\ \hline
\end{tabular}
\caption{Experimental Data}
\end{table}

\section{Discussion}
Analysis of results.

\section{Conclusion}
Key takeaways.

\begin{thebibliography}{9}
\bibitem{ref1} Author, \textit{Title}, Journal, Year.
\end{thebibliography}

\end{document}
