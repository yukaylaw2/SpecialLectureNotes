<head><script type="text/javascript"
  src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script></head>
# A.1 Real Numbers and Their Properties

These notes are the notes I use for class and are *not* intended to be error-free or complete.  It is assumed that you would read your textbook and that you would ask questions in class.  The provision of these notes is there so that you would have backup information as needed.

## Classifying Numbers

We will start by looking at the different types of numbers that exist.  

<p align="center"><img alt="Categorization of real numbers showing how there are more and more specific descriptions." src="number_types.png" width="350"></p>

(Blitzer, *College Algebra* (Pearson))

For now, we will focus on *real numbers*, which are numbers that exist on the number line and can describe quantities in everyday life.  Of these, we divide them as *rational* versus *irrational* numbers:

* *Rational numbers* can be expressed as a fraction of two whole numbers

  $$\begin{equation}
   \mbox{number} =  \frac{p}{q}
  \end{equation}$$
  where $$p$$ and $$q$$ are integers.

* Other numbers, such as $$\pi$$ and $$\sqrt{2}$$ are *irrational* numbers.[^1]

Remember that we have fractions and integers, and we can divide them further.  You are expected to be able to **classify** the numbers.

> ### Class Question
>
> Which of these is *not* a natural number?
>
> 1. 0
> 2. 0.55
> 3. $$\sqrt{2}$$
> 4. None of the above
>
> <details><summary>Answer</summary>
>     The answer is (4).  0 is not a positive number; you can't count zero.  0.55 is a *fraction* (it is a rational number).  As indicated above, √2 is *irrational*.  So none of these are natural numbers.
> </details>

## The Number Line

We can represent any real number on the *real number line* - as a point on this line.  Numbers are indicated from left to right, with the zero point being the *origin*

![A number line with -4 to 4 illustrated, 0 as origin, and positive and negative directions included.](C:\Users\yukay\OneDrive - Western Governors University\CPSA stuff\Honors Precalculus - Grade 11\Lecture Notes\Chapter 0 - Review (A)\number_line.png)

Every real number can be plotted somewhere on this line (extended to infinity).

> ### Example
>
> Plot the following points on the number line: $$\frac{1}{5}, -\frac{4}{5},3,\frac{7}{4}, -\frac{9}{2}, -5, \frac{8}{3}$$.
>
> <details><summary>Answer</summary><img src="https://openstax.org/apps/image-cdn/v1/f=webp/apps/archive/20250522.165258/resources/6b668212cf867f2f5083d3042bd17ee824db5bc0" alt="A number line with the numbers above drawn out"></img></details>

> ### Class Question
>
> Which of these correctly depicts $$-\sqrt{3}$$?
>
> ![Number lines from -2 to +2 with the red dot at different points for A to D](C:\Users\yukay\OneDrive - Western Governors University\CPSA stuff\Honors Precalculus - Grade 11\Lecture Notes\Chapter 0 - Review (A)\numberline_plicker.png)
>
> <details><summary>Answer</summary> B </details>

## Ordering Real Numbers

As you may recall, real numbers are ordered: there is a definite direction for where $$a < b$$ or vice versa.  Note the difference between, say, $$a \geq b$$ and $$a > b$$.

> ### Example
>
> As $$b$$ is to the right of $$a$$ on the number line (and $$b - a > 0$$), $$a < b$$.
>
> ![A number line with a (close to 0) to the left of b (close to 2)](C:\Users\yukay\OneDrive - Western Governors University\CPSA stuff\Honors Precalculus - Grade 11\Lecture Notes\Chapter 0 - Review (A)\large_small.png)

> ### Class Question
>
> Which of these is true?
>
> 1. $$1 < -5$$
> 2. $$-\frac{2}{3} < -\frac{3}{4}$$
> 3. $$\frac{3}{2} < 7$$
> 4. $$-3.5 > 1$$
>
> <details><summary>Answer</summary>3</details>

### Interval Notation

We can describe subsets of real numbers in *Iintervals* - numbers between two different real numbers  $$a$$ and $$b$$ (the *endpoints*).

* **Square** brackets if endpoint is part of the interval.
* **Round** brackets if endpoint is *not* part of the interval.

![Illustrations of different types of bounded intervals](C:\Users\yukay\OneDrive - Western Governors University\CPSA stuff\Honors Precalculus - Grade 11\Lecture Notes\Chapter 0 - Review (A)\bounded_intervals.png)

> #### Example
>
> Let's think about grade boundaries.  You would probably prefer that I count 90% (exactly) as an A.  You would therefore want As to be $$[90,100]$$ and Bs to be $$[80,90)$$.  You would *not* want me to make 

> #### Class Question
>
> Express $$-9 \lt x \leq -4$$ in interval notation
>
> <details><summary>Answer</summary>Since the lower bound does not include -9 itself, this is an open bracket.  Conversely, since the upper bound allows for the equality, that is a square bracket.  Therefore, (-9,-4] is the answer.</details>

## Absolute Values

The absolute value $$|x|$$ of a number is the *magnitude* of the number; you make the number positive however you do it.[^2]  One way of expressing this is

$$|a| = \begin{cases} a & a \geq 0 \\ -a & a < 0 \end{cases} $$

> ### Examples
>
> Find
>
> 1. $$|4-1|$$
> 2. $$\frac{|x+3|}{x+3}$$ for both $$x>-3$$ and $$x<-3$$

[^1]: Do not confuse irrational numbers with complex/imaginary numbers; the latter are important but do not represent physical quantities *per se* (though they play a major role in upper level physics for representing oscillations and waves).
[^2]: So far we are assuming the number is real.  We will deal with the possibility that the number is imaginary or complex in Ch. 2.