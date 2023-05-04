Download Link: https://assignmentchef.com/product/solved-cs7641-homework-1-linear-algebra
<br>
<h2>Determinant and Inverse of Matrix</h2>

Given a matrix <em>M</em>:

<ul>

 <li>Calculate the determinant of <em>M </em>in terms of <em>r</em>. [4pts]</li>

 <li>For what value(s) of <em>r </em>does <em>M</em><sup>−1 </sup>not exist? Why? What does it mean in terms of rank and singularity of <em>M </em>for these values of <em>r</em>? [3pts]</li>

 <li>Calculate <em>M</em><sup>−1 </sup>by hand for <em>r </em>= 4. [5pts] (<strong>Hint 1: </strong>Please double check your answer and make sure <em>MM</em><sup>−1 </sup>= <em>I</em>)</li>

 <li>Find the determinant of <em>M</em><sup>−1 </sup>for <em>r </em>= 4. [3pts]</li>

</ul>

<h2>1.2         Characteristic Equation</h2>

Consider the eigenvalue problem:

<em>Ax </em>= <em>λx,x </em>6= 0

where <em>x </em>is a non-zero eigenvector and <em>λ </em>is eigenvalue of <em>A</em>. Prove that the determinant |<em>A </em>− <em>λI</em>| = 0.

<strong>1.3 Eigenvalues and Eigenvectors [10pts] </strong>Given a matrix A:

<ul>

 <li>Calculate the eigenvalues of <em>A </em>as a function of <em>x </em>[5 pts]</li>

 <li>Find the normalized eigenvectors of matrix <em>A </em>[5 pts]</li>

</ul>

<h1>2                   Expectation, Co-variance and Independence [18pts]</h1>

Suppose <em>X,Y </em>and <em>Z </em>are three different random variables. Let <em>X </em>obey a Bernouli Distribution. The probability disbribution function is

<em>c </em>is a constant here. Let <em>Y </em>obey a standard Normal (Gaussian) distribution, which can be written as <em>Y </em>∼ <em>N</em>(0<em>,</em>1). <em>X </em>and <em>Y </em>are independent. Meanwhile, let <em>Z </em>= <em>XY </em>.

<ul>

 <li>Show that <em>Z </em>also follows a Normal (Gaussian) distribution. Calculate the Expectation and Variance of <em>Z</em>. [9pts] (<strong>Hint: </strong>Sum rule and conditional probability formula)</li>

 <li>How should we choose <em>c </em>such that <em>Y </em>and <em>Z </em>are uncorrelated(which means <em>Cov</em>(<em>Y,Z</em>) = 0)? [5pts]</li>

 <li>Are <em>Y </em>and <em>Z </em>independent? Make use of probabilities to show your conclusion. Example: <em>P</em>(<em>Y </em>∈ (−1<em>,</em>0)) and <em>P</em>(<em>Z </em>∈ (2<em>c,</em>3<em>c</em>)) [4pts]</li>

</ul>

<h1>3           Optimization</h1>

Optimization problems are related to minimizing a function (usually termed loss, cost or error function) or maximizing a function (such as the likelihood) with respect to some variable x. The Kuhn-Tucker conditions are first-order conditions that provide a unified treatment of constraint optimization. In this question, you will be solving the following optimization problem:

max <em>f</em>(<em>x,y</em>) = 2<em>x</em><sup>2 </sup>+ 3<em>xy </em><em>x,y</em>

s.t.

<ul>

 <li>Specify the Legrange function [2 pts]</li>

 <li>List the KKT conditions [2 pts]</li>

 <li>Solve for 4 possibilities formed by each constraint being active or inactive [5 pts]</li>

 <li>List all candidate points [4 pts]</li>

 <li>Check for maximality and sufficiency [2 pts]</li>

</ul>

<h1>4           Maximum Likelihood</h1>

<h2>4.1         Discrete Example</h2>

Suppose we have two types of coins, A and B. The probability of a Type A coin showing heads is <em>θ</em>. The probability of a Type B coin showing heads is 2<em>θ</em>. Here, we have a bunch of coins of either type A or B. Each time we choose one coin and flip it. We do this experiment 10 times and the results are shown in the chart below. (<strong>Hint: </strong>The probabilities aforementioned are for the particular sequence below.)

<table width="131">

 <tbody>

  <tr>

   <td width="86">Coin Type</td>

   <td width="45">Result</td>

  </tr>

  <tr>

   <td width="86">A</td>

   <td width="45">Tail</td>

  </tr>

  <tr>

   <td width="86">A</td>

   <td width="45">Tail</td>

  </tr>

  <tr>

   <td width="86">A</td>

   <td width="45">Tail</td>

  </tr>

  <tr>

   <td width="86">A</td>

   <td width="45">Tail</td>

  </tr>

  <tr>

   <td width="86">A</td>

   <td width="45">Tail</td>

  </tr>

  <tr>

   <td width="86">A</td>

   <td width="45">Head</td>

  </tr>

  <tr>

   <td width="86">A</td>

   <td width="45">Head</td>

  </tr>

  <tr>

   <td width="86">B</td>

   <td width="45">Head</td>

  </tr>

  <tr>

   <td width="86">B</td>

   <td width="45">Head</td>

  </tr>

  <tr>

   <td width="86">B</td>

   <td width="45">Head</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>What is the likelihood of the result given <em>θ</em>? [4pts]</li>

 <li>What is the maximum likelihood estimation for <em>θ</em>? [6pts]</li>

</ul>

<h2>4.2         Normal distribution [15 pts](Bonus for Undergrads)</h2>

Suppose that we observe samples of a known function <em>g</em>(<em>t</em>) = <em>t</em><sup>3 </sup>with unknown amplitude <em>θ </em>at (known) arbitrary locations <em>t</em><sub>1</sub><em>,…,t<sub>N</sub>, </em>and these samples are corrupted by Gaussian noise. That is, we observe the sequence of random variables

<em>X<sub>n </sub></em>= <em>θt</em><sup>3</sup><em><sub>n </sub></em>+ <em>Z<sub>n</sub>,            n </em>= 1<em>,…,N</em>

where the <em>Z<sub>n </sub></em>are independent and <em>Z<sub>n </sub></em>∼ Normal

<ul>

 <li>Given <em>X</em><sub>1 </sub>= <em>x</em><sub>1</sub><em>,…,X<sub>N </sub></em>= <em>x<sub>N</sub>, </em>compute the log likelihood function</li>

</ul>

<em>`</em>(<em>θ</em>;<em>x</em><sub>1</sub><em>,…,x<sub>N</sub></em>) = log<em>f<sub>X</sub></em><sub>1<em>,…,X</em></sub><em><sub>N </sub></em>(<em>x</em><sub>1</sub><em>,…,x<sub>N</sub></em>;<em>θ</em>) = log(<em>f<sub>X</sub></em><sub>1 </sub>(<em>x</em><sub>1</sub>;<em>θ</em>)<em>f<sub>X</sub></em><sub>2 </sub>(<em>x</em><sub>2</sub>;<em>θ</em>)···<em>f<sub>X</sub></em><em><sub>N </sub></em>(<em>x<sub>N</sub></em>;<em>θ</em>))

Note that the <em>X<sub>n </sub></em>are independent (as the last equality is suggesting) but not identically distributed (they have different means). [9pts]

<ul>

 <li>Compute the MLE for <em>θ</em>. [6pts]</li>

</ul>

<h2>4.3         Bonus for undergrads [10 pts]</h2>

The C.D.F of independent random variables <em>X</em><sub>1</sub><em>,X</em><sub>2</sub><em>,…,X<sub>n </sub></em>is

<em>,               x &gt; β</em>

where <em>α </em>≥ 0, <em>β </em>≥ 0.

<ul>

 <li>Write down the P.D.F of above independent random variables. [4pts]</li>

 <li>Find the MLEs of <em>α </em>and <em>β</em>. [6pts]</li>

</ul>

<h1>5           Information Theory</h1>

<h2>5.1         Marginal Distribution</h2>

Suppose the joint probability distribution of two binary random variables <em>X </em>and <em>Y </em>are given as follows.

<table width="83">

 <tbody>

  <tr>

   <td width="40"><em>X</em>|<em>Y</em></td>

   <td width="22">1</td>

   <td width="22">2</td>

  </tr>

  <tr>

   <td width="40">0</td>

   <td width="22"><u>1</u>3</td>

   <td width="22"><u>1</u>3</td>

  </tr>

  <tr>

   <td width="40">1</td>

   <td width="22">0</td>

   <td width="22"><u>1</u>3</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Show the marginal distribution of <em>X </em>and <em>Y </em>, respectively. [3pts]</li>

 <li>Find mutual information for the joint probability distribution in the previous question [3pts]</li>

</ul>

<h2>5.2         Mutual Information and Entropy</h2>

Given a dataset as below.

<table width="564">

 <tbody>

  <tr>

   <td width="54"><em>Sr.No.</em></td>

   <td width="81"><em>Age</em></td>

   <td width="75"><em>Immunity</em></td>

   <td width="77"><em>Travelled</em>?</td>

   <td width="148"><em>UnderlyingConditions</em></td>

   <td width="129"><em>Self </em>− <em>quarantine</em>?</td>

  </tr>

  <tr>

   <td width="54">1</td>

   <td width="81"><em>young</em></td>

   <td width="75"><em>high</em></td>

   <td width="77"><em>no</em></td>

   <td width="148"><em>yes</em></td>

   <td width="129"><em>no</em></td>

  </tr>

  <tr>

   <td width="54">2</td>

   <td width="81"><em>young</em></td>

   <td width="75"><em>high</em></td>

   <td width="77"><em>no</em></td>

   <td width="148"><em>no</em></td>

   <td width="129"><em>no</em></td>

  </tr>

  <tr>

   <td width="54">3</td>

   <td width="81"><em>middleaged</em></td>

   <td width="75"><em>high</em></td>

   <td width="77"><em>no</em></td>

   <td width="148"><em>yes</em></td>

   <td width="129"><em>yes</em></td>

  </tr>

  <tr>

   <td width="54">4</td>

   <td width="81"><em>senior</em></td>

   <td width="75"><em>medium</em></td>

   <td width="77"><em>no</em></td>

   <td width="148"><em>yes</em></td>

   <td width="129"><em>yes</em></td>

  </tr>

  <tr>

   <td width="54">5</td>

   <td width="81"><em>senior</em></td>

   <td width="75"><em>low</em></td>

   <td width="77"><em>yes</em></td>

   <td width="148"><em>yes</em></td>

   <td width="129"><em>yes</em></td>

  </tr>

  <tr>

   <td width="54">6</td>

   <td width="81"><em>senior</em></td>

   <td width="75"><em>low</em></td>

   <td width="77"><em>yes</em></td>

   <td width="148"><em>no</em></td>

   <td width="129"><em>no</em></td>

  </tr>

  <tr>

   <td width="54">7</td>

   <td width="81"><em>middleaged</em></td>

   <td width="75"><em>low</em></td>

   <td width="77"><em>yes</em></td>

   <td width="148"><em>no</em></td>

   <td width="129"><em>yes</em></td>

  </tr>

  <tr>

   <td width="54">8</td>

   <td width="81"><em>young</em></td>

   <td width="75"><em>medium</em></td>

   <td width="77"><em>no</em></td>

   <td width="148"><em>yes</em></td>

   <td width="129"><em>no</em></td>

  </tr>

  <tr>

   <td width="54">9</td>

   <td width="81"><em>young</em></td>

   <td width="75"><em>low</em></td>

   <td width="77"><em>yes</em></td>

   <td width="148"><em>yes</em></td>

   <td width="129"><em>no</em></td>

  </tr>

  <tr>

   <td width="54">10</td>

   <td width="81"><em>senior</em></td>

   <td width="75"><em>medium</em></td>

   <td width="77"><em>yes</em></td>

   <td width="148"><em>yes</em></td>

   <td width="129"><em>yes</em></td>

  </tr>

  <tr>

   <td width="54">11</td>

   <td width="81"><em>young</em></td>

   <td width="75"><em>medium</em></td>

   <td width="77"><em>yes</em></td>

   <td width="148"><em>no</em></td>

   <td width="129"><em>yes</em></td>

  </tr>

  <tr>

   <td width="54">12</td>

   <td width="81"><em>middleaged</em></td>

   <td width="75"><em>medium</em></td>

   <td width="77"><em>no</em></td>

   <td width="148"><em>no</em></td>

   <td width="129"><em>yes</em></td>

  </tr>

  <tr>

   <td width="54">13</td>

   <td width="81"><em>middleaged</em></td>

   <td width="75"><em>high</em></td>

   <td width="77"><em>yes</em></td>

   <td width="148"><em>yes</em></td>

   <td width="129"><em>yes</em></td>

  </tr>

  <tr>

   <td width="54">14</td>

   <td width="81"><em>senior</em></td>

   <td width="75"><em>medium</em></td>

   <td width="77"><em>no</em></td>

   <td width="148"><em>no</em></td>

   <td width="129"><em>no</em></td>

  </tr>

 </tbody>

</table>

We want to decide whether an individual working in an essential services industry should be allowed to work or self-quarantine. Each input has four features (<em>x</em><sub>1</sub>, <em>x</em><sub>2</sub>, <em>x</em><sub>3</sub>, <em>x</em><sub>4</sub>): Age, Immunity, Travelled, Underlying Conditions. The decision (quarantine vs not) is represented as <em>Y </em>.

<ul>

 <li>Find entropy <em>H</em>(<em>Y </em>). [3pts]</li>

 <li>Find conditional entropy <em>H</em>(<em>Y </em>|<em>x</em><sub>1</sub>), <em>H</em>(<em>Y </em>|<em>x</em><sub>4</sub>), respectively. [8pts]</li>

 <li>Find mutual information <em>I</em>(<em>x</em><sub>1</sub><em>,Y </em>) and <em>I</em>(<em>x</em><sub>4</sub><em>,Y </em>) and determine which one</li>

</ul>

(<em>x</em><sub>1 </sub>or <em>x</em><sub>4</sub>) is more informative. [4pts]

<ul>

 <li>Find joint entropy <em>H</em>(<em>Y,x</em><sub>3</sub>). [4pts]</li>

</ul>

<h2>5.3         Entropy Proofs</h2>

<ul>

 <li>Suppose <em>X </em>and <em>Y </em>are independent. Show that <em>H</em>(<em>X</em>|<em>Y </em>) = <em>H</em>(<em>X</em>). [2pts]</li>

 <li>Suppose <em>X </em>and <em>Y </em>are independent. Show that <em>H</em>(<em>X,Y </em>) = <em>H</em>(<em>X</em>)+<em>H</em>(<em>Y </em>).</li>

</ul>

[2pts]

<ul>

 <li>Prove that the mutual information is symmetric, i.e., <em>I</em>(<em>X,Y </em>) = <em>I</em>(<em>Y,X</em>) and <em>x<sub>i </sub></em>∈ <em>X,y<sub>i </sub></em>∈ <em>Y </em>[3pts]</li>

</ul>

<h1>6           Bonus for All</h1>

<ul>

 <li>If a random variable X has a Poisson distribution with mean 8, then calculate the expectation E[(<em>X </em>+ 2)<sup>2</sup>] [2 pts]</li>

 <li>A person decides to toss a fair coin repeatedly until he gets a head. He will make at most 3 tosses. Let the random variable Y denote the number of heads. Find the variance of Y. [4 pts]</li>

 <li>Two random variables X and Y are distributed according to</li>

</ul>

<em>,   otherwise</em>

What is the probability P(X+Y ≤ 1)? [4 pts]