Download Link: https://assignmentchef.com/product/solved-smai-homework7-perceptrons-defined-by-the-threshold-expression
<br>
Consider two perceptrons defined by the threshold expression <em>w</em><sub>0 </sub>+ <em>w</em><sub>1</sub><em>x</em><sub>1 </sub>+ <em>w</em><sub>2</sub><em>x</em><sub>2 </sub><em>&gt; </em>0.

Perceptron A has weight values

<em>w</em><sub>0 </sub>= 1<em>,       w</em><sub>1 </sub>= 2<em>,       w</em><sub>2 </sub>= 1

and Perceptron B has weight values

<em>w</em><sub>0 </sub>= 0<em>,w</em><sub>1 </sub>= 2<em>,w</em><sub>2 </sub>= 1

True or False? Perceptron A is <em>more general than </em>Perceptron B.

<strong>Definition: </strong>Let <em>h<sub>j </sub></em>and <em>h<sub>k </sub></em>be boolean valued function defined over <em>X</em>. Then <em>h<sub>j </sub></em>is <em>more general than or equal to h<sub>k </sub></em>(written <em>h<sub>j </sub></em>≥<em><sub>g </sub>h<sub>k</sub></em>) if and only if

(∀<em>x </em>∈ <em>X</em>)[<em>h<sub>k</sub></em>(<em>x</em>) = 1 → <em>h<sub>j</sub></em>(<em>x</em>) = 1]

That is, any instance of <em>h<sub>k </sub></em>also satisfies <em>h<sub>j</sub></em>.

<strong>2        Subjective Question </strong>

Design a two-input perceptron that implements the boolean function <em>A </em>∧¬<em>B</em>.

3        Programming Question

Using the linear perceptron algorithm, solve the multi-class classification problem of predicting hand-written digit data. Report the accuracy achieved. A starter code has been provided in the ‘Linear Perceptron Excercise.ipynb’ notebook [Hint: You can use a one-vs-one, one-vs-all scheme or use a multi-class signum function]

1