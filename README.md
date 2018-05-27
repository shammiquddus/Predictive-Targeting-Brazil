# Predictive Targeting
## Increasing the efficiency of social service delivery in Brazil
Creating a Proxy Means Test (PMT) for poverty targeting in Brazil using the national PNAS dataset. We propose a predictive targeting model that uses a set of easily observable poverty indicators and removes the dependency on self-reported income for social benefits targeting.

Poor households in Brazil have many differentiating characteristics compared to the nonpoor.These differences can be used to create a precise predictive targeting model. For example, households are more likely to be poor if headed by a female or if the household head cannot read and write. Poorer households tend to be younger and have a lower proportion of adult household members being currently employed. Unsurprisingly, the quality of their dwelling is of lower quality, they have lower access to public utilities, and own fewer material assets. The proposed predictive targeting model uses 45 of these differentiating characteristics to predict the probability of a household being poor. Information on these 45 indicators will be collected through a one-page survey and entered into an **probit model** that will assign each household a ‘poverty score’ between 0 and 1. 

The threshold score proposed is **0.20** which means a household will be eligible for benefits if the probability of its being poor is equal or greater than 20%. This cutoff results in an undercoverage (exclusion of deserving poor households) and leakage (inclusion of non-poor households) of **39%** each. This is a significant improvement on an undercoverage rate of 59% and leakage rate of 49% of the Bolsa Familia Program reported in 2004. With a concurrent reduction of both undercoverage and leakage, the MDS can extend its benefits to a greater number of deserving poor and minimize wastage by eliminating a greater number of non-poor households.

![graph](https://user-images.githubusercontent.com/31656996/40581970-011eb2da-611c-11e8-90ff-587d3b9714fd.jpg)


