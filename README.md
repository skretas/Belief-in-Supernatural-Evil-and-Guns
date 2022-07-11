### Belief-in-Supernatural-Evil-and-Guns


<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/20301691/178231479-ede57976-77d4-4ba9-88a1-4b6deb03bb57.png">
</p>

> In this assignment we will replicate a study of belief in supernatural evil and attitudes towards guns in the United States. The study is:

Christopher G. Ellison, Benjamin Dowd-Arrow, Amy M. Burdette, Pablo E. Gonzalez, Margaret S. Kelley, Paul Froese, 
"Peace through superior firepower: Belief in supernatural evil and attitudes toward gun policy in the United States", 
Social Science Research, Volume 99, 2021, https://doi.org/10.1016/j.ssresearch.2021.102595.

# Part 1:
Belief in Supernatural Evil Metric
In order to measure the belief in supernatural evil, we will use the answers to three questions asked by the participants in the survey:

- Whether the respondent believes in the devil.

- Whether the respondent believes in hell.

- Whether the respondent believes in demons.

- We will investigate how the answers to these three questions can be combined to a single metric. We will justify our approach.

# Part 2: 
Variables Selection
Apart from the belief in supernatural evil metric, we will use several other variables to control your estimates. The variables are (see Appendix B of the original publication):

> Dependent Variables

- Ban on Semi-Auto Guns
- Ban on High-Capacity Ammo Clips
- Banning Civilian Handguns
- Support for Concealed Carry Laws
- More Armed Security at Schools
- More Teachers/Faculty having Guns
- More Gun Safety Programs
- Expanded Mental Health Screening

> Independept Variables

- Religious Variables

  Attendance
  
    Bible (Human Error, History and Fables)---Biblical Inerrancy---Biblical Literalism

- Religious Affiliation

   Conservative Protestant---Mainline Protestant---Black Protestant---Catholic---Other---No Affiliation

- Political Ideology

- Age

- Sex

  Female
  Male

- Race

  White---Hispanic---African American/Black---Other

- Education

  Less Than High School---High School or Equivalent---Some College---College Degree---Post-graduate Degree
  
- Household Income

- Marital Status

  Not Partnered/Single---Married/Cohabitating
  
- Children

  No kids under 18 in home---Kids under 18 in home
  
- Area Demographics

  Small Town/Rural---Urban Area

- Region

  South---Other Region

We will derive descriptive statistics of our variables and encode them with dummy variables where needed.

# Part 3:
Predict Support for Various Gun Policies
We will then proceed to predict support for various gun policies from the metric of supernatural evil, controlling for background variables.

The gun policies are:

> Semi-Auto Weapons Ban

> High-Capacity Magazine Ban

> Cilivian Hand Gun Possession Ban

> Support for Concealed Carry

> More Armed Security at Schools

> More Teachers / Faculty with Guns

> Required Gun Safety Programs

> Expanded Mental Health Screening

We will discuss the effects and the strengths of the various predictors (metric of supernatural evil, which is our focal variable, 
plus any others that you see significant).

The research was reported in The Economist, on November 6, 2021, under the title "Belief in supernatural evil is a 
strong predictor of pro-gun beliefs" (United States section), 
available at https://www.economist.com/united-states/2021/11/06/belief-in-supernatural-evil-is-a-strong-predictor-of-pro-gun-beliefs. 
We will compare our results with the reporting of the research on the newspaper.

# Part 4:
Additional Estimations of the Strength of Predictors
In addition to logistic regression, we will run a complementary series of linear regressions to estimate the strength of the various predictors. 
In this way you will obtain standardized coefficients that are easier to interpret than the coefficients of logistic regression. For more on this approach, 
see: Von Hippel, Paul, 2015. “Linear vs. Logistic models: which is better, and when?” Statistical horizons. July 5. Retrieved on December 3, 2021. 
https://statisticalhorizons.com/linear-vs-logistic.

# Part 5: 
Compare with Decision Trees / Random Forest Estimators
Having worked with logistic and linear regression models, carry out predictions by using Decision Trees / Random Forests of our choice; 
we have to try different ones and pick up the best. Then, we will check if the predictors, primarily the belief in supernatural evil, 
make also a strong showing with the best model we have found.
