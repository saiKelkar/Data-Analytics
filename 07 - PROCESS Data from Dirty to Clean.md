Data integrity - the accuracy, completeness, consistency, and trustworthiness of data throughout its lifecycle. 
Data manipulation - the process of changing data to make it more organized and easier to read. 

Other threats to data integrity:
- Human error
- Viruses
- Malware
- Hacking
- System failures

Types of insufficient data:
- data from only one source
- data that keeps updating
- outdated data
- geographically-limited data

Ways to address insufficient data:
- identify trends with the available data
- wait for more data if time allows
- talk with stakeholders and adjust your objectives
- look for new dataset

![[Pasted image 20251103104724.png]]

Data issue 1: no data
(possible solutions) 
- gather the data on a small scale to perform a preliminary analysis and then request additional time to complete the analysis after you have collected more data.
- if there isn't time to collect data, perform the analysis using proxy data from other datasets. (this is the most common workaround)

Data issue 2: too little data
(possible solutions)
- do the analysis using proxy data along with actual data.
- adjust your analysis to align with the data you already have.

Data issue 3: wrong data, including data with errors
(possible solutions)
- if you have wrong data because requirements were misunderstood, communicate the requirements again.
- identify errors in the data and, if possible, correct them at the source by looking for a pattern in the errors.
- if you can't correct data errors yourself, you can ignore the wrong data and go ahead with the analysis if your sample size is still large enough and ignoring the data won't cause systematic bias. 


Margin of error - maximum amount that the sample results are expected to differ from those of the actual population.
to calculate margin of error, we need - population size, sample size, confidence level

e.g. in a survey about a new type of protein bar, 70% of respondents reported they would buy the bar again. The margin of error for the survey is 4%. Based on the margin of error, what range reflects the population's true response?

sample proportion (p) = 70% = 0.7
margin of error (ME) = 4% = 0.04

confidence interval (range) for the true population proportion is:
range = p (+-) ME

Lower limit = 0.7 - 0.04 = 0.66
Upper limit = 0.7 + 0.04 = 0.74

so true population proportion likely lies between 66% and 74%