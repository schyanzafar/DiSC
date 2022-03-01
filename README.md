# DiSC
This repository contains the R scripts and data files used to produce the results, figures and tables reported in Zafar and Nicholls (2021) "Measuring diachronic sense change: new models and Monte Carlo methods for Bayesian inference".

**Data extraction and snippets:**
The ancient Greek data used to extract snippets for "kosmos" is freely available online. Links included in the file "Greek data extraction.R" point to the data sources, and the code may be used to extract the snippets. Alternatively, the file "kosmos_snippets.RData" contains the extracted snippets ready to use. Two versions of the "kosmos" snippets are included, i.e. including and excluding non-collocates.

The English data used to extract snippets for "bank" needs to be purchased from https://www.english-corpora.org/coha/. The file "COHA data extraction.R" may be used to extract the snippets once the data has been obtained. With permission from the data publisher, the extracted snippets are included in the file "bank_snippets.words.RData", as well as our manual sense annotation for these snippets, ready to use.

**Models and samplers:**
R scripts used to fit the DiSC and GASC models using the different MCMC samplers discussed in the paper. One of the snippet files mentioned above (or any other snippet file in the same format) needs to be loaded before the samplers can be run. Parameters such as number of MCMC iterations and runs need to be manually set.

**Toy data for validation:**
Contains an R script to generate a simple data example, together with some simulated toy data that were used to validate the models/samplers to a high precision (cf. start of Section 6 in the paper).

**Synthetic data experiments:**
Contains the code used to generate the synthetic data discussed in Section 8 and Appendix E of the paper.

**figures and tables.R:**
Contains the code used to produce all the figures, tables and results reported in the paper.
