Download Link: https://assignmentchef.com/product/solved-economics7103-hw5
<br>
This assignment continues to use the same data from the previous homework.

You have imaginary data on the monthly yields for Pacific fish trawling companies (<em>fishbycatch.csv</em>). An environmental nonprofit targeted these firms and implemented a program designed to reduce bycatch. As part of the program, the nonprofit contacted firm managers and provided information about best practices to reduce bycatch. The program was implemented in two phases. In January 2018, the nonprofit contacted half of the firms. The next year in January 2019, the nonprofit contacted the remaining firms.

You are interested in whether the program worked or not and decide to use this panel data to empirically estimate the effect of the program. You realize that you have a treatment and control group in pre- and post-treatment periods due to the program’s rollout, so you think a difference-in-differences design is a good approach. You have the following data:

<table width="422">

 <tbody>

  <tr>

   <td width="67">Variable</td>

   <td width="355">Description</td>

  </tr>

  <tr>

   <td width="67"><em>firm</em></td>

   <td width="355">Firm identification number</td>

  </tr>

  <tr>

   <td width="67"><em>shrimp*</em></td>

   <td width="355">Pounds of shrimp in month *</td>

  </tr>

  <tr>

   <td width="67"><em>salmon*</em></td>

   <td width="355">Pounds of salmon in month *</td>

  </tr>

  <tr>

   <td width="67"><em>bycatch*</em></td>

   <td width="355">Pounds of bycatch in month *</td>

  </tr>

  <tr>

   <td width="67"><em>firmsize</em></td>

   <td width="355">Size of fishing fleet</td>

  </tr>

  <tr>

   <td width="67"><em>treated</em></td>

   <td width="355">=1 if firm received information treatment in January 2018</td>

  </tr>

 </tbody>

</table>

Table 1: Variable descriptions for homework 4.

Report your results from both questions in the same table. Omit the estimates for the time dummies and instead indicate in a single row that time dummies are present like in the papers we have been reading.

<ol>

 <li>Suppose you would like to use the full monthly sample to improve on what you did in Homework4. Using the full monthly sample, estimate the treatment effect of the program on bycatch using a regression-based difference-in-differences estimator using the regression:</li>

</ol>

<em>bycatch<sub>i,t </sub></em>= <em>c<sub>i </sub></em>+ <em>λ<sub>t </sub></em>+ <em>γg</em>(<em>i</em>) + <em>δtreat<sub>i,t </sub></em>+ <em>ε<sub>i,t</sub>.                                                         </em>(1)

where <em>λ<sub>t </sub></em>are indicator variables for each time period. Report and interpret the results using the same cluster-robust standard errors you used in Homework 4. How did your results change?

<ol start="2">

 <li>Suppose now that you want to control for firm size and other covariates that change over time such aspounds of shrimp and salmon harvested. Estimate the difference-in-differences regression with added controls:</li>

</ol>

(2)

where <em>X<sub>i,t </sub></em>includes fimr size, pounds of shrimp harvested by firm <em>i </em>in month <em>t</em>, and pounds of salmon harvested by firm <em>i </em>in month <em>t</em>. How do your results change from question 1?