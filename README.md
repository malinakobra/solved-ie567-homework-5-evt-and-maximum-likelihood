Download Link: https://assignmentchef.com/product/solved-ie567-homework-5-evt-and-maximum-likelihood
<br>



<em>Assignment.</em>  You have the S&amp;P 500 index (SPX) data in the.csv file F567.s2020.HW5.data.csv.  You want to use extreme value theory (EVT) and the continuously compounded returns you compute from the SPX data to estimate the probability of a large decline in the index.

In this homework you should work with the loss <em>X</em> = −<em>R</em> rather than the return <em>R</em>.  For example, the December 11, 2015 return is <em>R</em> = −0.01961.  Instead of using this number, use the loss <em>X</em> = −<em>R</em> = 0.01961.

<ol>

 <li><strong>Mean excess function</strong> (1.5 points) For each threshold <em>u</em> ∈ {0.010, 0.012, 0.014, …, 0.05} compute the mean excess loss <em>e</em>(<em>u</em>) given by the second displayed equation on slide 11 of the lecture notes EVT and VaR.ppt. (You should compute 21 different mean excess losses.)  Prepare a graph that shows the mean excess loss <em>e</em>(<em>u</em>) as a function of the threshold <em>u</em>.  (The threshold <em>u</em> should be on the horizontal axis.)</li>

</ol>




<ol start="2">

 <li><strong>Losses beyond the threshold </strong>(0.5 point) Examining the mean excess function, you decide that the mean excess function is linear beyond <em>u</em> = 0.022. Thus, you decide that the GPD can be used to approximate the conditional density of excess losses beyond the threshold <em>u</em> = 0.022.  How many losses are greater than or equal to 0.022?</li>

 <li><strong>Maximum likelihood estimation of the GPD parameters </strong>(5 points) Using the losses <em>X</em> such that <em>X</em> ≥ 0.022, compute the excess losses <em>X</em> – <em>u</em> = <em>X</em> – 0.022.  Then use the excess losses, the density function of the GPD, and the method of maximum likelihood to estimate the parameters ξ and β of the GPD.  What are your estimates of the parameters ξ and β?</li>

 <li><strong>Conditional density function</strong> (1 point)  Using the density function of the GPD and your parameter estimates from Question 3, create a figure that shows the conditional density function of the losses, condition on the loss being greater than or equal to 0.022.  Your figure should show the conditional density for losses between 0.022 and 0.10.</li>

 <li><strong>Probabilities of various losses</strong> (2 points) What is your estimate of the probability that the loss <em>X</em> is greater than or equal to 0.022?  (That is, what is your estimate of <em>P</em>(<em>X</em> ≥ 0.022)?)  What is your estimate of <em>P</em>(<em>X</em> ≥ 0.05)?  What is your estimate of <em>P</em>(<em>X</em> ≥ 0.10)?  Create a figure showing <em>P</em>(<em>X</em> ≥ <em>x</em>), for <em>x</em> ∈ [0.022, 0.10].</li>

</ol>

1