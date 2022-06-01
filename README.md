# UnderstandingPFI

This is the repository for the Econometrics course project.

## Problem
Globally, the past decade was characterized by the increasing restrictions on media and journalism in many countries. The enormous amounts of information and news fuel divisions even in democratic societies both on a national and international level. The increasing online presence becomes the ground for spreading fakes and bias, as well as an opportunity for authoritarian regimes to suppress freedom of speech and belief in their states.

Locally, in Ukraine, the propaganda war played an incredibly powerful role in preparing the grounds for the armed russian invasion in February. During the conflict, we already saw many attempts from the occupants to deny people’s right to information and expression and to prevent journalists from covering war crimes the russian army conducts.

## Aim of the project
The task of the project is to prove that free press is influenced by a variety of economic, legal, and political characteristics. This would mean that in order to counter the problems caused by the suppression of press freedom, a country needs to improve in other aspects of development at the same time. The authors intend to do so by exploring the correlation between the press freedom index and such variables as Education index, Corruption, Judicial independence and more.

## Outcomes
The strongest correlation is with the judiciary independence coefficient (-0.88), which can be explained under the presumption that the freedom of the press is regulated by the law, and uncorrupted courts are less likely to restrict expression on falsified grounds. According to the regression output, 85% of the data is explained by the model, but with a relatively low log likelihood and relatively high AIC, which is not ideal. Most of the independent variables logically influence the dependent variable.

After fitting a new model without the insignificant variables, the authors concluded that it performed better. Although the R-squared remained pretty much the same, the F-statistic and associated p-value indicate the significance of the new model over an intercept-only one.

## Usage
To run the code, one needs to copy the **main.ipynb** notebooks from this repository to a Google Colaboratory and upload all the files from the **data** folder. All the code is reusable and can be re-run as many times as one needs through the notebook. 

## Further improvements
- Based on the conducted tests, perform the Fisher test for joint significance and experiment with fitting models using different subsets of the independent variables.
- Investigate causality between certain variables using Granger causality test.
- Look at the countries in context one at a time, taking into account political and economic environments over some time. This way, more exact results can be obtained.
