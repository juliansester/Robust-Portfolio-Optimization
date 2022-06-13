# Code for "Markov Decision Processes udner Model Uncertainty"

## Ariel Neufeld, Julian Sester

# Abstract

We introduce a general framework for Markov decision problems under model uncertainty in a discrete-time infinite horizon setting. 
By providing a dynamic programming principle we obtain a local-to-global paradigm, namely solving a local, i.e., a one time-step robust optimization problem leads to an optimizer of the global (i.e. infinite time-steps) robust stochastic optimal control problem, as well as to a corresponding worst-case measure.

Moreover, we apply this  framework to portfolio optimization involving data of the S&P500. We present two different types of ambiguity sets; one is fully data-driven given by a Wasserstein-ball around the empirical measure, the second one is described by a parametric set of multivariate normal distributions, where the corresponding uncertainty sets of the parameters are estimated from the data.
It turns out that in scenarios where the market is volatile or bearish, the optimal portfolio strategies from the corresponding robust optimization problem outperforms the ones without model uncertainty, showcasing the importance of taking model uncertainty into account.


# Content

The Portfolio Optimization procedure from the paper is provided in a [Jupyter Notebook]([https://github.com/juliansester/nga/blob/main/Example%20Butterfly.ipynb](https://github.com/juliansester/Robust-Portfolio-Optimization/blob/main/Portfolio_Optimization.ipynb)).


## Data
Note that the data of the S&P 500 is directly downloaded from Yahoo Finance within the jupyter notebook.

# License

MIT License

Copyright (c) 2022 Julian Sester

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
