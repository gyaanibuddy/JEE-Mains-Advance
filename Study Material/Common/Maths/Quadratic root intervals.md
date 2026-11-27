# When do both roots lie in the interval?

**JEE algebra practice • द्विघात समीकरण • 10 minutes**

Let $a$ be real and let $p(x)=x^2-2ax+a+2$. Try each question before reading the hints. These are original practice questions.

1. For which $a$ does $p$ have two **distinct positive** roots? किन मानों के लिए दोनों मूल धनात्मक और अलग-अलग हैं?
2. For which $a$ are both roots **distinct and greater than 1**? किन मानों के लिए दोनों मूल अलग-अलग और 1 से बड़े हैं?
3. Write $a=k/7$ for an integer $k$. How many choices of $k$ give two distinct roots **strictly between 1 and 4**? ऐसे कितने पूर्णांक $k$ हैं जिनके लिए दोनों मूल अलग-अलग हैं और 1 तथा 4 के बीच हैं?

**Hint for 2.** Write $x=y+1$. What do the sum and product of the two new roots tell you?

**Hint for 3.** If the original roots are $r,s$, what are the sum and product of $4-r,4-s$?

### Worked solutions

1. The discriminant is $4(a-2)(a+1)$. Two distinct real roots require $a<-1$ or $a>2$. Their sum is $2a$ and their product is $a+2$. Two real numbers with positive product have the same sign; a positive sum then makes them both positive. Intersecting the three conditions gives **$a>2$**.
2. The shifted polynomial is $p(y+1)=y^2+2(1-a)y+3-a$. Its roots must be positive: their sum $2(a-1)$ and product $3-a$ must both be positive. Shifting preserves distinctness, so intersect $1<a<3$ with the discriminant condition from 1. The answer is **$2<a<3$**. At $a=2$ the root 2 is repeated; at $a=3$ one root equals 1.
3. Start with $2<a<3$ from 2. To make both original roots less than 4, the two numbers $4-r,4-s$ must be positive. Their sum $8-2a$ is already positive. Their product is $p(4)=18-7a$, so the extra condition is $a<18/7$. Hence $14<k<18$, giving **three choices: 15, 16, 17**.

**Why checking only the endpoints can fail.** At $a=0$, both $p(1)$ and $p(4)$ are positive, yet $p(x)=x^2+2$ has no real roots. Check the discriminant before interpreting signs.
