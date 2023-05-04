Download Link: https://assignmentchef.com/product/solved-cs596-homework-3
<br>
<strong>Problem 1: </strong>Let <em>χ</em><sub>1</sub><em>,χ</em><sub>2 </sub>be random variables which 99% of the time are independent and Normally (Gaussian) distributed, both with mean 0 and variance 1 and 1% of the time they are independent and Normally distributed both with mean 0 and variance <em>σ</em><sup>2 </sup>6= 1. a) Compute the joint pdf of the two random variables.

<ol>

 <li>b) Examine if the two random variables are <em>independent</em>. c) Give an example of two random variables that are <em>uncorrelated </em>but not independent.</li>

</ol>

<strong>Problem 2: </strong>Let <em>χ,ζ </em>be random variables that are related through the equality

<em>ζ </em>= |<em>χ </em>+ <em>s</em>|<em>.</em>

<ol>

 <li>a) If the pdf of <em>χ </em>is <em>f<sub>χ</sub></em>(<em>x</em>) compute the pdf of <em>ζ </em>when <em>s </em>is a deterministic quantity. b) Repeat the previous question when <em>s </em>is a random variable independent from <em>χ </em>and takes only the two values 0 and 1 with probability 0.2 and 0.8 respectively. c) Under the assumptions of question b) compute the posterior probability P(<em>s </em>= 0|<em>ζ </em>= <em>z</em>). <em>Hint: For the computation of the pdf of a random variable the simplest way is to start with the computation of the cdf and then take the derivative. For b) use total probability.</em></li>

</ol>

<strong>Problem 3: </strong>You are given an <em>unfair </em>coin where every time you throw it the probability to observe “head” is <em>p </em>∈ (0<em>,</em>1) (and “tail” 1 − <em>p</em>) where <em>p </em>is unknown. Assume that you throw the coin <em>N </em>times and you report the sequence of heads (H) and tails (T). If <em>N<sub>h </sub></em>is the number of heads you observed and <em>N </em>− <em>N<sub>h </sub></em>the number of tails then: a) Find the probability of the specific sequence you have observed as a function of <em>p,N,N<sub>h</sub></em>. b) Compute the maximum likelihood estimator (MLE) of <em>p </em>if you are given such a sequence. Is the result familiar/expected? c) Compute the average of your estimate and the mean square error from the true unknown value <em>p</em>. What do you conclude about your estimate as <em>N </em>→ ∞?

<strong>Problem 4: </strong>Consider the random data {<em>x</em><sub>1</sub><em>,…,x<sub>N</sub></em>} and assume that they are Markov related as follows

<em>x<sub>n </sub></em>= <em>αx<sub>n</sub></em><sub>−1 </sub>+ <em>w<sub>n</sub>, n </em>= 2<em>,…,N,</em>

where |<em>α</em>| <em>&lt; </em>1, {<em>w<sub>n</sub></em>} are independent and identically distributed Gaussian random variables with mean 0 and variance 1 and independent from <em>x</em><sub>1</sub>. Random variable <em>x</em><sub>1 </sub>is also Gaussian with mean 0 and variance . a) Using the fact that linear combinations of Gaussians is also Gaussian show that all <em>x<sub>n </sub></em>are Gaussian.

<ol>

 <li>b) Find the joint probability density function of {<em>x</em><sub>1</sub><em>,…,x<sub>N</sub></em>} assuming <em>α </em>is given. c) Find the maximum likelihood estimator (MLE) of parameter <em>α</em>. <em>Hint: For b) use the fact that </em>{<em>x</em><sub>1</sub><em>,x</em><sub>2 </sub>− <em>αx</em><sub>1</sub><em>,…,x<sub>N </sub></em>− <em>αx<sub>N</sub></em><sub>−1</sub>} <em>are independent Gaussians.</em></li>

</ol>

<strong>Problem 5: </strong>Assume that you have two hypotheses H<sub>0</sub><em>,</em>H<sub>1</sub>. Under Hypothesis H<sub>0 </sub>your observation vector <em>X </em>= [<em>x</em><sub>1</sub><em>,…,x<sub>N</sub></em>]<em><sup>T </sup></em>is Gaussian with mean vector <em>µ</em><sub>0 </sub>and covariance matrix Σ<sub>0</sub>, while under H<sub>1 </sub>it is again Gaussian with mean <em>µ</em><sub>1 </sub>and covariance matrix Σ<sub>1</sub>. Assume that the two hypotheses are equiprobable (P(H<sub>0</sub>) = P(H<sub>1</sub>) = 0<em>.</em>5). a) Find the Likelihood ratio test (LRT) and its equivalent form by taking the logarithm on both sides of the inequality. b) What is the latter form reduced to when the two covariance matrices are equal (Σ<sub>0 </sub>= Σ<sub>1</sub>)? c) What if additionally the two means are equal? Does this make sense?