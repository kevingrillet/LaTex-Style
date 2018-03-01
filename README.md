# LaTex-Style

## Utilisation Style.sty ##
```
\documentclass[a4paper, 10pt]{article}
\usepackage{style}

% Début du document
\begin{document}
	\debut{2}{Titre}{Sous-titre}
	  %Corps du document
    
% Fin du document
\end{document}
```

## Options ##
### Titre sur deux lignes ###
```
\debut{3}{\begin{tabular}{c}Titre\\long\end{tabular}}{Sous-titre}
\fancyhead[RE,LO]{\textsc{Titre long}}
```
### Couleurs personnalisées ###
- ![#009900](https://placehold.it/15/009900/000000?text=+) `mygreen`
- ![#808080](https://placehold.it/15/808080/000000?text=+) `mygray`
- ![#9400d1](https://placehold.it/15/9400d1/000000?text=+) `mymauve`
- ![#cccc00](https://placehold.it/15/cccc00/000000?text=+) `darkyellow`

### Tableaux ###
```
\begin{tabular}{|l|l|l|} \hline
	\thead{Col1} & \thead{Col2} & \thead{Col3} \\ \hline
	Lorem & Lorem & Lorem \\ \hline
	Lorem & Lorem & Lorem \\ \hline
\end{tabular}
```

### Code ###
Inclure un fichier
```
\lstinputlisting{sujet23.ml}
```
Écrire directement dans le .tex
```
\begin{lstlisting}
	Code...
\end{lstlisting}
```
