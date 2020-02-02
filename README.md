# Convergence analysis of particle swarm optimization using stochastic Lyapunov functions and quantifier elimination
We present a computational procedure for stability analysis of particle swarm optimizer (PSO) and show that this approach leads to an extension of previously known stability regions for PSO under stagnation assumptions.

# Requirements
- Mathematica (>9.0)
- Maple
- Synrac library
# Instructions
For calculating the region according our described method we have to use mathematica and maple. The quantifier-free formula is calculated by maple wich uses the Synrac libarie. This Libarie have to be include in maple before running any script there.
The Authors working on a script which use only maple.
## calculating E(dV)
to calculate the expectation of E(dV) 'run mathematica/EdV.nb'
## QE with maple
run the maple-skript according to the System and the P-matrix. For instance:
'run maple/Sys1PIdentity.mw'
## convergence region
'run mathematica/regions.nb'
