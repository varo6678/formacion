<!-- ./ -->

# README.md

### Cosas a tener cuenta

#### Trabajar con VSCODE.

> Importante tener el settings.json en user actualizado con el que esta en el repositorio.

> Puedes hacer ctrl+click para ir a la zona del pdf donde estas en el codigo.

> Puedes hacer ctrl+alt+j para ir a la zona del codigo donde estas en el pdf.

#### Ejemplos de pseudocodigo.

```{latex}
% Ejemplo de algoritmo.
\begin{figure}[h!]
    \centering
    \begin{minipage}[b]{0.45\textwidth}
        \centering
        \begin{algorithm}[H]  % Evitar que el algoritmo sea un flotante independiente
            \caption{An algorithm with caption}\label{alg:cap}
            \begin{algorithmic}
            \Require $n \geq 0$
            \Ensure $y = x^n$
            \State $y \gets 1$
            \State $X \gets x$
            \State $N \gets n$
            \While{$N \neq 0$}
                \If{$N$ is even}
                    \State $X \gets X \times X$
                    \State $N \gets \frac{N}{2}$  \Comment{This is a comment}
                \ElsIf{$N$ is odd}
                    \State $y \gets y \times X$
                    \State $N \gets N - 1$
                \EndIf
            \EndWhile
            \end{algorithmic}
        \end{algorithm}
    \end{minipage}
    \caption{Algoritmo}
\end{figure}
```