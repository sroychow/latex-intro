[← Back to Home](../index.md)

# Exercises Part 1
Try typesetting the following examples as shown in the slides on Overleaf.

## Exercise 1

```
\documentclass{article}
\begin{document}
Hello World! % your content goes here...
\end{document}
```

## Exercise 2

```
\documentclass{article}
\begin{document}
In March 2006, Congress raised that ceiling an additional $0.79 trillion to $8.97 trillion, which is approximately 68% of GDP. As of October 4, 2008, the "Emergency Economic Stabilization
Act of 2008" raised the current debt ceiling to $11.3 trillion.
% hint: the cause of the error is actually above,
% even though LaTeX puts the error message here
\end{document}
```

## Exercise 3
```
\documentclass{article}
\begin{document}

% hints:
% 1. you might want to use the amsmath package, add the   following line before \begin{document}
%\usepackage{amsmath}
% 2. the command for an infinity symbol is \infty

Let X1, X2, ..., Xn be a sequence of independent and
identically distributed random variables with
E[Xi] = mu and Var[Xi] = sigma squared < infinity, 
and let

Sn = 1/n times the sum for i from 1 to n of Xi

denote their mean. Then as n approaches infinity, the
random variables square root n(Sn - mu) converge in
distribution to a normal N(0; sigma squared).

\end{document}
```
