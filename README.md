# sdr_ai

This repository contains MATLAB code to implement **Sufficient Dimension Reduction with Additional Information** based on the method proposed in the following article currently under review:

* Ibañez, I.,  Forzani, L., & Tomassi, D. (2024). Generalized kernel-based method for sufficient dimension reduction with additional information.

It also includes the example of pancreatic cancer data presented in the mentioned article.


## Instructions

* Extract the file sdr_ai.zip
* Run setpaths.m to add all subfolders to the MATLAB search path.
* Explore the example located at example/pancancerAI.m


## Notes

1. The **sdrAI** function implements a couple of specific cases of what we call the *generalized two-step method*, using kernel-based dimension reduction methods: RKEF and COIR. 
The user can make necessary modifications if they wish to use other dimension reduction methods in any of the two steps.
2. Pancreatic cancer data used is from International Cancer Genome Consortium ([ICGC](https://dcc.icgc.org/)), but it is also available in a shared folder: [click here](https://drive.google.com/drive/folders/1JeULeRrNv3sOc_-XGVfl-Qc-rvlcspp5?usp=sharing).



## References

Some of the functions included in this package rely on procedures previously published in:

* Cook, R. D., Forzani, L.M., & Tomassi, D. R. (2011). LDR: A Package for Likelihood-Based Sufficient Dimension Reduction. *Journal of Statistical Software*, 39(3), 1–20. https://doi.org/10.18637/jss.v039.i03
* Ibañez, I., Forzani, L. & Tomassi, D. (2022). Generalized discriminant analysis via kernel exponential families. *Pattern Recognition*, 132, 108933. https://doi.org/10.1016/j.patcog.2022.108933.
* Kim, M., & Pavlovic, V. (2011). Central subspace dimensionality reduction using covariance operators. *IEEE Transactions on Pattern Analysis and Machine Intelligence*, 33(4), 657–670.
