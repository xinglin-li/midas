# MIDAS
* The repository contains implementaions of Mixed-data sampling (MIDAS).[^1][^2]
* Currently, it is based on the package by Jonas Striaukas (https://github.com/jstriaukas/midasml). [^3][^4], the language of that package is R. Although it has [Python Version](https://github.com/jstriaukas/midasmlpy), it contains a lot of bugs. In addition, some of the code is also not fully optimized.
* The main goal of this repository is to build a python version MIDAS package
* I'll start with debugging the code mentioned above, and try to optimize it. 
* I also have the plan to introduce PyTorch to this repository, which would benefit building a hybrid model combines DNNs and MIDAS together. 

# Working Log
* fixed bugs in date_functions.mixed_freq_data
* optimized date_functions.is_na & date_functions.date_vec
* fixed bugs in midas_polynomials.gb


## Reference:
[^1]: Eric Ghysels, Pedro Santa-Clara, Rossen Valkanov. (2004)  *The MIDAS touch: Mixed data sampling regression models*
[^2]: Eric Ghysels, Arthur Sinko, Rossen Valkanov. (2007) *MIDAS regressions: Further results and new directions*
[^3]: Babii, A., Ghysels, E., & Striaukas, J. Machine learning time series regressions with an application to nowcasting, (2022) Journal of Business & Economic Statistics, Volume 40, Issue 3, 1094-1106. https://doi.org/10.1080/07350015.2021.1899933. ↩
[^4]: Babii, A., Ghysels, E., & Striaukas, J. High-dimensional Granger causality tests with an application to VIX and news, (2022) Journal of Financial Econometrics, Forthcoming. ↩
