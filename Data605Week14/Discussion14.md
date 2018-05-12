### In Exercises 25 – 30, use the Taylor series given in Key Idea 32 to create the Taylor series of the given functions.

29) $f(x)=e^x sin \quad x$ (only find the first 4 terms)

We know that the Taylor Series Expansion for $sin(x)$ is:
$$
sin(x) =\sum_{n=0}^{\infty} (-1)^n \frac{x^{2n+1}}{(2n + 1)!}
$$

We also know, from the text book, that:

$$
f(x)=e^x = \sum_{n=0}^{\infty} \frac{x^n}{n!}
$$

We now have to solve this by distributing the equations against each other
(polynomial multiplication). We only do the first 4 terms.

$$
\sum_{n=0}^{3} \frac{x^n}{n!} \cdot \sum_{n=0}^{3} (-1)^n \frac{x^{2n+1}}{(2n + 1)!}
$$

Expanded they equal:

$$
e^x = 1 + x + \frac{x^2}{2} + \frac{x^3}{3}
$$
$$
sin(x) = x -\frac{x^3}{3!}-\frac{x^5!}{5}-\frac{x^7}{7!}-\frac{x^9}{9!}
$$

$$
sin(x) = x -\frac{x^3}{6}-\frac{x^5!}{120}-\frac{x^7}{5040}-\frac{x^9}{362880}
$$

$$
sin(x) = x -\frac{60480x^3}{362880}-\frac{3024x^5!}{362880}-\frac{72x^7}{362880}-\frac{x^9}{362880}
$$

$$
sin(x) = \frac{362880x - 60480x^3 - 33024x^5-72x^7-x^9}{362880}
$$
This gives:

$$
1(\frac{362880x - 60480x^3 - 33024x^5-72x^7-x^9}{362880}) +
$$
$$
x(\frac{362880x - 60480x^3 - 33024x^5-72x^7-x^9}{362880})+
$$
$$
\frac{x^2}{2}(\frac{362880x - 60480x^3 - 33024x^5-72x^7-x^9}{362880}) +
$$
$$
\frac{x^3}{3}(\frac{362880x - 60480x^3 - 33024x^5-72x^7-x^9}{362880})
$$

This is going to be a very larger equation...

$$
\frac{362880x - 60480x^3 - 33024x^5-72x^7-x^9}{362880} +
$$
$$
\frac{362880x^2 - 60480x^4 - 33024x^6-72x^8-x^{10}}{362880}+
$$
$$
\frac{362880x^3 - 60480x^5 - 33024x^7-72x^8-x^{11}}{725760}+
$$
$$
\frac{362880x^4 - 60480x^6 - 33024x^8-72x^{10}-x^{12}}{1088640}
$$


Taylor series was the bane of my existence in my B.A. in economics. This text
did a lot better of a job explaining it.

Still, this is quite the amount of work.
