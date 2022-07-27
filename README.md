# fnirs-rsfc

### Background

Resting State Functional Connectivity (RSFC) in Functional Near-Infrared Spectroscopy (fNIRS) Signals

RSFC -> Pearson's correlation coefficient -> signal assumptions for valid statistical results

FNIRS signals -> non-white and non-stationary -> violate assumptions -> invalidate statistical RSFC results

### Code files

**Correction methods to correct for the assumption violations**

Code for simulation signals 

The methods can be applied in experimental fnirs data

Check [this link](https://sites.google.com/view/mengmengwang/research) for detailed methods

`nw_sim.m` : a statistical correction method to correct for the effects for non-white signals in sample correlation distributions

`ns_sim.m` : a correction method to correct for the effects for multiplicative non-stationary signals in sample correlation distributions

