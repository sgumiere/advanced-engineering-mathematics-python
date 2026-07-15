# Advanced Engineering Mathematics with Python — Code Notebooks

Jupyter notebooks containing all Python code from the book, organized by chapter. Each notebook mirrors the chapter's section structure, with one code cell per listing.

## Contents

| Notebook | Chapter | Code cells |
|---|---|---|
| [chapter_01.ipynb](chapter_01.ipynb) | A Brief Python Introduction for Symbolic Mathematics | 68 |
| [chapter_02.ipynb](chapter_02.ipynb) | First-Order Ordinary Differential Equations | 18 |
| [chapter_03.ipynb](chapter_03.ipynb) | Higher-Order Ordinary Differential Equations | 32 |
| [chapter_04.ipynb](chapter_04.ipynb) | Systems of Ordinary Differential Equations | 10 |
| [chapter_05.ipynb](chapter_05.ipynb) | Laplace Transforms | 23 |
| [chapter_06.ipynb](chapter_06.ipynb) | Matrices, Vectors, and Linear Systems | 27 |
| [chapter_07.ipynb](chapter_07.ipynb) | Eigenvalues and Eigenvectors in Engineering Applications | 32 |
| [chapter_08.ipynb](chapter_08.ipynb) | Vector Calculus | 15 |
| [chapter_09.ipynb](chapter_09.ipynb) | Fourier Series | 15 |
| [chapter_10.ipynb](chapter_10.ipynb) | Fourier Transform | 11 |
| [chapter_11.ipynb](chapter_11.ipynb) | Partial Differential Equations | 9 |
| [chapter_12.ipynb](chapter_12.ipynb) | Optimization | 13 |
| [chapter_13.ipynb](chapter_13.ipynb) | Neural Network Methods for Partial Differential Equations | 15 |
| [chapter_14.ipynb](chapter_14.ipynb) | Physics-Informed Neural Networks | 24 |
| [appendix_a.ipynb](appendix_a.ipynb) | Appendix A: Mathematical Reference Tables | 4 |

## Requirements

```bash
pip install numpy scipy sympy matplotlib torch
```

Chapters 13–14 (neural network methods and PINNs) require PyTorch; earlier chapters rely mainly on NumPy, SciPy, SymPy, and Matplotlib.

## Usage

```bash
jupyter lab
```

Open any notebook and run cells top to bottom. Cells within a chapter are ordered as they appear in the book but are largely self-contained per section.
