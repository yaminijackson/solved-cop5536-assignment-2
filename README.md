Download Link: https://assignmentchef.com/product/solved-cop5536-assignment-2
<br>
Question 1. (10)

<ul>

 <li>[4 points] Draw a clearly labeled suffix tree for the string dggddgg#.</li>

 <li>[6 points] Describe how you can use a suffix tree to find the Longest Common Substring of two strings in time linear in the lengths of the two strings.</li>

</ul>

Question 2. (15)

For the min radix priority search tree (RPST) with range [0,32),

<ul>

 <li>[8 points] Perform insert operation into an initially empty RPST in sequence with the following keys:(6,6), (9,17), (4,4), (17,1), (6,3), (21,7). Show each step. The elements x and y of a key (x, y) stand for the search and priority key values, respectively.</li>

</ul>




<ul>

 <li>[7 points] Delete (6, 3) from the result RPST of part (a).</li>

</ul>

Question 3. (10)

Suppose that you are to design a Bloom filter with minimum P(u) and that

n = 100,000, m = 5000, and u = 1000.

<ul>

 <li>[5 points] Using any of the results obtained in the class, compute the number h, of hash functions to use. Show your computations.</li>

 <li>[5 points] Compute the probability, P(u), of a filter error when h has this value.</li>

</ul>




Question 4. (15)

Given n pairs of intervals (l<sub>i</sub>, r<sub>i</sub>), i=1,2…n, and a query interval J = (l<sub>, </sub>r). In order to list all the intervals that overlap J, we have constructed an interval tree with the following properties:

Each node v has a value v.key and two subtrees v.left and v.right.

The interval tree is a binary search tree on the “key” values.

Intervals with r<sub>i</sub> &lt; v.key are stored in the left subtree of v.

Intervals with l<sub>i</sub> &gt; v.key are stored in the right subtree of v.

Intervals with l<sub>i</sub> &lt;= v.key &lt;= r<sub>i</sub> are stored in v.

Describe an efficient algorithm that returns all the intervals that intersect J using the above interval tree data structure.


