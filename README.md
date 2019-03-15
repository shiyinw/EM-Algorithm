# EM-Algorithm
**A Small R Implement of EM Algorithm**

A study tracks the health of a population of N people over a time period of $T$ years. 

All members of the population start off healthy, and by the end of the study some have contracted an infectious disease at least once. Let $y_i$ be a Bernoulli random variable taking on the values $\{0,1\}$ that indicates whether subject i has ever contracted the disease by the end of the study (note that this subject could have been infected more than once). Put $y = (y_1,...,y_N)$. We also know whether or not each subject has been exposed to the disease each year. Let $μ_{ij} = 1$ if subject i has been exposed to the disease during year $j$, and $μ_{ij} = 0$ otherwise. 

Our goal is to estimate the infection rate $r_j$ for each year $(j = 1,2,...,T)$ of the study. Put $r = (r_1,...,r_T)$. 