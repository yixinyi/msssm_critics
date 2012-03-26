# MATLAB FS12 – Research Plan (in progress...)

 * Group Name: the critics
 * Group participants name: Xinyi Chen, Artemi Egorov, Pegah Kassraian Fard
 * Project Title: self-organized criticality in sandpile models
 
## General Introduction

The physical world is full of complex systems, which, in order to study them, we used to model them as dynamical systems, but governed by highly non-linear equations that we barely know how to solve them. Despite the nonanalicity, simple and regular rules might manifest in complex systems, like the simple power-law in critical systems, or the emergence of fractal patterns, etc. Moreoever, computer simulations allow us to study the complexity in a much more comprehensive way.

We would like, thus, to study in particular, "Self organized criticality (SOC)", which describes the tendency of strongly dissipative systems to drive themselves to a critical state, without any external tuning parameter, e.g. the temperature for an equilibrium thermodynamic system. This idea seems to provide a unifying large scale behaviour in systems with many degrees of freedom, as a complementary idea of 'Chaos', wherein simple systems with a small number of degrees of freedom display complex behaviour.

Despite nowadays many authors try to explain a vast range of systems with SOC, there seems to be none satisfying general understanding of SOC. Therefore, we will study the classical paradigm of the sandpile model as a cellula automaton and investigate its possibilities, as we aim at a better understanding of the SOC phenomenon. 

## The Model

Sandpile models are cellular automata with a variable (we model with the gravitational potential energy of each grain) defined in a d-dimensional lattice. At each time step an energy grain is added to a randomly chosen site, until the energy of a site reaches a threshold. When this happens the site relaxes and the energy is transferred to the nearest neighbors, which can relax on their turn too. New active sites can generate other relaxations and so on, eventually giving rise to an avalanche. The distribution of avalanches according to the their size follows a power law, which is attributed to the phenomenon of SOC. 
However, these models suppose many idealizations, e.g. the average energy conservation and instantaneous driving time between different avalanches. In order to understand better SOC, in this project, we adopt the mean field model [1] and investigate more complex sandpile models introducing, for example average energy dissipation, finite driving time, etc, and also, study if there is any dependence on the dimensionality of the lattice in the manifestation of SOC. 



## Fundamental Questions

At the end of the project we want to find the answer to these questions:

 * What characterizes SOC?
 * Can SOC be understood in a general framework of criticality, i.e. with an order parameter and external triggering? 
 * Is the mean field approximation the right approach to model SOC?
 * What benefits/insights can we gain from applying the mean field theory?
 * Why (classical) sandpile models manifest SOC? 
 * What are the possibilities/constraints of the sandpile model and how can we expand its functionality?
 * What is the practical value of SOC and the related models and the sandpile model in particular?
 * What different models of SOC exist and what are their differences?
 * How do we implement SOC in a simulation environment?



## Expected Results
 * We expect the mean field approach to give a unified picture of SOC in critical systems.
 * We expect SOC to be a particular case of criticality when certain specfic conditions hold.
 * We expect our more realistic sandpile models to not hold (maybe partially) the SOC behaviour.
 


## References 

(Explain possible extension to the above models)
(Code / Projects Reports of the previous year)

 * [1] How self-organized criticality works: A uniﬁed mean-ﬁeld picture; Alessandro Vespignani and Alessandro Vespignani; June 1998
 * [2] Fluctuations and Correlations in Sandpile Models; Alain Barrat, Alessandro Vespignani and Stefano Zapperi; September 1999
 * [3] Cellular automata and self-organized criticality; Michael Creutz; November 1996


## Research Methods

* cellular automata (CA)
** a discrete model consisting of a regular grid with a finite number of cells in a finite number of dimensions, where the cells have a finite number of possible states.
* sandpile model
** a CA-model, where grains are randomly placed on the sites/cells until a specific threshold is exceeded, when the pile collapses and transfers the sand to the adjacent sites.
* mean field theory
** used to simplify a model with multiple interactions by replacing them with an average interaction

## Other

(mention datasets you are going to use)
