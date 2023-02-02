# Chi-Squared Tests

This lecture is to show another example of a hypothesis tests and can be used in the A/B test lectures. This is meant to also solidify the concept of hypothesis test in using a statistic and a distribution to get a p-value.

## Learning Goals

- Understand how the χ2-statistic and tests are similar to other hypothesis tests (t-test, ANOVA, etc.)
- Calculate the χ2-statistic
- Perform a χ2 goodness-of-fit test
- Perform a χ2 test for independence

## Lecture Materials

[Jupyter Notebook: Chi-Square](chi_squared.ipynb)

## Lesson Plan

### Introduction and Non-parametric Tests (10 Mins)

Relate how the tests we've learned so far are similar but different. Explain why we have non-parametric tests.

### Chi-Square Test/Distribution (5 Mins)

Relat how we have a new statistic and distribution but it's the same process of finding a p-value (area under the curve from statistic) to compare with our significance level.

### 𝜒2 Goodness-of-Fit Test (20 Mins)

Explain the concepts for the goodness-of-fit test and the assumptions used. Then walk through the full procedure of performing the test and interpretting it for the hypothetical stakeholder. Show the simple SciPy method to perform test.

### 𝜒2 Test for Independence (15 Mins)

Similar to the goodness-of-fit test. End with showing how to do it in SciPy.

### Exercise (10 Mins)

Given enough time, allow the students to perform the exercise as breakout groups or as one large group.

## Tips

- (Victor Geislinger) Take time in explaining how this test is similar to past tests. I found that this being their 4th hypothesis tests, they should start to see the connection.
