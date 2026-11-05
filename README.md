This repository accompanies the two studies on the six gold prospects of permit PR3280 at Pangi, Maniema (DR Congo), on the Twangiza–Namoya trend of the Karagwe–Ankole Belt. Both papers are submitted to the International Workshop on Applied AI & Mathematical Methods for Real-world Applications (A2MRA), April 13–15, 2027, Delft, Netherlands.
The two archives contain the full, self-contained analysis code behind the papers:
Code_Pangi_MMCM.zip — implementation of the replication-weighted Mean–Median Compromise Method, the empirical-Bayes grade model, the unsupervised anomaly score, the SMAA scenarios and the Gaussian-process surrogate with Bayesian active learning.

Code_Pangi_Pathfinders.zip — implementation of the compositional, rank-based and robust multivariate analyses used to assess the Au pathfinder elements (Pearson/Spearman/Kendall/proportionality, bootstrap, jackknife, cluster bootstrap, median+2MAD, MCD, isolation forest, LOF and Ward clustering on clr coordinates).

Environment. Python 3. The scripts were run with SciPy 1.18 and scikit-learn 1.9; no other non-standard dependency is required.

Random seeds. All randomness is controlled. The main analyses use seed 20261028. The SMAA scenarios use 3,000 draws each; the predictive scenario uses 2,000 draws for each estimate of τ²; the bootstrap uses 10,000 resamples; the Gaussian-process active-learning step uses 250 simulated future data sets × 300 posterior draws per action.

Data. The 20 rock-chip assays with coordinates are included in the archives and are also described in the papers. They are reproduced as supplementary material and will be deposited in a public repository upon acceptance.
