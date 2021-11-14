Revenge of the polynomial method: Upper-bounding the adversary bound's tightness
Symmetric problems admit symmetric optimal solutions

Change rho, sigma, pi to rho_xyz particularly for faulty ops


Selling points: sell that no reverse queries are needed


Fill gap in rewriting

Fill gap in dual derivation

Faulty: Find bound, error analysis, find dual
Find application for faulty?

use "purification of reduced state" reduced state: purif 12x
vs "representation of Gram matrix" gramam atrix: rerpres 0x gram 27x

define mixification?
introduce notation specifying every matrix domain, type? and states? yes, useful, also saves having to explain exact domain somewhere, particularly in concrete applications
notation: underscore vs [[x,y]]
rho^T vs transpose...

everything expressed in terms of Gram matrix: clearly worse than as RDM
choose 1!
Define G_H, G_HX
vs define G_H, use trx as needed
vs don't define G_H, use diag=1 as needed.

define matrix entry as [[x,y]]
vs define matrix entry as _xy.
define space X' Hilbert space without idle subspace in the beginning, or just in the one part in the dual bound where I need it now? Would it be helpful anywhere else?
introduce notation L(H), H(H) or so explicitly?

to remember: acti

TODO IS THERE CONTEΧΤ ΗΕLP FOR SYMBOLS?

Fourier
WARNING this part not yet written down in LaTeX, and may therefore be wrong. For a more concrete application - and to demonstrate how symmetry arguments can be used to simplify the problem - I discuss a model of the phase estimation problem. If the problem formulation is invariant under phase shifts, one can assume w.l.o.g that an optimal solution exhibits the same symmetry by a group-averaging argument and convexity. Then the Gram matrices involved are circulant, and the conversion problem turns into a time-optimal transport problem of the probability mass in Fourier space. TODO WRIT/DeVELOP RESULTS ON OUTPUT CONDITIONS, TODo group averaging actually isnt necessary for this particular problem? TOMAYBEDO it seems the Fourier transform trick can be easily generalized to Fourier transforming over other symmetry groups?

We can check whether arbitrary posterior probability distributions of phases are feasible given a certain budget of queries by semidefinite programming constraints.???

We apply the algorithm-bound duality to achieve 
