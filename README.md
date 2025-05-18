# MasterThesis
The repository includes:
- the unity project folder for a gamified NF task
- the unity project folder for a standard NF task
- data (pseudonymized) + analysis of BCI task accuracy and user experience:
  * R: acc_bayesian_stats for the Bayesian t-test comparing accuracy in the gamified against the standard condition
  * R: Bayesian_ANOVA for a Bayesian 2x3 repeated measures ANOVE for a more detailed analysis of the differences in accuracy between the gamified and standard condition
  * R: order_bayesian_stats for a Bayesian t-test to check for a novelty effect
  * R: questionnaire_bayesian_stats for the Bayesian analysis of differences in the user experience for the gamified and the standard condition
  * JASP: Multinomial_preference for the Bayesion analysis of the preferences for either, both, or neither condition 
  * python: preparationStatisticsAccData, preparationStatisticsGEQData, preprocessGameData, preprocessStandardData for the preprocessing and some EDA & plotting of the accuracy and experience data 
(Note: the preparationStatisticsGEQData.ipynb python notebook will not run from the top, as the original data is not included in this repository for privacy protection reasons -- start running from later cell with cleaned data included in the folder.) 

User experience data was obtained using the game experience questionnaire (see IJsselsteijn, W. A., De Kort, Y. A., & Poels, K. (2013). The game experience questionnaire.)


