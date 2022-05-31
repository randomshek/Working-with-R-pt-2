# Working-with-R-pt-2

**plankton.csv:** contains records plankton data where the levels of Pseudonitzschia
were more than 700 (in 100 cells/litre). The levels of the other 2 plankton cell varieties
may be zero, or positive (in cells/litre).

Here, we analyse and visualise a dataset related to plankton in the water where shellfish are farmed. Using a dataset which contains the monitoring of planktons cells Pseudonitzschia (measured in hundreds of cells per litre), Alexandrium (measured in cells per litre) and the little known Robgordia (measured in cells per litre). This is important as these cells are capable of producing harmful toxins.

At shellfish farms, water samples are regularly taken and, for each plankton variety, amounts 
are recorded (in the units of measure specified earlier) as well as the species farmed 
(common mussels, common cockles and oysters).

## TASKS
Carried out the following tasks in R:
1. Use univariate statistics to analyse the plankton dataset. Do not use any plots.
2. Use a boxplot to show the distribution of Pseudonitzschia and a second one to show 
the distribution of water temperature. Comment on the plots.
3. Use univariate statistics to compare data for Pseudonitzschia in year 2021 with its 
data in previous years (consider all previous years together). Comment on the results. 
Do not use plots.
4. Produce two histograms: one showing an attribute with a skewed distribution and 
one showing an attribute with a normal distribution. Comment on the plots.
5. Produce a bar plot for Species. Comment on the plot.
6. Produce a pie chart for an attribute of your choice. Comment on the plot.
7. Use a plot to show values of Robgordia.Sp against values of Pseudonitzschia.A.Sp 
where the species is either common mussels or pacific oysters. Use colour to show 
the Species. Comment on the plot.
8. Use a plot to show Alexandrium.Sp in different regions by farming species. Use jitter 
if needed. Comment on the plot.
9. Find a pair of plankton species which are correlated and a pair which are not 
correlated. Do not use plots. Justify your answers.
10. Produce a line plot which shows the water temperature (y axis) against the sample 
index (x axis), for samples of common cockles and pacific oysters. Both lines (one per 
species) should be shown in the same plot.
11. Produce a linear regression model of Pseudonitzschia.A.Sp on Robgordia.Sp for 
Common mussels. Estimate the value of Pseudonitzschia.A.Sp for a values of 
Robgordia.Sp of 1000, 2500 and 4000 cells per litre. Justify the appropriateness of the 
model and comment on any concerns you may have about your predictions. Can you 
use this model to predict the value of Rogbodia?
12. Create a data frame with three columns: month, year, and the mean of the water 
temperatures observed in the plankton dataset during that month-year period. Check 
whether the mean temperature is 12 degrees at 99% confidence. Without conducting 
another test, can you say whether the mean temperature is 12.5 at 95% confidence?
13. You suspect that the water temperature is affected by the period of the year. Use the 
plankton dataset to produce a test to check this suspicion, clearly highlighting the 
NULL hypothesis and the alternative hypothesis and justifying whether the suspicion 
is supported by the data or not. Justify your answer.
14. NO CODE NEEDED FOR THIS TASK. You think that an ANOVA test may be useful to 
determine whether different species are farmed in different water temperatures. 
Comment on any concerns that you may have if applying this test to the plankton 
dataset.
15. Using the plankton dataset (or one derived from it), select some data that has not 
been visualised already, and produce TWO alternative plots of that data which you 
have not presented earlier. One of the plots should be very informative and effective 
while the other one should have deliberate deficiencies. Compare and contrast the 2 
plots, clearly highlighting their merits and drawbacks.

