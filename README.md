java c
MGTSC 212 Fall 2024 
Lab Assignment 3 
Due by 11:59 PM, November 08, 2024 
Total points: 82Perform. all  calculations  using  Excel, when  calculations  are  needed: no  other  source  of answers  requiring calculation will be permitted. Some of the answers will automatically appear in the Answer worksheet (except tables and graphs). Leave the table(s) and graph(s) within the respective worksheet unless instructed to copy-paste them to the Answer sheet. After calculating answers on the designated worksheet for each problem, they should appear on the Answer sheet automatically. If they do not automatically appear in the Answer sheet, Copy and Paste 123 (Values) to the Answer sheet without rounding. Do not type values into the Answer sheet that you calculate elsewhere. Any numbers written directly without Excel cell reference or formula into the answer cells will get 0 unless otherwise specified [e.g., you can type in the given x-values while calculatingY(̂)]. Rounded numbers will be treated as errors. You can type degrees of freedom whenever applicable (as there is no rounding involved).
[3 points] Put your student ID and name in the designated shaded cells in the Answer sheet.
Questions: 
1.   [5 points] In the Rand worksheet, you are given a randomly generated number between 0 and  1 in cell A4. Treat this value as the right tail area under an F-distribution (numerator and denominator DFs are specified within the worksheet). Now simulate a value in cell B4 from the F-distribution such that the area to the right reflects the value in A4. Simulation means generating a value from F-distribution with given specifications. Copy the value from B4 as Paste Special in cell C7 of the Answer worksheet [paste as values  123, slide #45 from Lab-cycle1_data_summary]. Note that, failure to fulfill the instructions for the Rand portion, as outlined above, will result in a 20% deduction from your earned marks for Lab Assignment 3.
Estimating regression models to predict 5 Year Average Return (Y) Data description: 
Fund Type: The types of funds are labeled as DE (Domestic Equity), IE (International Equity), and FI (Fixed Income). Respective dummy variables are created.
Morningstar Rank: The risk-adjusted star rating for each fund; Morningstar ranks go from a low of 2-Star to a high of 5-Stars. Respective dummy variables are created.
5-Year Average Return (%): The average annual return for the fund over the past five years Net Asset Value ($): The closing price per share on December 31, 2007.
Expense Ratio (%): The percentage of assets deducted each fiscal year for fund expenses.Interaction variables between Expense Ratio and Fund Type dummies are created: ERFI, ERDE, and ERIE to check the joint impact of Expense Ratio and Fund Type dummies on 5 Year Average Return. The inclusion of interaction variables indicates different impacts (slope) of the Expense Ratio on Return for different fund types.
Use α = 10% for all hypothesis testing-related questions.
2.   [8 points] Scatter diagram of 5-Year Average Return versus Net Asset Value ($) 
a.    [4 pts.] Go to the Data worksheet. Create a scatter diagram of the 5-Year Average Return as the dependent variable (y-axis) versus the Net Asset Value ($) (x-axis). You can place the plot in E40 (that means to start creating the blank scatter plot from cell E40).
b.   [4 pts.] Add the axis labels, linear trend line, trend equation, and R2  value within the plot.
3.   [11 points] Start within the Data worksheet and run a simple linear regression of 5-Year Average Return (%) on Net Asset Value ($), and select cell E1 in the Model1 worksheet as the Output Range. We call this Model 
1. Answer the following questions within the Model1 Worksheet.
a.    [1 pt.] Provide the p-value indicating whether the slope coefficient of the Net Asset Value ($) has a significant impact on the 5-Year Average Return based on Model 1.
b.   [1 pt.] Based on the above p-value, what is your conclusion: select the right answer from the drop-down menu (using α  = 10%)?
c.    [1 pt.] What proportion of total variability in 5-year Average Return is explained by the regression on Net Asset Value ($)?
d.   [2 pt.] What is the estimated value of σ in Model 1 [one of the model assumptions is ε~N(0, σ 2)]?
e.    [0.5 pts.] What are the numerator degrees of freedom for the F-statistic provided under the ANOVA section of Model 1?
f.    [0.5 pts.] What are the denominator degrees of freedom for the F-statistic provided under the ANOVA section of Model 1?
g.   [1 pt.] What is the estimated intercept value in Model 1?
h.   [1 pt.] What is the estimated slope coefficient value of the Net Asset Value ($) in Model 1?
i.    [3 pts.] What is the predicted value of 5-Year Average Return for a fund with a Net Asset Value = $35.5 in Model 1?
4.   [16 points] Start within the Data worksheet and run a multiple linear regression of 5 Year Average Return on Net Asset Value ($), Expense Ratio (%), and the Fund-type dummies; and select cell E1 in the Model2 worksheet as Output Range. We call this Model 2. Answer the following questions within the Model2 Worksheet. Use International Equity as the base case.
a.    [1.5 pts.] Provide the F-statistic value to test that the regression model of ‘5 Year Average Return on Net Asset Value ($), Expense Ratio (%) and the Fund-type dummies ’ is significant.
b.   [1.5 pts.] What proportion of total variability in 5-代 写MGTSC 212 Fall 2024 Lab Assignment 3Matlab
代做程序编程语言Year Average Return is explained by the regression on Net Asset Value ($), Expense Ratio (%), and the Fund-type dummies?
c.    [1 pt.] What is the regression degrees of freedom in Model 2?
d.   [1 pt.] What is the error degrees of freedom in Model 2?
e.    [1 pt.] How many population slope coefficients are significantly non-zero in Model 2 (using α = 10%). f.     [1.5 pts.] What is the estimated intercept value in Model 2?
g.   [1.5 pts.] What is the estimated slope coefficient value of the Expense Ratio in Model 2? h.   [1.5 pts.] What is the estimated slope coefficient value of Net Asset Value in Model 2?
i.    [1.5 pts.] What is the estimated standard error of the coefficient of Expense Ratio in Model 2?
j.    [4 pts.] What is the predicted value of 5-Year Average Return for an International Equity fund with Net Asset Value = $35.50 and Expense Ratio = 1.3% in Model 2? [Note. Expense Ratio is measured in %, so don’t convert 1.3% further]
5.   [11 points] Continue on the Model 2 Worksheet. Inference about β Expense Ratio:  population  slope of the Expense Ratio.
a.    [3 pts.] What is the test statistics value totest H0: β Expense Ratio  = 10 vs. H0: β Expense Ratio  ≠ 10?
b.   [2 pts.] What is the p-value for the above test H0: β Expense Ratio  = 10 vs. H0: β Expense Ratio  ≠ 10?
c.    [1 pt.] What is your conclusion for the above test: select the most appropriate conclusion from the drop- down menu (using α  = 10%).
d.   [3  pts.]  What   is  the  MOE  value   (margin   of  error)  to   estimate  the   90%  confidence  interval of β Expense Ratio?
e.    [1 pt.] What is the Lower limit of the 90% confidence interval of β Expense Ratio? f.    [1 pt.] What is the Upper limit of the 90% confidence interval of β Expense Ratio?
6.   [16 points] Start within the Data worksheet and run a multiple linear regression of 5-Year Average Return on Net Asset Value ($), Expense Ratio (%), the Fund-type dummies, and the interaction variables between Expense Ratio with Fund-type dummies. Select cell E1 in the Model3 worksheet as the Output Range. We call this Model 3. Use International Equity as the base case.
a.    [0.75 pts.] What is the p-value to check if Model 3 is statistically significant (i.e., p-value to check if the prediction of 5-Year Average Return based on Model 3 will provide a better estimate than by pure chance)?
b.   [0.75 pts.] Can you conclude if Model 3 is a good predictive model statistically speaking using α = 1%? Select the right answer from the drop-down menu.
c.    [1 pt.] What are the regression degrees of freedom in Model 3?
d.   [1.5 pts.] What is the estimated intercept value in Model 3?
e.    [1.5 pts.] What is the estimated slope coefficient value of the Expense Ratio in Model 3? f.    [1.5 pts.] What is the estimated slope coefficient value of Net Asset Value in Model 3?
g.   [1.5 pts.] What is the estimated slope coefficient value of the Fund-type dummy DE in Model 3?
h.   [1.5 pts.] What is the estimated slope coefficient value of the interaction variable ERDE in Model 3? i.    [6 pts.] What is the predicted value of 5-Year Average Return for a Domestic Equity fund with a Net
Asset Value = $35.50 and Expense Ratio = 1.3% in Model 3? [Note.Expense Ratio is measured in %, so don’t convert 1.3% further]
7.   [12 points] Partial F-test: A partial F-test can be used to compare two regression models when they both have the same dependent variable, but only when the list of the explanatory variables for the one (the reduced model) is a subset of the list of the explanatory variables included in the other one (the full model). As an example under the context of this assignment, with the Partial F-test, we will be able to test whether adding the interaction variables to Model 2 would improve the prediction of Return given other factors remained fixed. In other words, we can test whether Model 3 is significantly better than Model 2 (using α  = 10%).For partial F-test we work with nested models: The full model has all the variables and the Reduced (or Restricted) model has all the ‘other’ variables except the group of variables you are testing the joint significance of. For example, if you want to test the joint significance of all the interaction variables (ER and Fund-type dummies), then
Full model = ‘Other variables’ + interaction variables (total p no. of explanatory variables); and Reduced model = ‘Other variables’ (total q no. of variables). So, the Reduced model is a subset of the Full model.Partial F − stat =  ,   follows   F-distribution   with   numerator   df   =   p-q   and denominator df = n-p-1; where p-q is also the number of population slopes-coefficients you are testing with the Partial F-test.  Fill in the ANOVA table values from your estimated Model 2 and Model 3 and then calculate the partial F-statistic value and provide the related conclusion. 
Checking submission (these steps are necessary for checking Midterm submissions as well) 
Submit the completed Excel file (you need to click the ‘Submit” button to complete any submissions). You can submit any assessments multiple times.Close all the existing Excel files on your computer. Download your submission, open it, and make sure that the file you submitted is the one you intended. Your latest submitted file will be graded (for example, if you submit a blank or a shadow file, you will get a 0 on the assignment).

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
