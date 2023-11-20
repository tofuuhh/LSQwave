# LSQwave

Supplement to manuscript:

Title: Well-posedness of first-order acoustic wave equations and space-time finite element approximation
<br>
Authors: T.F&uuml;hrer, R. Gonz&aacute;lez, M. Karkulik

Preprint uploaded to arXiv.org, URL: <a href="https://arxiv.org/abs/2311.10536">https://arxiv.org/abs/2311.10536</a>

## Contents of project
This project contains two files: 
<ul>
<li>LSQwave1D_Direct.ipynb</li>
<li>LSQwave2D_PCG.ipynb</li>
</ul>
Both are Jupyter Notebooks that execute Netgen/NGsolve via its Python interface. 
File 'LSQwave1D_Direct.ipynb' runs code using a direct solver for one-dimensional spatial domains and 'LSQwave2D_PCG.ipynb' runs a similar code for two-dimensional domains but with multigrid preconditioner and CG. 
