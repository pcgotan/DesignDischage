# Estimation of Design discharge

This is the statistical approach to estimate the design discharge (50 year return period flood) at a given site, by making use of given Hundred years of annual maximum daily discharge measured at 5 different sites.  
Given data is plotted and found a suitable distribution which fits this data among Exponential, Gaussian, Lognormal, Gamma, Pearson Type-III and Gumbel distributions.  
Several goodness-of-fit tests (Chi-squared, Kolmogorov-Smirnov and Anderson-Darling) also performed at 5% significant level and best distribution is chosen based on AIC, BIC values etc.  
Then the Design discharge is calculated for 50 year return period flood.

## Executive Summary

-   While going through this project the best-fitted distribution is identified out of given i.e. Gaussian, Log-Normal, Exponential, Pearson type III, Gamma on the basis of goodness-of-fit.
-   The given data set for annual daily maximum discharge for a hundred years is provided and discharge is assumed to be a random variable.
-   The probability distribution of various distribution is calculated by programming in Python language.
-   Chi-Squared, Kolmogorov-Smirnov and Anderson-Darling goodness-of-fit at 5% significance level is performed to select the best distribution out of the given distribution. Preference is given to the Anderson-Darling test.
-   The corresponding p-value is tabulated on the basis of which the distribution is selected.
-   The graph of the best-fitted distribution is attached along with the distribution. Then the corresponding design discharge is calculated for best-fitted distribution for the given data set.

## Methodology

Python language was used on Jupyter-notebook to define the distribution to calculate the probability distribution for these hundred data points. For the Chi-Squared test the data is divided into ten intervals of equal frequency. The three goodness of fit tests are defined then, and the value corresponding to 5% critical value for each distribution is calculated and compared with the statistical value of each distribution. The distributions which are within the 5% of critical value are accepted and the corresponding p-value is calculated using the critical value chart, this is done for each test. On the basis of these values, the best distribution is selected.
In this study, frequency Analysis was carried out using different distribution models such as Exponential, Gaussian, Lognormal, Gamma, Pearson Type-III and Gumbel distributions for each site. The annual peak flow series was used for this purpose and then Chi-squared, Kolmogorov-Smirnov and Anderson-Darling goodness-of-fit tests were performed at 5% significance level and the best distribution was selected. Then using the distribution that fitted best was used to calculate the 50-year return period discharge at each site.

## Resutls

Results and graphs are in `170492.pdf` file.
