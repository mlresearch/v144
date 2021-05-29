---
title: Accelerating Distributed SGD for Linear Regression using Iterative Pre-Conditioning
abstract: This paper considers the multi-agent distributed linear least-squares problem.
  The system comprises multiple agents, each agent with a locally observed set of
  data points, and a common server with whom the agents can interact. The agents’
  goal is to compute a linear model that best fits the collective data points observed
  by all the agents. In the server-based distributed settings, the server cannot access
  the data points held by the agents. The recently proposed Iteratively Pre-conditioned
  Gradient-descent (IPG) method has been shown to converge faster than other existing
  distributed algorithms that solve this problem. In the IPG algorithm, the server
  and the agents perform numerous iterative computations. Each of these iterations
  relies on the entire batch of data points observed by the agents for updating the
  current estimate of the solution. Here, we extend the idea of iterative pre-conditioning
  to the stochastic settings, where the server updates the estimate and the iterative
  pre-conditioning matrix based on a single randomly selected data point at every
  iteration. We show that our proposed Iteratively Pre-conditioned Stochastic Gradient-descent
  (IPSG) method converges linearly in expectation to a proximity of the solution.
  Importantly, we empirically show that the proposed IPSG method’s convergence rate
  compares favorably to prominent stochastic algorithms for solving the linear least-squares
  problem in server-based networks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakrabarti21a
month: 0
tex_title: Accelerating Distributed {SGD} for Linear Regression using Iterative Pre-Conditioning
firstpage: 447
lastpage: 458
page: 447-458
order: 447
cycles: false
bibtex_author: Chakrabarti, Kushal and Gupta, Nirupam and Chopra, Nikhil
author:
- given: Kushal
  family: Chakrabarti
- given: Nirupam
  family: Gupta
- given: Nikhil
  family: Chopra
date: 2021-05-29
address:
container-title: Proceedings of the 3rd Conference on Learning for Dynamics and Control
volume: '144'
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 5
  - 29
pdf: http://proceedings.mlr.press/v144/chakrabarti21a/chakrabarti21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
