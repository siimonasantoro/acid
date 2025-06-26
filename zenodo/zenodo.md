This repository contains the scripts and StepUp workflows to regenerate
the "AutoCorrelation Integral Drill" (ACID) test set.
The ACID test set comprises a diverse collection of algorithmically generated time series
designed to evaluate the performance of algorithms that compute the autocorrelation integral.
The set contains in total 15360 test cases, and each case consists of one or more time series.
The cases differ in the kernel characterizing the time correlations, the number of time series,
and the length of the time series.
For each combination of kernel, number of sequences and sequence length,
64 test cases are generated with different random seeds
to allow for a systematic validation of uncertainty estimates.
The total dataset, once generated, is about 80 GB in size.

In addition to the ACID test set, this repository also contains scripts and workflows
to validate [STACIE](https://molmod.github.io/stacie/),
a software package for the computation of the autocorrelation integral.
The results of this analysis are discussed in the following paper:

> Gözdenur, T.; Fauconnier, D.; Verstraelen, T.
> "STable AutoCorrelation Integral Estimator (STACIE): Robust and accurate transport properties from molecular dynamics simulations"
> arXiv 2025, [arXiv:2506.20438](https://arxiv.org/abs/2506.20438).
