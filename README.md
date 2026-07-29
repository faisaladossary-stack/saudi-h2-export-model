# saudi-h2-export-model
Stochastic techno-economic model of Saudi hydrogen export pathways (MSc thesis, Imperial College London).

# Saudi Hydrogen Export Pathways — Stochastic TEA

MSc thesis model (Imperial College London). One notebook regenerates
every figure and table in the thesis: Run All executes the full
pipeline (57 correlated inputs, N = 10,000 Latin Hypercube draws,
Sobol analysis at 483,328 evaluations) with a fixed seed (42), so
results reproduce exactly. Runtime approx. XX minutes; the Sobol
stage dominates. Requires the packages in requirements.txt.
