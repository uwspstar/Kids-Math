# Explicit formula for an arithmetic sequence, and then distinguish it from the recursive formula.


### Arithmetic Sequence (Explicit Formula)

**English**:

**What is the Explicit Formula for an Arithmetic Sequence?**

The explicit formula, sometimes called the general formula, allows us to find the \( n^{th} \) term of an arithmetic sequence without having to know any of the previous terms. In contrast, the recursive formula defines each term in relation to the one before it.

**Explicit Formula for Arithmetic Sequence**:

\[ a_n = a_1 + (n-1)d \]

Where:
- \( a_n \) is the \( n^{th} \) term of the sequence.
- \( a_1 \) is the first term.
- \( d \) is the common difference.
- \( n \) is the position in the sequence.

For example, to find the 5th term in the sequence starting with 2 and having a common difference of 3, we'd use the formula:

\[ a_5 = 2 + (5-1)\times3 = 14 \]

**Difference between Explicit and Recursive Formulas**:

- **Explicit Formula**: Gives a direct way to find any term in the sequence without needing to find all the preceding terms. Ideal for when you need to find a term far down in a sequence without calculating all previous terms.
  
- **Recursive Formula**: Defines each term in relation to the one before it. It's a step-by-step approach, requiring knowledge of the previous term to find the next one.

---

**Chinese**:

**算术序列的显式公式是什么？**

显式公式，有时称为通用公式，允许我们找到算术序列的第 \( n^{th} \) 项，而无需知道任何前面的项。与此相反，递归公式定义了每一项相对于它之前的项。

**算术序列的显式公式**:

\[ a_n = a_1 + (n-1)d \]

其中：
- \( a_n \) 是序列的第 \( n^{th} \) 项。
- \( a_1 \) 是第一项。
- \( d \) 是公差。
- \( n \) 是序列中的位置。

例如，要找到以2开始，公差为3的序列的第5项，我们可以使用公式：

\[ a_5 = 2 + (5-1)\times3 = 14 \]

**显式公式与递归公式的区别**：

- **显式公式**：提供了一个直接的方法来找到序列中的任何项，而无需找到所有前面的项。当您需要找到序列中较远的项，而无需计算所有前面的项时，这是理想的选择。
  
- **递归公式**：定义了每一项相对于它之前的项。这是一种逐步的方法，需要知道前一个项来找到下一个项。


**1. Medium:**
Given the arithmetic sequence \(2, 7, 12, \ldots\), find the 10th term.

**Solution:**
\[ a_n = a_1 + (n-1)d \]
\[ a_{10} = 2 + (10-1) \times 5 = 2 + 45 = 47 \]

**Chinese:**
给定算术序列 \(2, 7, 12, \ldots\), 求第10项。
**解答:**
\[ a_{10} = 2 + (10-1) \times 5 = 2 + 45 = 47 \]

---

**2. Medium:**
If \( a_4 = 16 \) and \( d = 3 \), find \( a_1 \).

**Solution:**
\[ a_4 = a_1 + 3d = a_1 + 9 \]
\[ a_1 = 16 - 9 = 7 \]

**Chinese:**
如果 \( a_4 = 16 \) 并且 \( d = 3 \), 求 \( a_1 \).
**解答:**
\[ a_1 = 16 - 9 = 7 \]

---

**3. Medium:**
Find the next term in the sequence: \(5, 10, 15, \ldots\).

**Solution:**
The next term is \( 15 + 5 = 20 \).

**Chinese:**
找到序列中的下一项: \(5, 10, 15, \ldots\).
**解答:**
下一项是 \( 15 + 5 = 20 \).

---

**4. Hard:**
Given the first term \( a_1 = 5 \) and the 7th term \( a_7 = 50 \), find \( d \).

**Solution:**
\[ a_7 = a_1 + 6d \]
\[ d = \frac{a_7 - a_1}{6} = \frac{50 - 5}{6} = 7.5 \]

**Chinese:**
给定第一项 \( a_1 = 5 \) 和第七项 \( a_7 = 50 \), 求 \( d \).
**解答:**
\[ d = \frac{a_7 - a_1}{6} = \frac{50 - 5}{6} = 7.5 \]

---

**5. Hard:**
Find the sum of the first 20 terms of the sequence \(2, 6, 10, \ldots\).

**Solution:**
Using the sum formula:
\[ S_n = \frac{n}{2} (a_1 + a_n) \]
\[ S_{20} = \frac{20}{2} (2 + 2 + 19 \times 4) = 10 \times 78 = 780 \]

**Chinese:**
找到序列 \(2, 6, 10, \ldots\) 的前20项的和。
**解答:**
\[ S_{20} = \frac{20}{2} (2 + 2 + 19 \times 4) = 10 \times 78 = 780 \]

---

**6. SAT Level:**
Given \( a_3 = 5 \) and \( a_7 = 21 \), find \( d \) and \( a_1 \).

**Solution:**
Using the explicit formula, we get:
\[ a_3 - a_1 = 2d = 5 - a_1 \]
\[ a_7 - a_1 = 6d = 21 - a_1 \]
Subtracting these equations, we get:
\[ 4d = 16 \implies d = 4 \]
Thus, \( a_1 = 5 - 2 \times 4 = -3 \).

**Chinese:**
给定 \( a_3 = 5 \) 和 \( a_7 = 21 \), 求 \( d \) 和 \( a_1 \).
**解答:**
\[ a_1 = 5 - 2 \times 4 = -3 \]
\[ d = 4 \]

Alright, let's continue with more questions and their solutions.

---

**7. SAT Level:**
Find the sum of the first 10 terms of the arithmetic sequence if \( a_1 = 3 \) and \( d = -2 \).

**Solution:**
\[ S_n = \frac{n}{2} (2a_1 + (n-1)d) \]
\[ S_{10} = \frac{10}{2} (2(3) + (10-1)(-2)) = 5 \times (-11) = -55 \]

**Chinese:**
找到算术序列的前10项的和，如果 \( a_1 = 3 \) 和 \( d = -2 \)。
**解答:**
\[ S_{10} = 5 \times (-11) = -55 \]

---

**8. Hard:**
An arithmetic sequence starts with \( a_1 = -5 \). The sum of the first 10 terms is 95. Find \( d \).

**Solution:**
Using the sum formula:
\[ S_{10} = \frac{10}{2} (2(-5) + 9d) = 95 \]
Solving, we get \( d = 12 \).

**Chinese:**
一个算术序列以 \( a_1 = -5 \) 开始。前10项的和是95。找到 \( d \)。
**解答:**
\[ d = 12 \]

---

**9. SAT Level:**
Given an arithmetic sequence where \( a_5 = 3 \) and \( a_{10} = 13 \), find \( a_1 \).

**Solution:**
From the formula:
\[ a_5 = a_1 + 4d = 3 \]
\[ a_{10} = a_1 + 9d = 13 \]
Subtracting, we have \( 5d = 10 \) so \( d = 2 \). Using this value in the first equation gives \( a_1 = -5 \).

**Chinese:**
给定算术序列 \( a_5 = 3 \) 和 \( a_{10} = 13 \)，求 \( a_1 \)。
**解答:**
\[ a_1 = -5 \]

---

**10. Hard:**
What is the common difference of an arithmetic sequence if the sum of the first 7 terms is 28 and \( a_1 = 2 \)?

**Solution:**
\[ S_7 = \frac{7}{2} (2a_1 + 6d) = 28 \]
This gives \( d = 3 \).

**Chinese:**
如果一个算术序列的前7项的和是28，并且 \( a_1 = 2 \)，那么公差是多少？
**解答:**
\[ d = 3 \]

---

**11. SAT Level:**
Find the 15th term of an arithmetic sequence where the 7th term is 10 and the 10th term is 19.

**Solution:**
\[ a_7 = a_1 + 6d = 10 \]
\[ a_{10} = a_1 + 9d = 19 \]
From the two, \( d = 3 \) and \( a_1 = 1 \). Thus, \( a_{15} = 1 + 14 \times 3 = 43 \).

**Chinese:**
找到算术序列的第15项，其中第7项是10，第10项是19。
**解答:**
\[ a_{15} = 43 \]

---

**12. Hard:**
The 3rd term in an arithmetic sequence is 15, and the sum of the first 10 terms is 110. Find the first term.

**Solution:**
\[ a_3 = a_1 + 2d = 15 \]
\[ S_{10} = \frac{10}{2} (2a_1 + 9d) = 110 \]
From these, \( a_1 = 5 \).

**Chinese:**
算术序列的第三项是15，前10项的和是110。找到第一项。
**解答:**
\[ a_1 = 5 \]

---

**13. SAT Level:**
The 6th term of an arithmetic sequence is 3 times the first term. The common difference is 5. Find the first term.

**Solution:**
\[ a_6 = a_1 + 5d = 3a_1 \]
Thus, \( a_1 = 25 \).

**Chinese:**
算术序列的第六项是第一项的三倍。公差是5。找到第一项。
**解答:**
\[ a_1 = 25 \]

---

**14. Medium:**
Find the next two terms in the sequence: \(8, 12, 16, \ldots\).

**Solution:**
The terms are \( 20 \) and \( 24 \).

**Chinese:**
找到序列中的下两项: \(8, 12, 16, \ldots\).
**解答:**
这两项是 \( 20 \) 和 \( 24 \).

---

**15. SAT Level:**
Given an arithmetic sequence with a common difference of -4 and a 5th term of 8, find the 10th term.

**Solution:**
\[ a_{10} = a_5 + 5d = 8 + 5(-4) = -12 \].

**Chinese:**
给定一个公差为-4的算术序列，第五项为8，找到第十项。
**解答:**
\[ a_{10} = -12 \].

