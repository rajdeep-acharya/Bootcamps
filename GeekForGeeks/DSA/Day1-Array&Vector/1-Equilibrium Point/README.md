Given an array A of n positive numbers. The task is to find the first Equilibium Point in the array.
Equilibrium Point in an array is a position such that the sum of elements before it is equal to the sum of elements after it.

*Note: Retun the index of Equilibrium point. (1-based index)*

*Example 1:*

Input: 
n = 5 
A[] = {1,3,5,2,2} 
Output: 3 
Explanation:  
equilibrium point is at position 3 
as elements before it (1+3) = 
elements after it (2+2). 

*Example 2:*

Input:
n = 1
A[] = {1}
Output: 1
Explanation:
Since its the only element hence
its the only equilibrium point.

*Your Task:*

The task is to complete the function *equilibriumPoint()* which takes the array and n as input parameters and returns the point of equilibrium. Return -1 if no such point exists. 

*Expected Time Complexity:* O(n)
*Expected Auxiliary Space:* O(1)

*Constraints:*
1 <= n <= 10^6
1 <= A[i] <= 10^8
<!-- 1 &lt;= n&nbsp;&lt;= 10 -->

<span class="problem-tab__name">Equilibrium Point</span>
<p><span style="font-size:18px">Given an array A of n&nbsp;positive numbers. The task is to find the first Equilibium Point in the array.&nbsp;<br>
Equilibrium Point in an array is a position such that the sum of elements before it is equal to the sum of elements after it.</span></p>
<p><strong><span style="font-size:18px">Note: Retun the index of Equilibrium point. (1-based index)</span></strong></p>
<p><span style="font-size:18px"><strong>Example 1:</strong></span></p>
<p><span style="font-size:18px"><strong>Example 2:</strong></span></p>
<pre><strong>Input:
</strong><span style="font-size:18px">n = 1
A[] = {1}
<strong>Output: </strong>1<strong>
Explanation:
</strong>Since its the only element hence
its the only equilibrium point.</span></pre>