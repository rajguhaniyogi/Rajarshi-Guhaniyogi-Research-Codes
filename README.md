# Spatial Meta Kriging
This Repository contains research code for the research project ``Spatial Meta Kriging". 
Spatial process models for analyzing geostatistical data entail computations that
become prohibitive as the number of spatial locations becomes large. There is a burgeoning
literature on approaches for analyzing large spatial datasets. Spatial meta kriging approach
proposes a divide-and-conquer strategy within the Bayesian paradigm. We partition the
data into subsets, analyze each subset using a Bayesian spatial process model and then
obtain approximate posterior inference for the entire dataset by optimally combining
the individual posterior distributions from each subset. Importantly, as is often desired
in spatial analysis, we offer full posterior predictive inference at arbitrary locations for
the outcome as well as the residual spatial surface after accounting for spatially oriented
predictors. The proposed framework is embarassingly parallelizable and leads to scalability
in presence of datasets with complex spatial associations. The full article can be found at
https://www.soe.ucsc.edu/sites/default/files/technical-reports/UCSC-SOE-17-07.pdf
