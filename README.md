Download Link: https://assignmentchef.com/product/solved-math-151a-assignment-3
<br>
<ol>

 <li>Let <em>f</em>(<em>x</em>) = 1<em>/x</em>, <em>x<sub>i </sub></em>= <em>i </em>+ 1, 0 ≤ <em>i </em>≤ 2, find the Lagrange interpolation polynomial interpolating the points (<em>x<sub>i</sub>,f</em>(<em>x<sub>i</sub></em>)) using

  <ul>

   <li>Lagrange interpolation formula.</li>

   <li>Neville’s method.</li>

   <li>the divided difference interpolation.</li>

  </ul></li>

 <li>Find the natural cubic spline passing through (−1<em>,</em>1) , (0<em>,</em>1), (1<em>,</em>2).</li>

 <li>Consider Hermite interpolation problem. Prove the following theorem: Let <em>f </em>∈ <em>C</em><sup>1</sup>([<em>a,b</em>]) and <em>x</em><sub>0</sub><em>,x</em><sub>1</sub><em>,…x<sub>n </sub></em>be <em>n </em>distinct nodes in [<em>a,b</em>], and let</li>

</ol>

where

<em>H</em><em>n,j </em>= [1 − 2(<em>x </em>− <em>x</em><em>j</em>)<em>L</em>0<em>n,j</em>(<em>x</em><em>j</em>)]<em>L</em>2<em>n,j</em>(<em>x</em>)             <em>H</em>ˆ<em>n,j </em>= (<em>x </em>− <em>x</em><em>j</em>)<em>L</em>2<em>n,j</em>(<em>x</em>)<em>.</em>

Show that <em>H</em>(<em>x<sub>i</sub></em>) = <em>f</em>(<em>x<sub>i</sub></em>) and <em>H</em><sup>0</sup>(<em>x<sub>i</sub></em>) = <em>f</em><sup>0</sup>(<em>x<sub>i</sub></em>), for all 0 ≤ <em>i </em>≤ <em>n</em>. (You do not need to prove the uniqueness of <em>H</em>.)

1

<ol start="4">

 <li>Let <em>f</em>(<em>x</em>) be a function defined on the interval [<em>x</em><sub>0</sub>−<em>h,x</em><sub>0 </sub>+<em>h</em>], and <em>f </em>∈ <em>C</em><sup>3</sup>[<em>x</em><sub>0</sub>−<em>h,x</em><sub>0 </sub>+<em>h</em>] .</li>

</ol>

<ul>

 <li>Let <em>P</em>(<em>x</em>) be the Lagrange interpolation polynomial of <em>f</em>(<em>x</em>) at the nodes <em>x </em>= <em>x</em><sub>0 </sub>− <em>h,x</em><sub>0</sub><em>,x</em><sub>0 </sub>+ <em>h</em>. Write down the expression of <em>P</em>(<em>x</em>).</li>

 <li>Write down the error term <em>E</em>(<em>x</em>) := <em>f</em>(<em>x</em>) − <em>P</em>(<em>x</em>) in terms of the derivatives of <em>f</em>(<em>x</em>).</li>

 <li>Using the fact that <em>f</em>(<em>x</em>) = <em>P</em>(<em>x</em>)+<em>E</em>(<em>x</em>), calculate the derivatives of <em>f</em>, <em>f</em><sup>0</sup>(<em>x</em>) at <em>x </em>= <em>x</em><sub>0</sub>.</li>

 <li>If we approximate the derivative <em>f</em><sup>0</sup>(<em>x</em><sub>0</sub>) by <em>P</em><sup>0</sup>(<em>x</em><sub>0</sub>), is it true that the above approximation is exact if <em>f </em>is a polynomial of degree less than or equal to 2 ? Why ?</li>

 <li>Write down an error bound of this approximation rule suggested in (d) for a generalfunction <em>f</em>(<em>x</em>) based on the result in (b).</li>

</ul>

<ol start="5">

 <li>(<strong>Programming problem</strong>)</li>

</ol>

Let a number of points (<em>x<sub>i</sub>,f</em>(<em>x<sub>i</sub></em>)) be given, 0 ≤ <em>i </em>≤ <em>n</em>. Let <em>P</em>(<em>x</em>) be its Lagrange interpolation polynomial interpolating the points (<em>x<sub>i</sub>,f</em>(<em>x<sub>i</sub></em>)), 0 ≤ <em>i </em>≤ <em>n</em>.

Write a program which allow inputs {(<em>x<sub>i</sub>,f</em>(<em>x<sub>i</sub></em>))} and a value <em>a</em>, and calculate the value of <em>P</em>(<em>a</em>).

2