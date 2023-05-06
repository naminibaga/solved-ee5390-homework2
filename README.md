Download Link: https://assignmentchef.com/product/solved-ee5390-homework2
<br>
<strong>Exercise 2.1. </strong>Compute the arithmetic code for the two sequences given the shared spreadsheet. The probability mass function is also provided in the spreadsheet.

<strong>Exercise 2.2. </strong>Compute the LZ78 parsing for the three sequences given in the shared spreadsheet.

<strong>Exercise 2.3 </strong>(1-bit quantization)<strong>. </strong>In this exercise, you will implement a scalar quantizer that minimizes the mean squared error distortion. For any <em>x </em>P R, consider a 1-bit/2-level quantizer which does the following:

#<em>a       </em>if <em>x </em>ą <em>t</em>

<em>Q</em>p<em>x</em>q “ <em>b </em>if <em>x </em>ď <em>t</em>

where <em>a </em>ą <em>b </em>are the two levels, and <em>t </em>is the threshold. We assume that <em>a </em>ą <em>t </em>ą <em>b</em>.

For any real-valued random variable <em>X</em>, the mean squared error of the quantizer for a fixed <em>a,b,t </em>is

<em>MSE </em>“ Ep<em>X </em>´ <em>Q</em>p<em>X</em>qq<sup>2</sup>

Assume that <em>X </em>is uniformly distributed over the interval r<em>α,β</em>s. Set up the optimization problem and find the <em>a,b,t </em>which minimizes the mean squared error. These would be functions of <em>α,β</em>.

Now use the files mentioned in the shared spreadsheet. Each file contains a set of 100 points uniformly distributed over some r<em>α,β</em>s. Estimate <em>α,β </em>from the set given to you. Use this, and the optimal 1-bit quantizer that you have designed above. Find <em>Q</em>p<em>x</em>q for all <em>x </em>in the file, and compute the mean squared error

ř               .