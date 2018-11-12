# Template for evaluating and grading projects

**Evaluation of project number:** 1

**Name:** Jessica Alatorre Flores and Francisco Nava Lujan


## Abstract
*Abstract: accurate and informative? Total number of possible points: 5*

Mark and comments:
There was no abstract. For tips on writing this section, a good overview can be
found here:
[https://users.ece.cmu.edu/~koopman/essays/abstract.html](https://users.ece.cmu.edu/~koopman/essays/abstract.html).
Please remember this for projects 2 and 3.
Points: 0/5


## Introduction
*Introduction: status of problem and the major objectives. Total number of
possible points: 10*

Mark and comments:
Great introduction!

Points: 10/10


## Formalism
*Formalism/methods: Discussion of the methods used and their basis/suitability.
Total number of possible points 20*

Mark and comments:
Good that all the methods are touched upon, but I'd like you to include some
more discussion on the problem at hand, i.e., that the goal is to fit an
unknown function of the form
\begin{align}
    \mathbf{y} = \mathbf{X}\boldsymbol{\beta} + \boldsymbol{\epsilon}.
\end{align}
By introducing the cost functions of the different schemes (OLS, Ridge, Lasso)
you could also have shown _how_ we find an expression for $\boldsymbol{\beta}$.
For instance for OLS you have the cost function $C$
\begin{align}
    C = ||\mathbf{y} - \mathbf{X}\boldsymbol{\beta}||^2,
\end{align}
and the goal is to find a $\boldsymbol{\beta}$ such that we find a minimum for
this function. That is,
\begin{align}
    \frac{\partial C}{\partial{\boldsymbol{\beta}}} = 0.
\end{align}
You don't necessarily have to show how to solve these equations, but it's good
to include it. Also, this makes it easier to explain that there are problems
with the analytic solution of Lasso such that a gradient descent algorithm has
to be employed in order to find a minimum.

Some discussion of the various statistics used to measure performance such as
MSE, R2, variance, bias, etc, would have been good.

Points: 12/20



## Code
*Code/Implementations/test: Readability of code, implementation, testing and
discussion of benchmarks. Total number of possible points 20*

Mark and comments:
The code is readable and easy to understand. Especially when reading the
section on implementation in the report! Cool that you use Pandas! I would
however recommend to start using functions as an abstraction to avoid these
very massive scripts. They will eventually become unmanageable and it can be
hard to ``just play around'' if you want to run different parts separately.

This might be a personal opinion, but I'd prefer not to include that much code
examples in the report. As long as you explain what you do (which you do very
well) and looking at the output and the source code on Github is enough.

For future reports it would also be good if you were to move output in tabular
form to a table in the report instead of pasting images from the terminal.

I've subtracted some points for the missing parts of the project.

Points: 15/20


## Analysis
*Analysis: of results and the effectiveness of their selection and presentation.
Are the results well understood and discussed? Total number of possible points:
20*

Mark and comments:
The analysis is good, and you discuss important points of the project. It's
also good that you are open about what you had trouble in completing/solving.
Much of the results that you discuss, e.g., the decrease in MSE with the
complexity, would have been good to have as a figure. It is a little hard to
read of these values from tables.

Again, I've subtracted some points for the last part of the project.

Points: 15/20


## Conclusions
*Conclusions, discussions and critical comments: on what was learned about the
method used and on the results obtained. Possible directions and future
improvements? Total number of possible points: 10*

Mark and comments:
Good discussion!

Points: 10/10


## Overall presentation:
*Clarity of figures and overall presentation. Too much or too little? Total
number of possible points: 10*

Mark and comments:
As mentioned before, it would be good get figures on some of the values which
makes sense to visualize. Values which are dependent on complexity such as the
error, R2, variance, etc, is nice to see plotted as the value in itself is not
necessarily of such high importance, but rather the change in these over
different models.

Tabular values would be nice to have in a table in the report rather than
screenshots of the output.

Points: 5/10


## Referencing
*Referencing: relevant works cited accurately? Total number of possible points
5*

Mark and comments:
The reference list looks good. Citing in the report itself is missing. I'm
unsure on what document type you are using, but in latex this is doable using
bibtex and the hyperref package.

Points: 5/5


## Overall
*Overall mark (%) and final possible final comments*
This is a very good start and I hope I haven't been to strict! There are a few
points which I've listed above that I would like to see improved, but there are
more reports coming up so I expect to see an improvement. Remember, we are
here to learn!

Total points: 72
