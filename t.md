<p> 
Given a string <i>s</i>, partition <i>s</i> such that every substring of
the partition is a palindrome.
</p><p> 
Return the minimum cuts needed for a palindrome partitioning of
<i>s</i>.
</p><p> 
For example, given <i>s</i> = <code>"aab"</code>,<br
/> Return <code>1</code> since the palindrome partitioning
<code>["aa","b"]</code> could be produced using 1 cut.
</p>
Solve this problem</a><b>Palindrome Partitioning</b>
<p> 
Given a string <i>s</i>, partition <i>s</i> such that every substring of
the partition is a palindrome.
</p><p> 
Return all possible palindrome partitioning of <i>s</i>.
</p><p> 
For example, given <i>s</i> = <code>"aab"</code>,<br
/>Return
<pre>
  [
    ["aa","b"],
    ["a","a","b"]
  ]
</pre></p>
<b>Surrounded Regions</b><span
class='date' title='2013-02-22 02:32:25'>Feb 22</span><span
class='stats' title='11049 accepted submissions out of 41380 (27%)'>11049
/ 41380</span>
</div><div
class='row-even question-content'><p> 
Given a 2D board containing <code>'X'</code> and <code>'O'</code>,
capture all regions surrounded by <code>'X'</code>.
</p><p>
A region is captured by flipping all <code>'O'</code>s into
<code>'X'</code>s in that surrounded region .
</p><p> 
For example,<br
/>
<pre>
X X X X
X O O X
X X O X
X O X X
</pre></p><p> 
After running your function, the board should be:
<pre>
X X X X
X X X X
X X X X
X O X X
</pre></p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(130, "Surrounded Regions"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_130'>(link to this question)</a></span>
</div></div><div><div
id='question_129' class='row-odd question-title'>
<span
class='none'></span><b>Sum Root to Leaf Numbers</b><span
class='date' title='2013-02-19 02:31:58'>Feb 19</span><span
class='stats' title='8344 accepted submissions out of 23632 (35%)'>8344
/ 23632</span>
</div><div
class='row-odd question-content'><p>
Given a binary tree containing digits from <code>0-9</code> only, each
root-to-leaf path could represent a number.
</p><p>
An example is the root-to-leaf path <code>1-\>2-\>3</code> which
represents the number <code>123</code>.
</p><p>
Find the total sum of all root-to-leaf numbers.
</p><p>
For example,
<pre>
    1
   / \
  2   3
</pre></p><p> 
The root-to-leaf path <code>1-\>2</code> represents the number
<code>12</code>.<br
/> The root-to-leaf path <code>1-\>3</code> represents the number
<code>13</code>.
</p><p> 
Return the sum = 12 + 13 = <code>25</code>.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(129, "Sum Root to Leaf Numbers"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_129'>(link to this question)</a></span>
</div></div><div><div
id='question_128' class='row-even question-title'>
<span
class='accepted'></span><b>Longest Consecutive Sequence</b><span
class='date' title='2013-02-14 02:45:27'>Feb 14</span><span
class='stats' title='7913 accepted submissions out of 22936 (35%)'>7913
/ 22936</span>
</div><div
class='row-even question-content'><p> 
Given an unsorted array of integers, find the length of the longest
consecutive elements sequence.
</p><p> 
For example,<br
/> Given <code>[100, 4, 200, 1, 3, 2]</code>,<br
/> The longest consecutive elements sequence is <code>[1, 2, 3,
4]</code>. Return its length: <code>4</code>.
</p><p> 
Your algorithm should run in O(<i>n</i>) complexity.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(128, "Longest Consecutive Sequence"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_128'>(link to this question)</a></span>
</div></div><div><div
id='question_126' class='row-odd question-title'>
<span
class='none'></span><b>Word Ladder II</b><span
class='date' title='2013-02-11 06:30:11'>Feb 11</span><span
class='stats' title='7646 accepted submissions out of 36433 (21%)'>7646
/ 36433</span>
</div><div
class='row-odd question-content'><p> 
Given two words (<i>start</i> and <i>end</i>), and a dictionary, find
all shortest transformation sequence(s) from <i>start</i> to <i>end</i>,
such that:
</p><ol><li>
Only one letter can be changed at a time
</li><li>
Each intermediate word must exist in the dictionary
</li></ol><p> 
For example,
</p><p> 
Given:<br
/> <i>start</i> = <code>"hit"</code><br
/> <i>end</i> = <code>"cog"</code><br
/> <i>dict</i> = <code>["hot","dot","dog","lot","log"]</code><br
/>
</p><p> 
Return<br
/>
<pre>
  [
    ["hit","hot","dot","dog","cog"],
    ["hit","hot","lot","log","cog"]
  ]
</pre></p><p> 
<b>Note:</b><br
/>
<ul><li>
All words have the same length.
</li><li>
All words contain only lowercase alphabetic characters.
</li></ul></p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(126, "Word Ladder II"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_126'>(link to this question)</a></span>
</div></div><div><div
id='question_127' class='row-even question-title'>
<span
class='none'></span><b>Word Ladder</b><span
class='date' title='2013-02-11 06:26:11'>Feb 11</span><span
class='stats' title='10499 accepted submissions out of 37276 (28%)'>10499
/ 37276</span>
</div><div
class='row-even question-content'><p> 
Given two words (<i>start</i> and <i>end</i>), and a dictionary, find
the length of shortest transformation sequence from <i>start</i> to
<i>end</i>, such that:
</p><ol><li>
Only one letter can be changed at a time
</li><li>
Each intermediate word must exist in the dictionary
</li></ol><p> 
For example,
</p><p> 
Given:<br
/> <i>start</i> = <code>"hit"</code><br
/> <i>end</i> = <code>"cog"</code><br
/> <i>dict</i> = <code>["hot","dot","dog","lot","log"]</code><br
/>
</p><p> 
As one shortest transformation is <code>"hit" -\> "hot" -\> "dot" -\>
"dog" -\> "cog"</code>,<br
/> return its length <code>5</code>.
</p><p> 
<b>Note:</b><br
/>
<ul><li>
Return 0 if there is no such transformation sequence.
</li><li>
All words have the same length.
</li><li>
All words contain only lowercase alphabetic characters.
</li></ul></p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(127, "Word Ladder"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_127'>(link to this question)</a></span>
</div></div><div><div
id='question_125' class='row-odd question-title'>
<span
class='accepted'></span><b>Valid Palindrome</b><span
class='date' title='2013-01-13 01:13:00'>Jan 13</span><span
class='stats' title='7412 accepted submissions out of 23481 (32%)'>7412
/ 23481</span>
</div><div
class='row-odd question-content'><p> 
Given a string, determine if it is a palindrome, considering only
alphanumeric characters and ignoring cases.
</p><p> 
For example,<br
/> <code>"A man, a plan, a canal: Panama"</code> is a palindrome.<br
/> <code>"race a car"</code> is <i>not</i> a palindrome.
</p><p> 
<b>Note:</b><br
/> Have you consider that the string might be empty? This is a good
question to ask during an interview.
</p><p> 
For the purpose of this problem, we define empty string as valid
palindrome.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(125, "Valid Palindrome"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_125'>(link to this question)</a></span>
</div></div><div><div
id='question_124' class='row-even question-title'>
<span
class='none'></span><b>Binary Tree Maximum Path Sum</b><span
class='date' title='2012-11-08 04:29:15'>Nov 8 '12</span><span
class='stats' title='7312 accepted submissions out of 26768 (27%)'>7312
/ 26768</span>
</div><div
class='row-even question-content'><p> 
Given a binary tree, find the maximum path sum.
</p><p> 
The path may start and end at any node in the tree.
</p><p> 
For example:<br
/> Given the below binary tree,
<pre>
       1
      / \
     2   3
</pre></p><p> 
Return <code>6</code>.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(124, "Binary Tree Maximum Path Sum"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_124'>(link to this question)</a></span>
</div></div><div><div
id='question_123' class='row-odd question-title'>
<span
class='none'></span><b>Best Time to Buy and Sell Stock III</b><span
class='date' title='2012-11-07 05:24:04'>Nov 7 '12</span><span
class='stats' title='6064 accepted submissions out of 18525 (33%)'>6064
/ 18525</span>
</div><div
class='row-odd question-content'><p>
Say you have an array for which the <i>i</i><sup>th</sup> element is the
price of a given stock on day <i>i</i>.
</p><p>
Design an algorithm to find the maximum profit. You may complete at most
<i>two</i> transactions.
</p><p>
<b>Note:</b><br
/> You may not engage in multiple transactions at the same time (ie, you
must sell the stock before you buy again).
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(123, "Best Time to Buy and Sell Stock III"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_123'>(link to this question)</a></span>
</div></div><div><div
id='question_122' class='row-even question-title'>
<span
class='none'></span><b>Best Time to Buy and Sell Stock II</b><span
class='date' title='2012-10-31 02:30:23'>Oct 31 '12</span><span
class='stats' title='6007 accepted submissions out of 11762 (51%)'>6007
/ 11762</span>
</div><div
class='row-even question-content'><p>
Say you have an array for which the <i>i</i><sup>th</sup> element is the
price of a given stock on day <i>i</i>.
</p><p>
Design an algorithm to find the maximum profit. You may complete as many
transactions as you like (ie, buy one and sell one share of the stock
multiple times). However, you may not engage in multiple transactions at
the same time (ie, you must sell the stock before you buy again).
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(122, "Best Time to Buy and Sell Stock II"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_122'>(link to this question)</a></span>
</div></div><div><div
id='question_121' class='row-odd question-title'>
<span
class='none'></span><b>Best Time to Buy and Sell Stock</b><span
class='date' title='2012-10-30 11:30:34'>Oct 30 '12</span><span
class='stats' title='7527 accepted submissions out of 16932 (44%)'>7527
/ 16932</span>
</div><div
class='row-odd question-content'><p>
Say you have an array for which the <i>i</i><sup>th</sup> element is the
price of a given stock on day <i>i</i>.
</p><p>
If you were only permitted to complete at most one transaction (ie, buy
one and sell one share of the stock), design an algorithm to find the
maximum profit.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(121, "Best Time to Buy and Sell Stock"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_121'>(link to this question)</a></span>
</div></div><div><div
id='question_120' class='row-even question-title'>
<span
class='none'></span><b>Triangle</b><span
class='date' title='2012-10-30 00:02:25'>Oct 30 '12</span><span
class='stats' title='6503 accepted submissions out of 17796 (37%)'>6503
/ 17796</span>
</div><div
class='row-even question-content'><p>
Given a triangle, find the minimum path sum from top to bottom. Each
step you may move to adjacent numbers on the row below.
</p><p> 
For example, given the following triangle<br
/>
<pre>
[
     [<font color="red">2</font>],
    [<font color="red">3</font>,4],
   [6,<font color="red">5</font>,7],
  [4,<font color="red">1</font>,8,3]
]
</pre></p><p> 
The minimum path sum from top to bottom is <code>11</code> (i.e., <font
color="red">2</font> + <font
color="red">3</font> + <font
color="red">5</font> + <font
color="red">1</font> = 11).
</p><p> 
<b>Note:</b><br
/> Bonus point if you are able to do this using only <i>O</i>(<i>n</i>)
extra space, where <i>n</i> is the total number of rows in the triangle.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(120, "Triangle"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_120'>(link to this question)</a></span>
</div></div><div><div
id='question_119' class='row-odd question-title'>
<span
class='none'></span><b>Pascal's Triangle II</b><span
class='date' title='2012-10-29 00:54:37'>Oct 29 '12</span><span
class='stats' title='5210 accepted submissions out of 12287 (42%)'>5210
/ 12287</span>
</div><div
class='row-odd question-content'><p>
Given an index <i>k</i>, return the <i>k</i><sup>th</sup> row of the
Pascal's triangle.
</p><p> 
For example, given <i>k</i> = 3,<br
/> Return <code>[1,3,3,1]</code>.
</p><p> 
<b>Note:</b><br
/> Could you optimize your algorithm to use only <i>O</i>(<i>k</i>)
extra space?
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(119, "Pascal&#039;s Triangle II"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_119'>(link to this question)</a></span>
</div></div><div><div
id='question_118' class='row-even question-title'>
<span
class='none'></span><b>Pascal's Triangle</b><span
class='date' title='2012-10-28 23:03:39'>Oct 28 '12</span><span
class='stats' title='4857 accepted submissions out of 10981 (44%)'>4857
/ 10981</span>
</div><div
class='row-even question-content'><p>
Given <i>numRows</i>, generate the first <i>numRows</i> of Pascal's
triangle.
</p><p> 
For example, given <i>numRows</i> = 5,<br
/> Return
<pre>
[
     [1],
    [1,1],
   [1,2,1],
  [1,3,3,1],
 [1,4,6,4,1]
]
</pre></p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(118, "Pascal&#039;s Triangle"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_118'>(link to this question)</a></span>
</div></div><div><div
id='question_117' class='row-odd question-title'>
<span
class='none'></span><b>Populating Next Right Pointers in Each Node
II</b><span
class='date' title='2012-10-28 17:54:41'>Oct 28 '12</span><span
class='stats' title='5299 accepted submissions out of 13177 (40%)'>5299
/ 13177</span>
</div><div
class='row-odd question-content'><p>
Follow up for problem "<i>Populating Next Right Pointers in Each
Node</i>".
</p><p>
What if the given tree could be any binary tree? Would your previous
solution still work?
</p><p> 
<b>Note:</b>
<ul><li>
You may only use constant extra space.
</li></ul></p><p> 
For example,<br
/> Given the following binary tree,<br
/>
<pre>
         1
       /  \
      2    3
     / \    \
    4   5    7
</pre></p><p> 
After calling your function, the tree should look like:<br
/>
<pre>
         1 -> NULL
       /  \
      2 -> 3 -> NULL
     / \    \
    4-> 5 -> 7 -> NULL
</pre></p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(117, "Populating Next Right Pointers in Each Node II"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_117'>(link to this question)</a></span>
</div></div><div><div
id='question_116' class='row-even question-title'>
<span
class='none'></span><b>Populating Next Right Pointers in Each
Node</b><span
class='date' title='2012-10-28 17:51:40'>Oct 28 '12</span><span
class='stats' title='5938 accepted submissions out of 12053 (49%)'>5938
/ 12053</span>
</div><div
class='row-even question-content'><p> 
Given a binary tree
<pre>
    struct TreeLinkNode {
      TreeLinkNode *left;
      TreeLinkNode *right;
      TreeLinkNode *next;
    }
</pre></p><p>
Populate each next pointer to point to its next right node. If there is
no next right node, the next pointer should be set to <code>NULL</code>.
</p><p>
Initially, all next pointers are set to <code>NULL</code>.
</p><p> 
<b>Note:</b>
<ul><li>
You may only use constant extra space.
</li><li>
You may assume that it is a perfect binary tree (ie, all leaves are at
the same level, and every parent has two children).
</li></ul></p><p> 
For example,<br
/> Given the following perfect binary tree,<br
/>
<pre>
         1
       /  \
      2    3
     / \  / \
    4  5  6  7
</pre></p><p> 
After calling your function, the tree should look like:<br
/>
<pre>
         1 -> NULL
       /  \
      2 -> 3 -> NULL
     / \  / \
    4->5->6->7 -> NULL
</pre></p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(116, "Populating Next Right Pointers in Each Node"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_116'>(link to this question)</a></span>
</div></div><div><div
id='question_115' class='row-odd question-title'>
<span
class='none'></span><b>Distinct Subsequences</b><span
class='date' title='2012-10-19 04:59:20'>Oct 19 '12</span><span
class='stats' title='6266 accepted submissions out of 17972 (35%)'>6266
/ 17972</span>
</div><div
class='row-odd question-content'><p> 
Given a string <b>S</b> and a string <b>T</b>, count the number of
distinct subsequences of <b>T</b> in <b>S</b>.
</p><p> 
A subsequence of a string is a new string which is formed from the
original string by deleting some (can be none) of the characters without
disturbing the relative positions of the remaining characters. (ie,
<code>"ACE"</code> is a subsequence of <code>"ABCDE"</code> while
<code>"AEC"</code> is not).
</p><p> 
Here is an example:<br
/> <b>S</b> = <code>"rabbbit"</code>, <b>T</b> = <code>"rabbit"</code>
</p><p> 
Return <code>3</code>.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(115, "Distinct Subsequences"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_115'>(link to this question)</a></span>
</div></div><div><div
id='question_114' class='row-even question-title'>
<span
class='accepted'></span><b>Flatten Binary Tree to Linked List</b><span
class='date' title='2012-10-14 23:37:44'>Oct 14 '12</span><span
class='stats' title='7105 accepted submissions out of 21371 (33%)'>7105
/ 21371</span>
</div><div
class='row-even question-content'><p> 
Given a binary tree, flatten it to a linked list in-place.
</p><p> 
For example,<br
/> Given
<pre>
         1
        / \
       2   5
      / \   \
     3   4   6
</pre></p>
The flattened tree should look like:<br
/>
<pre>
   1
    \
     2
      \
       3
        \
         4
          \
           5
            \
             6
</pre><p
class="showspoilers">
<a
href="#" onclick="showSpoilers(this); return false;">click to show
hints.</a>
</p><div
class="spoilers">
<b>Hints:</b>
<p>
If you notice carefully in the flattened tree, each node's right child
points to the next node of a pre-order traversal.
</p></div>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(114, "Flatten Binary Tree to Linked List"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_114'>(link to this question)</a></span>
</div></div><div><div
id='question_113' class='row-odd question-title'>
<span
class='none'></span><b>Path Sum II</b><span
class='date' title='2012-10-14 14:49:54'>Oct 14 '12</span><span
class='stats' title='6392 accepted submissions out of 17591 (36%)'>6392
/ 17591</span>
</div><div
class='row-odd question-content'><p> 
Given a binary tree and a sum, find all root-to-leaf paths where each
path's sum equals the given sum.
</p>
For example:<br
/> Given the below binary tree and <code>sum = 22</code>,
<pre>
              5
             / \
            4   8
           /   / \
          11  13  4
         /  \    / \
        7    2  5   1
</pre><p> 
return<br
/>
<pre>
[
   [5,4,11,2],
   [5,8,4,5]
]
</pre></p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(113, "Path Sum II"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_113'>(link to this question)</a></span>
</div></div><div><div
id='question_112' class='row-even question-title'>
<span
class='none'></span><b>Path Sum</b><span
class='date' title='2012-10-14 02:33:38'>Oct 14 '12</span><span
class='stats' title='6653 accepted submissions out of 15901 (42%)'>6653
/ 15901</span>
</div><div
class='row-even question-content'><p> 
Given a binary tree and a sum, determine if the tree has a root-to-leaf
path such that adding up all the values along the path equals the given
sum.
</p>
For example:<br
/> Given the below binary tree and <code>sum = 22</code>,
<pre>
              5
             / \
            4   8
           /   / \
          11  13  4
         /  \      \
        7    2      1
</pre><p> 
return true, as there exist a root-to-leaf path
<code>5-\>4-\>11-\>2</code> which sum is 22.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(112, "Path Sum"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_112'>(link to this question)</a></span>
</div></div><div><div
id='question_111' class='row-odd question-title'>
<span
class='none'></span><b>Minimum Depth of Binary Tree</b><span
class='date' title='2012-10-10 02:21:40'>Oct 10 '12</span><span
class='stats' title='7310 accepted submissions out of 18192 (40%)'>7310
/ 18192</span>
</div><div
class='row-odd question-content'><p>
Given a binary tree, find its minimum depth.
</p><p>
The minimum depth is the number of nodes along the shortest path from
the root node down to the nearest leaf node.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(111, "Minimum Depth of Binary Tree"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_111'>(link to this question)</a></span>
</div></div><div><div
id='question_110' class='row-even question-title'>
<span
class='none'></span><b>Balanced Binary Tree</b><span
class='date' title='2012-10-09 03:04:35'>Oct 9 '12</span><span
class='stats' title='7722 accepted submissions out of 18479 (42%)'>7722
/ 18479</span>
</div><div
class='row-even question-content'><p>
Given a binary tree, determine if it is height-balanced.
</p><p> 
For this problem, a height-balanced binary tree is defined as a binary
tree in which the depth of the two subtrees of <i>every</i> node never
differ by more than 1.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(110, "Balanced Binary Tree"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_110'>(link to this question)</a></span>
</div></div><div><div
id='question_109' class='row-odd question-title'>
<span
class='none'></span><b>Convert Sorted List to Binary Search
Tree</b><span
class='date' title='2012-10-03 00:35:00'>Oct 3 '12</span><span
class='stats' title='5768 accepted submissions out of 16298 (35%)'>5768
/ 16298</span>
</div><div
class='row-odd question-content'><p>
Given a singly linked list where elements are sorted in ascending order,
convert it to a height balanced BST.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(109, "Convert Sorted List to Binary Search Tree"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_109'>(link to this question)</a></span>
</div></div><div><div
id='question_108' class='row-even question-title'>
<span
class='none'></span><b>Convert Sorted Array to Binary Search
Tree</b><span
class='date' title='2012-10-02 23:21:00'>Oct 2 '12</span><span
class='stats' title='5459 accepted submissions out of 11289 (48%)'>5459
/ 11289</span>
</div><div
class='row-even question-content'><p>
Given an array where elements are sorted in ascending order, convert it
to a height balanced BST.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(108, "Convert Sorted Array to Binary Search Tree"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_108'>(link to this question)</a></span>
</div></div><div><div
id='question_107' class='row-odd question-title'>
<span
class='accepted'></span><b>Binary Tree Level Order Traversal II</b><span
class='date' title='2012-10-01 22:11:18'>Oct 1 '12</span><span
class='stats' title='4449 accepted submissions out of 10092 (44%)'>4449
/ 10092</span>
</div><div
class='row-odd question-content'><p>
Given a binary tree, return the <i>bottom-up level order</i> traversal
of its nodes' values. (ie, from left to right, level by level from leaf
to root).
</p><p> 
For example:<br
/> Given binary tree <code>{3,9,20,\#,\#,15,7}</code>,<br
/>
<pre>
    3
   / \
  9  20
    /  \
   15   7
</pre></p><p> 
return its bottom-up level order traversal as:<br
/>
<pre>
[
  [15,7]
  [9,20],
  [3],
]
</pre></p><p
class="showspoilers">
confused what <code>"{1,\#,2,3}"</code> means? <a
href="#" onclick="showSpoilers(this); return false;">\> read more on how
binary tree is serialized on OJ.</a>
</p><div
class="spoilers">
<br
/><b>OJ's Binary Tree Serialization:</b>
<p> 
The serialization of a binary tree follows a level order traversal,
where '\#' signifies a path terminator where no node exists below.
</p><p> 
Here's an example:<br
/>
<pre>
   1
  / \
 2   3
    /
   4
    \
     5
</pre>
The above binary tree is serialized as
<code>"{1,2,3,\#,\#,4,\#,\#,5}"</code>.
</p></div>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(107, "Binary Tree Level Order Traversal II"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_107'>(link to this question)</a></span>
</div></div><div><div
id='question_106' class='row-even question-title'>
<span
class='accepted'></span><b>Construct Binary Tree from Inorder and
Postorder Traversal</b><span
class='date' title='2012-09-30 22:37:43'>Sep 30 '12</span><span
class='stats' title='4493 accepted submissions out of 12665 (35%)'>4493
/ 12665</span>
</div><div
class='row-even question-content'><p>
Given inorder and postorder traversal of a tree, construct the binary
tree.
</p><p>
<b>Note:</b><br
/> You may assume that duplicates do not exist in the tree.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(106, "Construct Binary Tree from Inorder and Postorder Traversal"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_106'>(link to this question)</a></span>
</div></div><div><div
id='question_105' class='row-odd question-title'>
<span
class='accepted'></span><b>Construct Binary Tree from Preorder and
Inorder Traversal</b><span
class='date' title='2012-09-30 21:00:29'>Sep 30 '12</span><span
class='stats' title='4869 accepted submissions out of 14001 (35%)'>4869
/ 14001</span>
</div><div
class='row-odd question-content'><p>
Given preorder and inorder traversal of a tree, construct the binary
tree.
</p><p>
<b>Note:</b><br
/> You may assume that duplicates do not exist in the tree.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(105, "Construct Binary Tree from Preorder and Inorder Traversal"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_105'>(link to this question)</a></span>
</div></div><div><div
id='question_104' class='row-even question-title'>
<span
class='none'></span><b>Maximum Depth of Binary Tree</b><span
class='date' title='2012-09-30 02:40:09'>Sep 30 '12</span><span
class='stats' title='6343 accepted submissions out of 9043 (70%)'>6343 /
9043</span>
</div><div
class='row-even question-content'><p>
Given a binary tree, find its maximum depth.
</p><p>
The maximum depth is the number of nodes along the longest path from the
root node down to the farthest leaf node.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(104, "Maximum Depth of Binary Tree"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_104'>(link to this question)</a></span>
</div></div><div><div
id='question_103' class='row-odd question-title'>
<span
class='accepted'></span><b>Binary Tree Zigzag Level Order
Traversal</b><span
class='date' title='2012-09-29 05:09:43'>Sep 29 '12</span><span
class='stats' title='4378 accepted submissions out of 12129 (36%)'>4378
/ 12129</span>
</div><div
class='row-odd question-content'><p>
Given a binary tree, return the <i>zigzag level order</i> traversal of
its nodes' values. (ie, from left to right, then right to left for the
next level and alternate between).
</p><p> 
For example:<br
/> Given binary tree <code>{3,9,20,\#,\#,15,7}</code>,<br
/>
<pre>
    3
   / \
  9  20
    /  \
   15   7
</pre></p><p> 
return its zigzag level order traversal as:<br
/>
<pre>
[
  [3],
  [20,9],
  [15,7]
]
</pre></p><p
class="showspoilers">
confused what <code>"{1,\#,2,3}"</code> means? <a
href="#" onclick="showSpoilers(this); return false;">\> read more on how
binary tree is serialized on OJ.</a>
</p><div
class="spoilers">
<br
/><b>OJ's Binary Tree Serialization:</b>
<p> 
The serialization of a binary tree follows a level order traversal,
where '\#' signifies a path terminator where no node exists below.
</p><p> 
Here's an example:<br
/>
<pre>
   1
  / \
 2   3
    /
   4
    \
     5
</pre>
The above binary tree is serialized as
<code>"{1,2,3,\#,\#,4,\#,\#,5}"</code>.
</p></div>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(103, "Binary Tree Zigzag Level Order Traversal"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_103'>(link to this question)</a></span>
</div></div><div><div
id='question_102' class='row-even question-title'>
<span
class='accepted'></span><b>Binary Tree Level Order Traversal</b><span
class='date' title='2012-09-29 03:19:48'>Sep 29 '12</span><span
class='stats' title='5832 accepted submissions out of 14746 (40%)'>5832
/ 14746</span>
</div><div
class='row-even question-content'><p>
Given a binary tree, return the <i>level order</i> traversal of its
nodes' values. (ie, from left to right, level by level).
</p><p> 
For example:<br
/> Given binary tree <code>{3,9,20,\#,\#,15,7}</code>,<br
/>
<pre>
    3
   / \
  9  20
    /  \
   15   7
</pre></p><p> 
return its level order traversal as:<br
/>
<pre>
[
  [3],
  [9,20],
  [15,7]
]
</pre></p><p
class="showspoilers">
confused what <code>"{1,\#,2,3}"</code> means? <a
href="#" onclick="showSpoilers(this); return false;">\> read more on how
binary tree is serialized on OJ.</a>
</p><div
class="spoilers">
<br
/><b>OJ's Binary Tree Serialization:</b>
<p> 
The serialization of a binary tree follows a level order traversal,
where '\#' signifies a path terminator where no node exists below.
</p><p> 
Here's an example:<br
/>
<pre>
   1
  / \
 2   3
    /
   4
    \
     5
</pre>
The above binary tree is serialized as
<code>"{1,2,3,\#,\#,4,\#,\#,5}"</code>.
</p></div>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(102, "Binary Tree Level Order Traversal"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_102'>(link to this question)</a></span>
</div></div><div><div
id='question_101' class='row-odd question-title'>
<span
class='accepted'></span><b>Symmetric Tree</b><span
class='date' title='2012-09-24 02:30:52'>Sep 24 '12</span><span
class='stats' title='7123 accepted submissions out of 14917 (48%)'>7123
/ 14917</span>
</div><div
class='row-odd question-content'><p>
Given a binary tree, check whether it is a mirror of itself (ie,
symmetric around its center).
</p><p> 
For example, this binary tree is symmetric:
<pre>
    1
   / \
  2   2
 / \ / \
3  4 4  3
</pre></p><p> 
But the following is not:<br
/>
<pre>
    1
   / \
  2   2
   \   \
   3    3
</pre></p><p> 
<b>Note:</b><br
/> Bonus points if you could solve it both recursively and iteratively.
</p><p
class="showspoilers">
confused what <code>"{1,\#,2,3}"</code> means? <a
href="#" onclick="showSpoilers(this); return false;">\> read more on how
binary tree is serialized on OJ.</a>
</p><div
class="spoilers">
<br
/><b>OJ's Binary Tree Serialization:</b>
<p> 
The serialization of a binary tree follows a level order traversal,
where '\#' signifies a path terminator where no node exists below.
</p><p> 
Here's an example:<br
/>
<pre>
   1
  / \
 2   3
    /
   4
    \
     5
</pre>
The above binary tree is serialized as
<code>"{1,2,3,\#,\#,4,\#,\#,5}"</code>.
</p></div>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(101, "Symmetric Tree"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_101'>(link to this question)</a></span>
</div></div><div><div
id='question_100' class='row-even question-title'>
<span
class='accepted'></span><b>Same Tree</b><span
class='date' title='2012-09-03 23:48:41'>Sep 3 '12</span><span
class='stats' title='6423 accepted submissions out of 10037 (64%)'>6423
/ 10037</span>
</div><div
class='row-even question-content'><p> 
Given two binary trees, write a function to check if they are equal or
not.
</p><p>
Two binary trees are considered equal if they are structurally identical
and the nodes have the same value.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(100, "Same Tree"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_100'>(link to this question)</a></span>
</div></div><div><div
id='question_99' class='row-odd question-title'>
<span
class='none'></span><b>Recover Binary Search Tree</b><span
class='date' title='2012-09-01 21:00:40'>Sep 1 '12</span><span
class='stats' title='4967 accepted submissions out of 16821 (30%)'>4967
/ 16821</span>
</div><div
class='row-odd question-content'><p> 
Two elements of a binary search tree (BST) are swapped by mistake.
</p><p>
Recover the tree without changing its structure.
</p>
<b>Note:</b><br
/> A solution using O(<i>n</i>) space is pretty straight forward. Could
you devise a constant space solution?
</p><p
class="showspoilers">
confused what <code>"{1,\#,2,3}"</code> means? <a
href="#" onclick="showSpoilers(this); return false;">\> read more on how
binary tree is serialized on OJ.</a>
</p><div
class="spoilers">
<br
/><b>OJ's Binary Tree Serialization:</b>
<p> 
The serialization of a binary tree follows a level order traversal,
where '\#' signifies a path terminator where no node exists below.
</p><p> 
Here's an example:<br
/>
<pre>
   1
  / \
 2   3
    /
   4
    \
     5
</pre>
The above binary tree is serialized as
<code>"{1,2,3,\#,\#,4,\#,\#,5}"</code>.
</p></div>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(99, "Recover Binary Search Tree"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_99'>(link to this question)</a></span>
</div></div><div><div
id='question_98' class='row-even question-title'>
<span
class='accepted'></span><b>Validate Binary Search Tree</b><span
class='date' title='2012-08-31 20:54:13'>Aug 31 '12</span><span
class='stats' title='6761 accepted submissions out of 19400 (35%)'>6761
/ 19400</span>
</div><div
class='row-even question-content'><p> 
Given a binary tree, determine if it is a valid binary search tree
(BST).
</p><p> 
Assume a BST is defined as follows:
<ul><li>
The left subtree of a node contains only nodes with keys <b>less
than</b> the node's key.
</li><li>
The right subtree of a node contains only nodes with keys <b>greater
than</b> the node's key.
</li><li>
Both the left and right subtrees must also be binary search trees.
</li></ul></p><p
class="showspoilers">
confused what <code>"{1,\#,2,3}"</code> means? <a
href="#" onclick="showSpoilers(this); return false;">\> read more on how
binary tree is serialized on OJ.</a>
</p><div
class="spoilers">
<br
/><b>OJ's Binary Tree Serialization:</b>
<p> 
The serialization of a binary tree follows a level order traversal,
where '\#' signifies a path terminator where no node exists below.
</p><p> 
Here's an example:<br
/>
<pre>
   1
  / \
 2   3
    /
   4
    \
     5
</pre>
The above binary tree is serialized as
<code>"{1,2,3,\#,\#,4,\#,\#,5}"</code>.
</p></div>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(98, "Validate Binary Search Tree"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_98'>(link to this question)</a></span>
</div></div><div><div
id='question_97' class='row-odd question-title'>
<span
class='none'></span><b>Interleaving String</b><span
class='date' title='2012-08-31 00:40:40'>Aug 31 '12</span><span
class='stats' title='7096 accepted submissions out of 24208 (29%)'>7096
/ 24208</span>
</div><div
class='row-odd question-content'><p> 
Given <i>s1</i>, <i>s2</i>, <i>s3</i>, find whether <i>s3</i> is formed
by the interleaving of <i>s1</i> and <i>s2</i>.
</p><p> 
For example,<br
/> Given:<br
/> <i>s1</i> = <code>"aabcc"</code>,<br
/> <i>s2</i> = <code>"dbbca"</code>,
</p><p> 
When <i>s3</i> = <code>"aadbbcbcac"</code>, return true.<br
/> When <i>s3</i> = <code>"aadbbbaccc"</code>, return false.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(97, "Interleaving String"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_97'>(link to this question)</a></span>
</div></div><div><div
id='question_95' class='row-even question-title'>
<span
class='none'></span><b>Unique Binary Search Trees II</b><span
class='date' title='2012-08-27 23:48:50'>Aug 27 '12</span><span
class='stats' title='3664 accepted submissions out of 10952 (33%)'>3664
/ 10952</span>
</div><div
class='row-even question-content'><p>
Given <i>n</i>, generate all structurally unique <b>BST's</b> (binary
search trees) that store values 1...<i>n</i>.
</p><p> 
For example,<br
/> Given <i>n</i> = 3, your program should return all 5 unique BST's
shown below.
<pre>
   1         3     3      2      1
    \       /     /      / \      \
     3     2     1      1   3      2
    /     /       \                 \
   2     1         2                 3
</pre></p><p
class="showspoilers">
confused what <code>"{1,\#,2,3}"</code> means? <a
href="#" onclick="showSpoilers(this); return false;">\> read more on how
binary tree is serialized on OJ.</a>
</p><div
class="spoilers">
<br
/><b>OJ's Binary Tree Serialization:</b>
<p> 
The serialization of a binary tree follows a level order traversal,
where '\#' signifies a path terminator where no node exists below.
</p><p> 
Here's an example:<br
/>
<pre>
   1
  / \
 2   3
    /
   4
    \
     5
</pre>
The above binary tree is serialized as
<code>"{1,2,3,\#,\#,4,\#,\#,5}"</code>.
</p></div>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(95, "Unique Binary Search Trees II"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_95'>(link to this question)</a></span>
</div></div><div><div
id='question_96' class='row-odd question-title'>
<span
class='none'></span><b>Unique Binary Search Trees</b><span
class='date' title='2012-08-27 23:47:39'>Aug 27 '12</span><span
class='stats' title='5456 accepted submissions out of 10302 (53%)'>5456
/ 10302</span>
</div><div
class='row-odd question-content'><p>
Given <i>n</i>, how many structurally unique <b>BST's</b> (binary search
trees) that store values 1...<i>n</i>?
</p><p> 
For example,<br
/> Given <i>n</i> = 3, there are a total of 5 unique BST's.
<pre>
   1         3     3      2      1
    \       /     /      / \      \
     3     2     1      1   3      2
    /     /       \                 \
   2     1         2                 3
</pre></p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(96, "Unique Binary Search Trees"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_96'>(link to this question)</a></span>
</div></div><div><div
id='question_94' class='row-even question-title'>
<span
class='none'></span><b>Binary Tree Inorder Traversal</b><span
class='date' title='2012-08-27 23:47:03'>Aug 27 '12</span><span
class='stats' title='7385 accepted submissions out of 16684 (44%)'>7385
/ 16684</span>
</div><div
class='row-even question-content'><p>
Given a binary tree, return the <i>inorder</i> traversal of its nodes'
values.
</p><p> 
For example:<br
/> Given binary tree <code>{1,\#,2,3}</code>,<br
/>
<pre>
   1
    \
     2
    /
   3
</pre></p><p> 
return <code>[1,3,2]</code>.
</p><p>
<b>Note:</b> Recursive solution is trivial, could you do it iteratively?
</p><p
class="showspoilers">
confused what <code>"{1,\#,2,3}"</code> means? <a
href="#" onclick="showSpoilers(this); return false;">\> read more on how
binary tree is serialized on OJ.</a>
</p><div
class="spoilers">
<br
/><b>OJ's Binary Tree Serialization:</b>
<p> 
The serialization of a binary tree follows a level order traversal,
where '\#' signifies a path terminator where no node exists below.
</p><p> 
Here's an example:<br
/>
<pre>
   1
  / \
 2   3
    /
   4
    \
     5
</pre>
The above binary tree is serialized as
<code>"{1,2,3,\#,\#,4,\#,\#,5}"</code>.
</p></div>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(94, "Binary Tree Inorder Traversal"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_94'>(link to this question)</a></span>
</div></div><div><div
id='question_93' class='row-odd question-title'>
<span
class='none'></span><b>Restore IP Addresses</b><span
class='date' title='2012-08-08 02:47:56'>Aug 8 '12</span><span
class='stats' title='4543 accepted submissions out of 16957 (27%)'>4543
/ 16957</span>
</div><div
class='row-odd question-content'><p>
Given a string containing only digits, restore it by returning all
possible valid IP address combinations.
</p><p> 
For example:<br
/> Given <code>"25525511135"</code>,
</p><p> 
return <code>["255.255.11.135", "255.255.111.35"]</code>. (Order does
not matter)
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(93, "Restore IP Addresses"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_93'>(link to this question)</a></span>
</div></div><div><div
id='question_92' class='row-even question-title'>
<span
class='none'></span><b>Reverse Linked List II</b><span
class='date' title='2012-06-27 21:13:28'>Jun 27 '12</span><span
class='stats' title='5508 accepted submissions out of 18773 (29%)'>5508
/ 18773</span>
</div><div
class='row-even question-content'><p> 
Reverse a linked list from position <i>m</i> to <i>n</i>. Do it in-place
and in one-pass.
</p><p> 
For example:<br
/> Given <code>1-\>2-\>3-\>4-\>5-\>NULL</code>, <i>m</i> = 2 and
<i>n</i> = 4,
</p><p> 
return <code>1-\>4-\>3-\>2-\>5-\>NULL</code>.
</p><p> 
<b>Note:</b><br
/> Given <i>m</i>, <i>n</i> satisfy the following condition:<br
/> 1 ? <i>m</i> ? <i>n</i> ? length of list.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(92, "Reverse Linked List II"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_92'>(link to this question)</a></span>
</div></div><div><div
id='question_90' class='row-odd question-title'>
<span
class='none'></span><b>Subsets II</b><span
class='date' title='2012-06-25 22:32:45'>Jun 25 '12</span><span
class='stats' title='4769 accepted submissions out of 13419 (36%)'>4769
/ 13419</span>
</div><div
class='row-odd question-content'><p> 
Given a collection of integers that might contain duplicates, <i>S</i>,
return all possible subsets.
</p><p>
<b>Note:</b><br
/>
<ul><li>
Elements in a subset must be in non-descending order.
</li><li>
The solution set must not contain duplicate subsets.
</li></ul></p><p> 
For example,<br
/> If <b><i>S</i></b> = <code>[1,2,2]</code>, a solution is:
</p><pre>
[
  [2],
  [1],
  [1,2,2],
  [2,2],
  [1,2],
  []
]
</pre>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(90, "Subsets II"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_90'>(link to this question)</a></span>
</div></div><div><div
id='question_91' class='row-even question-title'>
<span
class='none'></span><b>Decode Ways</b><span
class='date' title='2012-06-25 21:13:00'>Jun 25 '12</span><span
class='stats' title='6747 accepted submissions out of 26583 (25%)'>6747
/ 26583</span>
</div><div
class='row-even question-content'><p> 
A message containing letters from <code>A-Z</code> is being encoded to
numbers using the following mapping:
</p><pre>
'A' -> 1
'B' -> 2
...
'Z' -> 26
</pre><p> 
Given an encoded message containing digits, determine the total number
of ways to decode it.
</p><p> 
For example,<br
/> Given encoded message <code>"12"</code>, it could be decoded as
<code>"AB"</code> (1 2) or <code>"L"</code> (12).
</p><p> 
The number of ways decoding <code>"12"</code> is 2.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(91, "Decode Ways"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_91'>(link to this question)</a></span>
</div></div><div><div
id='question_89' class='row-odd question-title'>
<span
class='none'></span><b>Gray Code</b><span
class='date' title='2012-05-20 16:20:00'>May 20 '12</span><span
class='stats' title='3727 accepted submissions out of 8371 (45%)'>3727 /
8371</span>
</div><div
class='row-odd question-content'><p>
The gray code is a binary numeral system where two successive values
differ in only one bit.
</p><p>
Given a non-negative integer <i>n</i> representing the total number of
bits in the code, print the sequence of gray code. A gray code sequence
must begin with 0.
</p><p>
For example, given <i>n</i> = 2, return <code>[0,1,3,2]</code>. Its gray
code sequence is:
</p><pre>
00 - 0
01 - 1
11 - 3
10 - 2
</pre><p>
<b>Note:</b><br
/> For a given <i>n</i>, a gray code sequence is not uniquely defined.
</p><p>
For example, <code>[0,2,3,1]</code> is also a valid gray code sequence
according to the above definition.
</p><p>
For now, the judge is able to judge based on one instance of gray code
sequence. Sorry about that.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(89, "Gray Code"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_89'>(link to this question)</a></span>
</div></div><div><div
id='question_88' class='row-even question-title'>
<span
class='accepted'></span><b>Merge Sorted Array</b><span
class='date' title='2012-05-20 16:19:00'>May 20 '12</span><span
class='stats' title='6055 accepted submissions out of 13640 (44%)'>6055
/ 13640</span>
</div><div
class='row-even question-content'><p>
Given two sorted integer arrays A and B, merge B into A as one sorted
array.
</p><p> 
<b>Note:</b><br
/> You may assume that A has enough space to hold additional elements
from B. The number of elements initialized in A and B are <i>m</i> and
<i>n</i> respectively.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(88, "Merge Sorted Array"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_88'>(link to this question)</a></span>
</div></div><div><div
id='question_87' class='row-odd question-title'>
<span
class='none'></span><b>Scramble String</b><span
class='date' title='2012-04-30 12:17:01'>Apr 30 '12</span><span
class='stats' title='4644 accepted submissions out of 14931 (31%)'>4644
/ 14931</span>
</div><div
class='row-odd question-content'><p> 
Given a string <i>s1</i>, we may represent it as a binary tree by
partitioning it to two non-empty substrings recursively.
</p><p> 
Below is one possible representation of <i>s1</i> =
<code>"great"</code>:
</p><pre>
    great
   /    \
  gr    eat
 / \    /  \
g   r  e   at
           / \
          a   t
</pre><p> 
To scramble the string, we may choose any non-leaf node and swap its two
children.
</p><p> 
For example, if we choose the node <code>"gr"</code> and swap its two
children, it produces a scrambled string <code>"rgeat"</code>.
</p><pre>
    rgeat
   /    \
  rg    eat
 / \    /  \
r   g  e   at
           / \
          a   t
</pre><p> 
We say that <code>"rgeat"</code> is a scrambled string of
<code>"great"</code>.
</p><p> 
Similarly, if we continue to swap the children of nodes
<code>"eat"</code> and <code>"at"</code>, it produces a scrambled string
<code>"rgtae"</code>.
</p><pre>
    rgtae
   /    \
  rg    tae
 / \    /  \
r   g  ta  e
       / \
      t   a
</pre><p> 
We say that <code>"rgtae"</code> is a scrambled string of
<code>"great"</code>.
</p><p> 
Given two strings <i>s1</i> and <i>s2</i> of the same length, determine
if <i>s2</i> is a scrambled string of <i>s1</i>.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(87, "Scramble String"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_87'>(link to this question)</a></span>
</div></div><div><div
id='question_86' class='row-even question-title'>
<span
class='none'></span><b>Partition List</b><span
class='date' title='2012-04-30 12:14:48'>Apr 30 '12</span><span
class='stats' title='5164 accepted submissions out of 15877 (33%)'>5164
/ 15877</span>
</div><div
class='row-even question-content'><p>
Given a linked list and a value <i>x</i>, partition it such that all
nodes less than <i>x</i> come before nodes greater than or equal to
<i>x</i>.
</p><p> 
You should preserve the original relative order of the nodes in each of
the two partitions.
</p><p> 
For example,<br
/> Given <code>1-\>4-\>3-\>2-\>5-\>2</code> and <i>x</i> = 3,<br
/> return <code>1-\>2-\>2-\>4-\>3-\>5</code>.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(86, "Partition List"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_86'>(link to this question)</a></span>
</div></div><div><div
id='question_85' class='row-odd question-title'>
<span
class='none'></span><b>Maximal Rectangle</b><span
class='date' title='2012-04-24 02:08:18'>Apr 24 '12</span><span
class='stats' title='3792 accepted submissions out of 13475 (28%)'>3792
/ 13475</span>
</div><div
class='row-odd question-content'><p> 
Given a 2D binary matrix filled with 0's and 1's, find the largest
rectangle containing all ones and return its area.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(85, "Maximal Rectangle"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_85'>(link to this question)</a></span>
</div></div><div><div
id='question_84' class='row-even question-title'>
<span
class='none'></span><b>Largest Rectangle in Histogram</b><span
class='date' title='2012-04-23 00:20:14'>Apr 23 '12</span><span
class='stats' title='6550 accepted submissions out of 21145 (31%)'>6550
/ 21145</span>
</div><div
class='row-even question-content'><p> 
Given <i>n</i> non-negative integers representing the histogram's bar
height where the width of each bar is 1, find the area of largest
rectangle in the histogram.
</p><p> 
<img
src="http://www.leetcode.com/wp-content/uploads/2012/04/histogram.png" /><br
/>
<p
style="font-size: 11px">
Above is a histogram where width of each bar is 1, given height =
<code>[2,1,5,6,2,3]</code>.
</p></p><p> 
<img
src="http://www.leetcode.com/wp-content/uploads/2012/04/histogram_area.png" /><br
/>
<p
style="font-size: 11px">
The largest rectangle is shown in the shaded area, which has area =
<code>10</code> unit.
</p></p><p> 
For example,<br
/> Given height = <code>[2,1,5,6,2,3]</code>,<br
/> return <code>10</code>.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(84, "Largest Rectangle in Histogram"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_84'>(link to this question)</a></span>
</div></div><div><div
id='question_82' class='row-odd question-title'>
<span
class='none'></span><b>Remove Duplicates from Sorted List II</b><span
class='date' title='2012-04-22 14:41:38'>Apr 22 '12</span><span
class='stats' title='5564 accepted submissions out of 16823 (33%)'>5564
/ 16823</span>
</div><div
class='row-odd question-content'><p> 
Given a sorted linked list, delete all nodes that have duplicate
numbers, leaving only <i>distinct</i> numbers from the original list.
</p><p> 
For example,<br
/> Given <code>1-\>2-\>3-\>3-\>4-\>4-\>5</code>, return
<code>1-\>2-\>5</code>.<br
/> Given <code>1-\>1-\>1-\>2-\>3</code>, return <code>2-\>3</code>.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(82, "Remove Duplicates from Sorted List II"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_82'>(link to this question)</a></span>
</div></div><div><div
id='question_83' class='row-even question-title'>
<span
class='none'></span><b>Remove Duplicates from Sorted List</b><span
class='date' title='2012-04-22 14:40:36'>Apr 22 '12</span><span
class='stats' title='6081 accepted submissions out of 11943 (51%)'>6081
/ 11943</span>
</div><div
class='row-even question-content'><p> 
Given a sorted linked list, delete all duplicates such that each element
appear only <i>once</i>.
</p><p> 
For example,<br
/> Given <code>1-\>1-\>2</code>, return <code>1-\>2</code>.<br
/> Given <code>1-\>1-\>2-\>3-\>3</code>, return <code>1-\>2-\>3</code>.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(83, "Remove Duplicates from Sorted List"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_83'>(link to this question)</a></span>
</div></div><div><div
id='question_81' class='row-odd question-title'>
<span
class='none'></span><b>Search in Rotated Sorted Array II</b><span
class='date' title='2012-04-20 00:33:03'>Apr 20 '12</span><span
class='stats' title='4077 accepted submissions out of 10753 (38%)'>4077
/ 10753</span>
</div><div
class='row-odd question-content'><p>
Follow up for "Search in Rotated Sorted Array":<br
/> What if <i>duplicates</i> are allowed?
</p><p>
Would this affect the run-time complexity? How and why?
</p><p>
Write a function to determine if a given target is in the array.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(81, "Search in Rotated Sorted Array II"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_81'>(link to this question)</a></span>
</div></div><div><div
id='question_80' class='row-even question-title'>
<span
class='none'></span><b>Remove Duplicates from Sorted Array II</b><span
class='date' title='2012-04-19 23:12:29'>Apr 19 '12</span><span
class='stats' title='4602 accepted submissions out of 11239 (41%)'>4602
/ 11239</span>
</div><div
class='row-even question-content'><p> 
Follow up for "Remove Duplicates":<br
/> What if duplicates are allowed at most <i>twice</i>?
</p><p> 
For example,<br
/> Given sorted array A = <code>[1,1,1,2,2,3]</code>,
</p><p> 
Your function should return length = <code>5</code>, and A is now
<code>[1,1,2,2,3]</code>.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(80, "Remove Duplicates from Sorted Array II"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_80'>(link to this question)</a></span>
</div></div><div><div
id='question_79' class='row-odd question-title'>
<span
class='none'></span><b>Word Search</b><span
class='date' title='2012-04-18 21:24:24'>Apr 18 '12</span><span
class='stats' title='6762 accepted submissions out of 21892 (31%)'>6762
/ 21892</span>
</div><div
class='row-odd question-content'><p> 
Given a 2D board and a word, find if the word exists in the grid.
</p><p> 
The word can be constructed from letters of sequentially adjacent cell,
where "adjacent" cells are those horizontally or vertically neighboring.
The same letter cell may not be used more than once.
</p><p> 
For example,<br
/> Given <b>board</b> =
<pre>
[
  ["ABCE"],
  ["SFCS"],
  ["ADEE"]
]
</pre>
<b>word</b> = <code>"ABCCED"</code>, -\> returns <code>true</code>,<br
/> <b>word</b> = <code>"SEE"</code>, -\> returns <code>true</code>,<br
/> <b>word</b> = <code>"ABCB"</code>, -\> returns <code>false</code>.<br
/>
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(79, "Word Search"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_79'>(link to this question)</a></span>
</div></div><div><div
id='question_78' class='row-even question-title'>
<span
class='none'></span><b>Subsets</b><span
class='date' title='2012-04-18 21:21:48'>Apr 18 '12</span><span
class='stats' title='6226 accepted submissions out of 16269 (38%)'>6226
/ 16269</span>
</div><div
class='row-even question-content'><p> 
Given a set of distinct integers, <i>S</i>, return all possible subsets.
</p><p>
<b>Note:</b><br
/>
<ul><li>
Elements in a subset must be in non-descending order.
</li><li>
The solution set must not contain duplicate subsets.
</li></ul></p><p> 
For example,<br
/> If <b><i>S</i></b> = <code>[1,2,3]</code>, a solution is:
</p><pre>
[
  [3],
  [1],
  [2],
  [1,2,3],
  [1,3],
  [2,3],
  [1,2],
  []
]
</pre>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(78, "Subsets"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_78'>(link to this question)</a></span>
</div></div><div><div
id='question_77' class='row-odd question-title'>
<span
class='none'></span><b>Combinations</b><span
class='date' title='2012-04-18 21:20:58'>Apr 18 '12</span><span
class='stats' title='5708 accepted submissions out of 14105 (40%)'>5708
/ 14105</span>
</div><div
class='row-odd question-content'><p> 
Given two integers <i>n</i> and <i>k</i>, return all possible
combinations of <i>k</i> numbers out of 1 ... <i>n</i>.
</p><p> 
For example,<br
/> If <i>n</i> = 4 and <i>k</i> = 2, a solution is:
</p><pre>
[
  [2,4],
  [3,4],
  [2,3],
  [1,2],
  [1,3],
  [1,4],
]
</pre>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(77, "Combinations"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_77'>(link to this question)</a></span>
</div></div><div><div
id='question_76' class='row-even question-title'>
<span
class='none'></span><b>Minimum Window Substring</b><span
class='date' title='2012-04-15 15:25:25'>Apr 15 '12</span><span
class='stats' title='4849 accepted submissions out of 20420 (24%)'>4849
/ 20420</span>
</div><div
class='row-even question-content'><p> 
Given a string S and a string T, find the minimum window in S which will
contain all the characters in T in complexity O(n).
</p><p> 
For example,<br
/> <b>S</b> = <code>"ADOBECODEBANC"</code><br
/> <b>T</b> = <code>"ABC"</code><br
/>
</p><p> 
Minimum window is <code>"BANC"</code>.
</p><p> 
<b>Note:</b><br
/> If there is no such window in S that covers all characters in T,
return the emtpy string <code>""</code>.
</p><p> 
If there are multiple such windows, you are guaranteed that there will
always be only one unique minimum window in S.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(76, "Minimum Window Substring"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_76'>(link to this question)</a></span>
</div></div><div><div
id='question_75' class='row-odd question-title'>
<span
class='accepted'></span><b>Sort Colors</b><span
class='date' title='2012-04-09 01:24:46'>Apr 9 '12</span><span
class='stats' title='5950 accepted submissions out of 14106 (42%)'>5950
/ 14106</span>
</div><div
class='row-odd question-content'><p> 
Given an array with <i>n</i> objects colored red, white or blue, sort
them so that objects of the same color are adjacent, with the colors in
the order red, white and blue.
</p><p> 
Here, we will use the integers 0, 1, and 2 to represent the color red,
white, and blue respectively.
</p><p> 
<b>Note:</b><br
/> You are not suppose to use the library's sort function for this
problem.
</p><p
class="showspoilers">
<a
href="#" onclick="showSpoilers(this); return false;">click to show
follow up.</a>
</p><div
class="spoilers"><p>
<b>Follow up:</b><br
/> A rather straight forward solution is a two-pass algorithm using
counting sort.<br
/> First, iterate the array counting number of 0's, 1's, and 2's, then
overwrite array with total number of 0's, then 1's and followed by 2's.
</p><p>
Could you come up with an one-pass algorithm using only constant
space?<br
/>
</p></div>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(75, "Sort Colors"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_75'>(link to this question)</a></span>
</div></div><div><div
id='question_74' class='row-even question-title'>
<span
class='accepted'></span><b>Search a 2D Matrix</b><span
class='date' title='2012-04-07 01:50:51'>Apr 7 '12</span><span
class='stats' title='5288 accepted submissions out of 11782 (45%)'>5288
/ 11782</span>
</div><div
class='row-even question-content'><p>
Write an efficient algorithm that searches for a value in an <i>m</i> x
<i>n</i> matrix. This matrix has the following properties:
</p><p><ul><li>
Integers in each row are sorted from left to right.
</li><li>
The first integer of each row is greater than the last integer of the
previous row.
</li></ul></p><p> 
For example,
</p><p> 
Consider the following matrix:
</p><pre>
[
  [1,   3,  5,  7],
  [10, 11, 16, 20],
  [23, 30, 34, 50]
]
</pre><p>
Given <b>target</b> = <code>3</code>, return <code>true</code>.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(74, "Search a 2D Matrix"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_74'>(link to this question)</a></span>
</div></div><div><div
id='question_73' class='row-odd question-title'>
<span
class='none'></span><b>Set Matrix Zeroes</b><span
class='date' title='2012-04-06 03:10:45'>Apr 6 '12</span><span
class='stats' title='4561 accepted submissions out of 10629 (43%)'>4561
/ 10629</span>
</div><div
class='row-odd question-content'><p> 
Given a <i>m</i> x <i>n</i> matrix, if an element is 0, set its entire
row and column to 0. Do it in place.
</p><p
class="showspoilers">
<a
href="#" onclick="showSpoilers(this); return false;">click to show
follow up.</a>
</p><div
class="spoilers">
<b>Follow up:</b>
<p> 
Did you use extra space?<br
/> A straight forward solution using O(<i>m</i><i>n</i>) space is
probably a bad idea.<br
/> A simple improvement uses O(<i>m</i> + <i>n</i>) space, but still not
the best solution.<br
/> Could you devise a constant space solution?
</p></div>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(73, "Set Matrix Zeroes"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_73'>(link to this question)</a></span>
</div></div><div><div
id='question_72' class='row-even question-title'>
<span
class='accepted'></span><b>Edit Distance</b><span
class='date' title='2012-04-04 21:05:54'>Apr 4 '12</span><span
class='stats' title='5171 accepted submissions out of 14897 (35%)'>5171
/ 14897</span>
</div><div
class='row-even question-content'><p> 
Given two words <i>word1</i> and <i>word2</i>, find the minimum number
of steps required to convert <i>word1</i> to <i>word2</i>. (each
operation is counted as 1 step.)
</p><p> 
You have the following 3 operations permitted on a word:
</p><p> 
a)  Insert a character<br
    /> b) Delete a character<br
    /> c) Replace a character<br
    />
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(72, "Edit Distance"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_72'>(link to this question)</a></span>
    </div></div><div><div
    id='question_71' class='row-odd question-title'>
    <span
    class='none'></span><b>Simplify Path</b><span
    class='date' title='2012-04-04 00:33:28'>Apr 4 '12</span><span
    class='stats' title='3445 accepted submissions out of 13388 (26%)'>3445
    / 13388</span>
    </div><div
    class='row-odd question-content'><p>
    Given an absolute path for a file (Unix-style), simplify it.
    </p><p>
    For example,<br
    /> <b>path</b> = <code>"/home/"</code>, =\> <code>"/home"</code><br
    /> <b>path</b> = <code>"/a/./b/../../c/"</code>, =\>
    <code>"/c"</code><br
    />
    </p><p
    class="showspoilers">
    <a
    href="#" onclick="showSpoilers(this); return false;">click to show
    corner cases.</a>
    </p><div
    class="spoilers">
    <b>Corner Cases:</b>
    <p><ul><li>
    Did you consider the case where <b>path</b> =
    <code>"/../"</code>?<br
    /> In this case, you should return <code>"/"</code>.
    </li><li>
    Another corner case is the path might contain multiple slashes
    <code>'/'</code> together, such as <code>"/home//foo/"</code>.<br
    /> In this case, you should ignore redundant slashes and return
    <code>"/home/foo"</code>.
    </li></p></div>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(71, "Simplify Path"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_71'>(link to this question)</a></span>
    </div></div><div><div
    id='question_70' class='row-even question-title'>
    <span
    class='accepted'></span><b>Climbing Stairs</b><span
    class='date' title='2012-04-03 22:00:37'>Apr 3 '12</span><span
    class='stats' title='6879 accepted submissions out of 13083 (53%)'>6879
    / 13083</span>
    </div><div
    class='row-even question-content'><p>
    You are climbing a stair case. It takes <i>n</i> steps to reach to
    the top.
    </p><p>
    Each time you can either climb 1 or 2 steps. In how many distinct
    ways can you climb to the top?
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(70, "Climbing Stairs"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_70'>(link to this question)</a></span>
    </div></div><div><div
    id='question_69' class='row-odd question-title'>
    <span
    class='none'></span><b>Sqrt(x)</b><span
    class='date' title='2012-04-03 21:59:57'>Apr 3 '12</span><span
    class='stats' title='8283 accepted submissions out of 28329 (29%)'>8283
    / 28329</span>
    </div><div
    class='row-odd question-content'><p>
    Implement <code>int sqrt(int x)</code>.
    </p><p>
    Compute and return the square root of <i>x</i>.
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(69, "Sqrt(x)"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_69'>(link to this question)</a></span>
    </div></div><div><div
    id='question_68' class='row-even question-title'>
    <span
    class='none'></span><b>Text Justification</b><span
    class='date' title='2012-04-03 07:28:18'>Apr 3 '12</span><span
    class='stats' title='3100 accepted submissions out of 15986 (19%)'>3100
    / 15986</span>
    </div><div
    class='row-even question-content'><p> 
    Given an array of words and a length <i>L</i>, format the text such
    that each line has exactly <i>L</i> characters and is fully (left
    and right) justified.
    </p><p> 
    You should pack your words in a greedy approach; that is, pack as
    many words as you can in each line. Pad extra spaces <code>'
    '</code> when necessary so that each line has exactly <i>L</i>
    characters.
    </p><p> 
    Extra spaces between words should be distributed as evenly as
    possible. If the number of spaces on a line do not divide evenly
    between words, the empty slots on the left will be assigned more
    spaces than the slots on the right.
    </p><p> 
    For the last line of text, it should be left justified and no extra
    space is inserted between words.
    </p><p> 
    For example,<br
    /> <b>words</b>: <code>["This", "is", "an", "example", "of", "text",
    "justification."]</code><br
    /> <b>L</b>: <code>16</code>.
    </p><p> 
    Return the formatted lines as:<br
    />
    <pre>
    [
       "This    is    an",
       "example  of text",
       "justification.  "
    ]
    </pre></p><p> 
    <b>Note:</b> Each word is guaranteed not to exceed <i>L</i> in
    length.
    </p><p
    class="showspoilers">
    <a
    href="#" onclick="showSpoilers(this); return false;">click to show
    corner cases.</a>
    </p><div
    class="spoilers">
    <b>Corner Cases:</b>
    <p><ul><li>
    A line other than the last line might contain only one word. What
    should you do in this case?<br
    /> In this case, that line should be left-justified.
    </li></p></div>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(68, "Text Justification"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_68'>(link to this question)</a></span>
    </div></div><div><div
    id='question_66' class='row-odd question-title'>
    <span
    class='none'></span><b>Plus One</b><span
    class='date' title='2012-04-02 12:38:32'>Apr 2 '12</span><span
    class='stats' title='5323 accepted submissions out of 12479 (43%)'>5323
    / 12479</span>
    </div><div
    class='row-odd question-content'><p>
    Given a number represented as an array of digits, plus one to the
    number.
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(66, "Plus One"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_66'>(link to this question)</a></span>
    </div></div><div><div
    id='question_65' class='row-even question-title'>
    <span
    class='none'></span><b>Valid Number</b><span
    class='date' title='2012-04-02 12:37:20'>Apr 2 '12</span><span
    class='stats' title='3716 accepted submissions out of 20322 (18%)'>3716
    / 20322</span>
    </div><div
    class='row-even question-content'><p>
    Validate if a given string is numeric.
    </p><p> 
    Some examples:<br
    /> <code>"0"</code> =\> <code>true</code><br
    /> <code>" 0.1 "</code> =\> <code>true</code><br
    /> <code>"abc"</code> =\> <code>false</code><br
    /> <code>"1 a"</code> =\> <code>false</code><br
    /> <code>"2e10"</code> =\> <code>true</code><br
    />
    </p><p>
    <b>Note:</b> It is intended for the problem statement to be
    ambiguous. You should gather all requirements up front before
    implementing one.
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(65, "Valid Number"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_65'>(link to this question)</a></span>
    </div></div><div><div
    id='question_67' class='row-odd question-title'>
    <span
    class='none'></span><b>Add Binary</b><span
    class='date' title='2012-04-02 11:38:00'>Apr 2 '12</span><span
    class='stats' title='5763 accepted submissions out of 16556 (35%)'>5763
    / 16556</span>
    </div><div
    class='row-odd question-content'><p> 
    Given two binary strings, return their sum (also a binary string).
    </p><p> 
    For example,<br
    /> a = <code>"11"</code><br
    /> b = <code>"1"</code><br
    /> Return <code>"100"</code>.
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(67, "Add Binary"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_67'>(link to this question)</a></span>
    </div></div><div><div
    id='question_21' class='row-even question-title'>
    <span
    class='none'></span><b>Merge Two Sorted Lists</b><span
    class='date' title='2012-03-30 21:40:00'>Mar 30 '12</span><span
    class='stats' title='6381 accepted submissions out of 13388 (48%)'>6381
    / 13388</span>
    </div><div
    class='row-even question-content'><p>
    Merge two sorted linked lists and return it as a new list. The new
    list should be made by splicing together the nodes of the first two
    lists.
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(21, "Merge Two Sorted Lists"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_21'>(link to this question)</a></span>
    </div></div><div><div
    id='question_64' class='row-odd question-title'>
    <span
    class='none'></span><b>Minimum Path Sum</b><span
    class='date' title='2012-03-29 01:53:58'>Mar 29 '12</span><span
    class='stats' title='4584 accepted submissions out of 10117 (45%)'>4584
    / 10117</span>
    </div><div
    class='row-odd question-content'><p>
    Given a <i>m</i> x <i>n</i> grid filled with non-negative numbers,
    find a path from top left to bottom right which <i>minimizes</i> the
    sum of all numbers along its path.
    </p><p>
    <b>Note:</b> You can only move either down or right at any point in
    time.
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(64, "Minimum Path Sum"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_64'>(link to this question)</a></span>
    </div></div><div><div
    id='question_63' class='row-even question-title'>
    <span
    class='none'></span><b>Unique Paths II</b><span
    class='date' title='2012-03-29 01:52:12'>Mar 29 '12</span><span
    class='stats' title='4573 accepted submissions out of 11497 (40%)'>4573
    / 11497</span>
    </div><div
    class='row-even question-content'><p>
    Follow up for "Unique Paths":
    </p><p>
    Now consider if some obstacles are added to the grids. How many
    unique paths would there be?
    </p><p>
    An obstacle and empty space is marked as <code>1</code> and
    <code>0</code> respectively in the grid.
    </p><p>
    For example,<br
    />
    <p>
    There is one obstacle in the middle of a 3x3 grid as illustrated
    below.
    </p><pre>
    [
      [0,0,0],
      [0,1,0],
      [0,0,0]
    ]
    </pre><p>
    The total number of unique paths is <code>2</code>.
    </p><p>
    <b>Note:</b> <i>m</i> and <i>n</i> will be at most 100.
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(63, "Unique Paths II"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_63'>(link to this question)</a></span>
    </div></div><div><div
    id='question_62' class='row-odd question-title'>
    <span
    class='none'></span><b>Unique Paths</b><span
    class='date' title='2012-03-28 21:32:23'>Mar 28 '12</span><span
    class='stats' title='5981 accepted submissions out of 13146 (45%)'>5981
    / 13146</span>
    </div><div
    class='row-odd question-content'><p>
    A robot is located at the top-left corner of a <i>m</i> x <i>n</i>
    grid (marked 'Start' in the diagram below).
    </p><p>
    The robot can only move either down or right at any point in time.
    The robot is trying to reach the bottom-right corner of the grid
    (marked 'Finish' in the diagram below).
    </p><p>
    How many possible unique paths are there?
    </p><p> 
    <img
    src="http://4.bp.blogspot.com/_UElib2WLeDE/TNJf8VtC2VI/AAAAAAAACXU/UyUa-9LKp4E/s400/robot_maze.png" /><br
    />
    <p
    style="font-size: 11px">
    Above is a 3 x 7 grid. How many possible unique paths are there?
    </p><p>
    <b>Note:</b> <i>m</i> and <i>n</i> will be at most 100.
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(62, "Unique Paths"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_62'>(link to this question)</a></span>
    </div></div><div><div
    id='question_61' class='row-even question-title'>
    <span
    class='none'></span><b>Rotate List</b><span
    class='date' title='2012-03-28 03:24:25'>Mar 28 '12</span><span
    class='stats' title='5071 accepted submissions out of 17192 (29%)'>5071
    / 17192</span>
    </div><div
    class='row-even question-content'><p>
    Given a list, rotate the list to the right by <i>k</i> places, where
    <i>k</i> is non-negative.
    </p><p>
    For example:<br
    /> Given <code>1-\>2-\>3-\>4-\>5-\>NULL</code> and <i>k</i> =
    <code>2</code>,<br
    /> return <code>4-\>5-\>1-\>2-\>3-\>NULL</code>.
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(61, "Rotate List"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_61'>(link to this question)</a></span>
    </div></div><div><div
    id='question_60' class='row-odd question-title'>
    <span
    class='none'></span><b>Permutation Sequence</b><span
    class='date' title='2012-03-28 02:22:50'>Mar 28 '12</span><span
    class='stats' title='4190 accepted submissions out of 14555 (29%)'>4190
    / 14555</span>
    </div><div
    class='row-odd question-content'><p>
    The set <code>[1,2,3,…,<i>n</i>]</code> contains a total of
    <i>n</i>! unique permutations.
    </p><p>
    By listing and labeling all of the permutations in order,<br
    /> We get the following sequence (ie, for <i>n</i> = 3):
    <ol><li>
    <code>"123"</code>
    </li><li>
    <code>"132"</code>
    </li><li>
    <code>"213"</code>
    </li><li>
    <code>"231"</code>
    </li><li>
    <code>"312"</code>
    </li><li>
    <code>"321"</code>
    </li></ol></p><p>
    Given <i>n</i> and <i>k</i>, return the <i>k</i><sup>th</sup>
    permutation sequence.
    </p><p>
    <b>Note:</b> Given <i>n</i> will be between 1 and 9 inclusive.
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(60, "Permutation Sequence"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_60'>(link to this question)</a></span>
    </div></div><div><div
    id='question_59' class='row-even question-title'>
    <span
    class='none'></span><b>Spiral Matrix II</b><span
    class='date' title='2012-03-28 00:00:51'>Mar 28 '12</span><span
    class='stats' title='3346 accepted submissions out of 7666 (44%)'>3346
    / 7666</span>
    </div><div
    class='row-even question-content'><p>
    Given an integer <i>n</i>, generate a square matrix filled with
    elements from 1 to <i>n</i><sup>2</sup> in spiral order.
    </p><p> 
    For example,<br
    /> Given <i>n</i> = <code>3</code>,
    </p> 
    You should return the following matrix:
    <pre>
    [
     [ 1, 2, 3 ],
     [ 8, 9, 4 ],
     [ 7, 6, 5 ]
    ]
    </pre>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(59, "Spiral Matrix II"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_59'>(link to this question)</a></span>
    </div></div><div><div
    id='question_58' class='row-odd question-title'>
    <span
    class='none'></span><b>Length of Last Word</b><span
    class='date' title='2012-03-27 20:55:46'>Mar 27 '12</span><span
    class='stats' title='5030 accepted submissions out of 12158 (41%)'>5030
    / 12158</span>
    </div><div
    class='row-odd question-content'><p>
    Given a string <i>s</i> consists of upper/lower-case alphabets and
    empty space characters <code>' '</code>, return the length of last
    word in the string.
    </p><p>
    If the last word does not exist, return 0.
    </p><p>
    <b>Note:</b> A word is defined as a character sequence consists of
    non-space characters only.
    </p><p> 
    For example, <br
    /> Given <i>s</i> = <code>"Hello World"</code>,<br
    /> return <code>5</code>.
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(58, "Length of Last Word"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_58'>(link to this question)</a></span>
    </div></div><div><div
    id='question_57' class='row-even question-title'>
    <span
    class='none'></span><b>Insert Interval</b><span
    class='date' title='2012-03-27 19:05:53'>Mar 27 '12</span><span
    class='stats' title='5301 accepted submissions out of 18671 (28%)'>5301
    / 18671</span>
    </div><div
    class='row-even question-content'><p>
    Given a set of <i>non-overlapping</i> intervals, insert a new
    interval into the intervals (merge if necessary).
    </p><p>
    You may assume that the intervals were initially sorted according to
    their start times.
    </p><p> 
    <b>Example 1:</b><br
    /> Given intervals <code>[1,3],[6,9]</code>, insert and merge
    <code>[2,5]</code> in as <code>[1,5],[6,9]</code>.
    </p><p> 
    <b>Example 2:</b><br
    /> Given <code>[1,2],[3,5],[6,7],[8,10],[12,16]</code>, insert and
    merge <code>[4,9]</code> in as <code>[1,2],[3,10],[12,16]</code>.
    </p><p> 
    This is because the new interval <code>[4,9]</code> overlaps with
    <code>[3,5],[6,7],[8,10]</code>.
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(57, "Insert Interval"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_57'>(link to this question)</a></span>
    </div>
    /div\>
    <div><div
    id='question_56' class='row-odd question-title'>
    <span
    class='none'></span><b>Merge Intervals</b><span
    class='date' title='2012-03-27 04:55:58'>Mar 27 '12</span><span
    class='stats' title='5655 accepted submissions out of 20100 (28%)'>5655
    / 20100</span>
    </div><div
    class='row-odd question-content'><p>
    Given a collection of intervals, merge all overlapping intervals.
    </p><p> 
    For example,<br
    /> Given <code>[1,3],[2,6],[8,10],[15,18]</code>,<br
    /> return <code>[1,6],[8,10],[15,18]</code>.
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(56, "Merge Intervals"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_56'>(link to this question)</a></span>
    </div></div><div><div
    id='question_55' class='row-even question-title'>
    <span
    class='none'></span><b>Jump Game</b><span
    class='date' title='2012-03-25 02:00:09'>Mar 25 '12</span><span
    class='stats' title='7493 accepted submissions out of 17569 (43%)'>7493
    / 17569</span>
    </div><div
    class='row-even question-content'><p> 
    Given an array of non-negative integers, you are initially
    positioned at the first index of the array.
    </p><p> 
    Each element in the array represents your maximum jump length at
    that position.
    </p><p> 
    Determine if you are able to reach the last index.
    </p><p> 
    For example:<br
    /> A = <code>[2,3,1,1,4]</code>, return <code>true</code>.
    </p><p> 
    A = <code>[3,2,1,0,4]</code>, return <code>false</code>.
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(55, "Jump Game"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_55'>(link to this question)</a></span>
    </div></div><div><div
    id='question_54' class='row-odd question-title'>
    <span
    class='none'></span><b>Spiral Matrix</b><span
    class='date' title='2012-03-25 01:22:23'>Mar 25 '12</span><span
    class='stats' title='4405 accepted submissions out of 15905 (28%)'>4405
    / 15905</span>
    </div><div
    class='row-odd question-content'><p>
    Given a matrix of <i>m</i> x <i>n</i> elements (<i>m</i> rows,
    <i>n</i> columns), return all elements of the matrix in spiral
    order.
    </p><p> 
    For example,<br
    /> Given the following matrix:
    </p><pre>
    [
     [ 1, 2, 3 ],
     [ 4, 5, 6 ],
     [ 7, 8, 9 ]
    ]
    </pre><p> 
    You should return <code>[1,2,3,6,9,8,7,4,5]</code>.
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(54, "Spiral Matrix"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_54'>(link to this question)</a></span>
    </div></div><div><div
    id='question_53' class='row-even question-title'>
    <span
    class='none'></span><b>Maximum Subarray</b><span
    class='date' title='2012-03-21 13:47:40'>Mar 21 '12</span><span
    class='stats' title='5966 accepted submissions out of 12657 (47%)'>5966
    / 12657</span>
    </div><div
    class='row-even question-content'><p> 
    Find the contiguous subarray within an array (containing at least
    one number) which has the largest sum.
    </p><p> 
    For example, given the array
    <code>[−2,1,−3,4,−1,2,1,−5,4]</code>,<br
    /> the contiguous subarray <code>[4,−1,2,1]</code> has the largest
    sum = <code>6</code>.
    </p><p
    class="showspoilers">
    <a
    href="#" onclick="showSpoilers(this); return false;">click to show
    more practice.</a>
    </p><div
    class="spoilers">
    <b>More practice:</b>
    <p>
    If you have figured out the O(<i>n</i>) solution, try coding another
    solution using the divide and conquer approach, which is more
    subtle.
    </p></div>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(53, "Maximum Subarray"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_53'>(link to this question)</a></span>
    </div></div><div><div
    id='question_52' class='row-odd question-title'>
    <span
    class='none'></span><b>N-Queens II</b><span
    class='date' title='2012-03-20 23:41:00'>Mar 20 '12</span><span
    class='stats' title='4720 accepted submissions out of 10565 (45%)'>4720
    / 10565</span>
    </div><div
    class='row-odd question-content'><p>
    Follow up for N-Queens problem.
    </p><p>
    Now, instead outputting board configurations, return the total
    number of distinct solutions.
    </p><p>
    <img
    src="http://www.leetcode.com/wp-content/uploads/2012/03/8-queens.png" />
    </p>
    <a
    href='#' onclick='clearSavedJudgeCode(); setJudge(52, "N-Queens II"); openConsole(); return false;'>?
    Solve this problem</a><span
    class='link-question'><a
    href='#question_52'>(link to this question)</a></span>
    </div></div><div><div
    id='question_51' class='row-even question-title'>
    <span
    class='none'></span><b>N-Queens</b><span
    class='date' title='2012-03-20 05:24:38'>Mar 20 '12</span><span
    class='stats' title='3976 accepted submissions out of 12479 (32%)'>3976
    / 12479</span>
    </div><div
    class='row-even question-content'><p>
    The <i>n</i>-queens puzzle is the problem of placing <i>n</i> queens
    on an <i>n</i>?<i>n</i> chessboard such that no two queens attack
    each other.
    </p><p>
    <img
    src="http://www.leetcode.com/wp-content/uploads/2012/03/8-queens.png" />
    </p><p>
    Given an integer <i>n</i>, return all distinct solutions to the
    <i>n</i>-queens puzzle.
    </p><p>
    Each solution contains a distinct board configuration of the
    <i>n</i>-queens' placement, where <code>'Q'</code> and
    <code>'.'</code> both indicate a queen and an empty space
    respectively.
    </p><p>
    For example,<br
    /> There exist two distinct solutions to the 4-queens puzzle:
    </p><pre>
    [ [".Q..", // Solution 1 "...Q", "Q...", "..Q."],

["..Q.", // Solution 2 "Q...", "...Q", ".Q.."] ]
</pre>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(51, "N-Queens"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_51'>(link to this question)</a></span>
</div></div><div><div
id='question_50' class='row-odd question-title'>
<span
class='none'></span><b>Pow(x, n)</b><span
class='date' title='2012-03-20 00:00:36'>Mar 20 '12</span><span
class='stats' title='10568 accepted submissions out of 27368 (39%)'>10568
/ 27368</span>
</div><div
class='row-odd question-content'><p>
Implement pow(<i>x</i>, <i>n</i>).
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(50, "Pow(x, n)"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_50'>(link to this question)</a></span>
</div></div><div><div
id='question_49' class='row-even question-title'>
<span
class='none'></span><b>Anagrams</b><span
class='date' title='2012-03-19 13:35:50'>Mar 19 '12</span><span
class='stats' title='5542 accepted submissions out of 18397 (30%)'>5542
/ 18397</span>
</div><div
class='row-even question-content'><p>
Given an array of strings, return all groups of strings that are
anagrams.
</p><p>
Note: All inputs will be in lower-case.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(49, "Anagrams"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_49'>(link to this question)</a></span>
</div></div><div><div
id='question_48' class='row-odd question-title'>
<span
class='none'></span><b>Rotate Image</b><span
class='date' title='2012-03-18 04:22:10'>Mar 18 '12</span><span
class='stats' title='4493 accepted submissions out of 10153 (44%)'>4493
/ 10153</span>
</div><div
class='row-odd question-content'><p>
You are given an <i>n</i> x <i>n</i> 2D matrix representing an image.
</p><p>
Rotate the image by 90 degrees (clockwise).
</p><p>
Follow up:<br
/> Could you do this in-place?
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(48, "Rotate Image"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_48'>(link to this question)</a></span>
</div></div><div><div
id='question_47' class='row-even question-title'>
<span
class='none'></span><b>Permutations II</b><span
class='date' title='2012-03-17 04:36:21'>Mar 17 '12</span><span
class='stats' title='5365 accepted submissions out of 13887 (39%)'>5365
/ 13887</span>
</div><div
class='row-even question-content'><p> 
Given a collection of numbers that might contain duplicates, return all
possible unique permutations.
</p><p> 
For example,<br
/> <code>[1,1,2]</code> have the following unique permutations:<br
/> <code>[1,1,2]</code>, <code>[1,2,1]</code>, and <code>[2,1,1]</code>.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(47, "Permutations II"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_47'>(link to this question)</a></span>
</div></div><div><div
id='question_46' class='row-odd question-title'>
<span
class='none'></span><b>Permutations</b><span
class='date' title='2012-03-17 04:35:42'>Mar 17 '12</span><span
class='stats' title='6281 accepted submissions out of 14628 (43%)'>6281
/ 14628</span>
</div><div
class='row-odd question-content'><p> 
Given a collection of numbers, return all possible permutations.
</p><p> 
For example,<br
/> <code>[1,2,3]</code> have the following permutations:<br
/> <code>[1,2,3]</code>, <code>[1,3,2]</code>, <code>[2,1,3]</code>,
<code>[2,3,1]</code>, <code>[3,1,2]</code>, and <code>[3,2,1]</code>.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(46, "Permutations"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_46'>(link to this question)</a></span>
</div></div><div><div
id='question_45' class='row-even question-title'>
<span
class='none'></span><b>Jump Game II</b><span
class='date' title='2012-03-17 01:49:23'>Mar 17 '12</span><span
class='stats' title='7347 accepted submissions out of 20162 (36%)'>7347
/ 20162</span>
</div><div
class='row-even question-content'><p> 
Given an array of non-negative integers, you are initially positioned at
the first index of the array.
</p><p> 
Each element in the array represents your maximum jump length at that
position.
</p><p> 
Your goal is to reach the last index in the minimum number of jumps.
</p><p> 
For example:<br
/> Given array A = <code>[2,3,1,1,4]</code>
</p><p> 
The minimum number of jumps to reach the last index is <code>2</code>.
(Jump <code>1</code> step from index 0 to 1, then <code>3</code> steps
to the last index.)
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(45, "Jump Game II"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_45'>(link to this question)</a></span>
</div></div><div><div
id='question_44' class='row-odd question-title'>
<span
class='none'></span><b>Wildcard Matching</b><span
class='date' title='2012-03-16 01:40:33'>Mar 16 '12</span><span
class='stats' title='8261 accepted submissions out of 32715 (25%)'>8261
/ 32715</span>
</div><div
class='row-odd question-content'><p>
Implement wildcard pattern matching with support for <code>'?'</code>
and <code>'\*'</code>.
</p><pre>
'?' Matches any single character.
'*' Matches any sequence of characters (including the empty sequence).

The matching should cover the <b>entire</b> input string (not partial).

The function prototype should be:
bool isMatch(const char *s, const char *p)

Some examples:
isMatch("aa","a") ? false
isMatch("aa","aa") ? true
isMatch("aaa","aa") ? false
isMatch("aa", "*") ? true
isMatch("aa", "a*") ? true
isMatch("ab", "?*") ? true
isMatch("aab", "c*a*b") ? false
</pre>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(44, "Wildcard Matching"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_44'>(link to this question)</a></span>
</div></div><div><div
id='question_43' class='row-even question-title'>
<span
class='none'></span><b>Multiply Strings</b><span
class='date' title='2012-03-12 22:02:01'>Mar 12 '12</span><span
class='stats' title='4589 accepted submissions out of 17324 (26%)'>4589
/ 17324</span>
</div><div
class='row-even question-content'><p>
Given two numbers represented as strings, return multiplication of the
numbers as a string.
</p><p>
Note: The numbers can be arbitrarily large and are non-negative.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(43, "Multiply Strings"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_43'>(link to this question)</a></span>
</div></div><div><div
id='question_42' class='row-odd question-title'>
<span
class='none'></span><b>Trapping Rain Water</b><span
class='date' title='2012-03-10 23:05:24'>Mar 10 '12</span><span
class='stats' title='4508 accepted submissions out of 11340 (40%)'>4508
/ 11340</span>
</div><div
class='row-odd question-content'><p> 
Given <i>n</i> non-negative integers representing an elevation map where
the width of each bar is 1, compute how much water it is able to trap
after raining.
</p><p> 
For example, <br
/> Given <code>[0,1,0,2,1,0,1,3,2,1,2,1]</code>, return <code>6</code>.
</p><p> 
<img
src="http://www.leetcode.com/wp-content/uploads/2012/08/rainwatertrap.png" /><br
/>
<p
style="font-size: 11px">
The above elevation map is represented by array
[0,1,0,2,1,0,1,3,2,1,2,1]. In this case, 6 units of rain water (blue
section) are being trapped. <b>Thanks Marcos</b> for contributing this
image!
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(42, "Trapping Rain Water"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_42'>(link to this question)</a></span>
</div></div><div><div
id='question_41' class='row-even question-title'>
<span
class='none'></span><b>First Missing Positive</b><span
class='date' title='2012-03-08 09:22:15'>Mar 8 '12</span><span
class='stats' title='5758 accepted submissions out of 17962 (32%)'>5758
/ 17962</span>
</div><div
class='row-even question-content'><p> 
Given an unsorted integer array, find the first missing positive
integer.
</p><p> 
For example,<br
/> Given <code>[1,2,0]</code> return <code>3</code>,<br
/> and <code>[3,4,-1,1]</code> return <code>2</code>.
</p><p> 
Your algorithm should run in <i>O</i>(<i>n</i>) time and uses constant
space.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(41, "First Missing Positive"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_41'>(link to this question)</a></span>
</div></div><div><div
id='question_40' class='row-odd question-title'>
<span
class='none'></span><b>Combination Sum II</b><span
class='date' title='2012-03-07 01:31:55'>Mar 7 '12</span><span
class='stats' title='4784 accepted submissions out of 14324 (33%)'>4784
/ 14324</span>
</div><div
class='row-odd question-content'><p> 
Given a collection of candidate numbers (<b><i>C</i></b>) and a target
number (<b><i>T</i></b>), find all unique combinations in
<b><i>C</i></b> where the candidate numbers sums to <b><i>T</i></b>.
</p><p>
Each number in <b><i>C</i></b> may only be used <b>once</b> in the
combination.
</p><p>
<b>Note:</b><br
/>
<ul><li>
All numbers (including target) will be positive integers.
</li><li>
Elements in a combination (<i>a</i><sub>1</sub>, <i>a</i><sub>2</sub>, ?
, <i>a</i><sub>k</sub>) must be in non-descending order. (ie,
<i>a</i><sub>1</sub> ? <i>a</i><sub>2</sub> ? ? ? <i>a</i><sub>k</sub>).
</li><li>
The solution set must not contain duplicate combinations.
</li></ul></p><p> 
For example, given candidate set <code>10,1,2,7,6,1,5</code> and target
<code>8</code>, <br
/> A solution set is: <br
/> <code>[1, 7]</code> <br
/> <code>[1, 2, 5]</code> <br
/> <code>[2, 6]</code> <br
/> <code>[1, 1, 6]</code> <br
/>
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(40, "Combination Sum II"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_40'>(link to this question)</a></span>
</div></div><div><div
id='question_39' class='row-even question-title'>
<span
class='none'></span><b>Combination Sum</b><span
class='date' title='2012-03-07 01:31:29'>Mar 7 '12</span><span
class='stats' title='6099 accepted submissions out of 17151 (36%)'>6099
/ 17151</span>
</div><div
class='row-even question-content'><p> 
Given a set of candidate numbers (<b><i>C</i></b>) and a target number
(<b><i>T</i></b>), find all unique combinations in <b><i>C</i></b> where
the candidate numbers sums to <b><i>T</i></b>.
</p><p>
The <b>same</b> repeated number may be chosen from <b><i>C</i></b>
unlimited number of times.
</p><p>
<b>Note:</b><br
/>
<ul><li>
All numbers (including target) will be positive integers.
</li><li>
Elements in a combination (<i>a</i><sub>1</sub>, <i>a</i><sub>2</sub>, ?
, <i>a</i><sub>k</sub>) must be in non-descending order. (ie,
<i>a</i><sub>1</sub> ? <i>a</i><sub>2</sub> ? ? ? <i>a</i><sub>k</sub>).
</li><li>
The solution set must not contain duplicate combinations.
</li></ul></p><p> 
For example, given candidate set <code>2,3,6,7</code> and target
<code>7</code>, <br
/> A solution set is: <br
/> <code>[7]</code> <br
/> <code>[2, 2, 3]</code> <br
/>
</p> 
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(39, "Combination Sum"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_39'>(link to this question)</a></span>
</div></div><div><div
id='question_38' class='row-odd question-title'>
<span
class='none'></span><b>Count and Say</b><span
class='date' title='2012-03-06 01:54:42'>Mar 6 '12</span><span
class='stats' title='4871 accepted submissions out of 13011 (37%)'>4871
/ 13011</span>
</div><div
class='row-odd question-content'><p>
The count-and-say sequence is the sequence of integers beginning as
follows:<br
/> <code>1, 11, 21, 1211, 111221, ...</code>
</p><p> 
<code>1</code> is read off as <code>"one 1"</code> or
<code>11</code>.<br
/> <code>11</code> is read off as <code>"two 1s"</code> or
<code>21</code>.<br
/> <code>21</code> is read off as <code>"one 2</code>, then <code>one
1"</code> or <code>1211</code>.<br
/>
</p><p> 
Given an integer <i>n</i>, generate the <i>n</i><sup>th</sup> sequence.
</p><p> 
Note: The sequence of integers will be represented as a string.
</p> 
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(38, "Count and Say"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_38'>(link to this question)</a></span>
</div></div><div><div
id='question_37' class='row-even question-title'>
<span
class='none'></span><b>Sudoku Solver</b><span
class='date' title='2012-03-04 21:37:08'>Mar 4 '12</span><span
class='stats' title='3375 accepted submissions out of 12622 (27%)'>3375
/ 12622</span>
</div><div
class='row-even question-content'><p>
Write a program to solve a Sudoku puzzle by filling the empty cells.
</p><p>
Empty cells are indicated by the character <code>'.'</code>.
</p><p>
You may assume that there will be only one unique solution.</code>
<p> 
<img
src="http://upload.wikimedia.org/wikipedia/commons/thumb/f/ff/Sudoku-by-L2G-20050714.svg/250px-Sudoku-by-L2G-20050714.svg.png" /><br
/>
<p
style="font-size: 11px">
A sudoku puzzle...
</p></p><p> 
<img
src="http://upload.wikimedia.org/wikipedia/commons/thumb/3/31/Sudoku-by-L2G-20050714_solution.svg/250px-Sudoku-by-L2G-20050714_solution.svg.png" /><br
/>
<p
style="font-size: 11px">
...and its solution numbers marked in red.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(37, "Sudoku Solver"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_37'>(link to this question)</a></span>
</div></div><div><div
id='question_36' class='row-odd question-title'>
<span
class='none'></span><b>Valid Sudoku</b><span
class='date' title='2012-03-03 20:46:32'>Mar 3 '12</span><span
class='stats' title='3545 accepted submissions out of 10545 (34%)'>3545
/ 10545</span>
</div><div
class='row-odd question-content'><p>
Determine if a Sudoku is valid, according to: <a
href="http://sudoku.com.au/TheRules.aspx">Sudoku Puzzles - The
Rules</a>.
</p><p>
The Sudoku board could be partially filled, where empty cells are filled
with the character <code>'.'</code>.
</p><p> 
<img
src="http://upload.wikimedia.org/wikipedia/commons/thumb/f/ff/Sudoku-by-L2G-20050714.svg/250px-Sudoku-by-L2G-20050714.svg.png" /><br
/>
<p
style="font-size: 11px">
A partially filled sudoku which is valid.
</p></p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(36, "Valid Sudoku"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_36'>(link to this question)</a></span>
</div></div><div><div
id='question_35' class='row-even question-title'>
<span
class='none'></span><b>Search Insert Position</b><span
class='date' title='2012-03-03 12:48:53'>Mar 3 '12</span><span
class='stats' title='5789 accepted submissions out of 11556 (50%)'>5789
/ 11556</span>
</div><div
class='row-even question-content'><p>
Given a sorted array and a target value, return the index if the target
is found. If not, return the index where it would be if it were inserted
in order.
</p><p>
You may assume no duplicates in the array.
</p><p> 
Here are few examples.<br
/> <code>[1,3,5,6]</code>, 5 → 2<br
/> <code>[1,3,5,6]</code>, 2 → 1<br
/> <code>[1,3,5,6]</code>, 7 → 4<br
/> <code>[1,3,5,6]</code>, 0 → 0
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(35, "Search Insert Position"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_35'>(link to this question)</a></span>
</div></div><div><div
id='question_34' class='row-odd question-title'>
<span
class='none'></span><b>Search for a Range</b><span
class='date' title='2012-03-03 04:26:10'>Mar 3 '12</span><span
class='stats' title='5829 accepted submissions out of 15540 (38%)'>5829
/ 15540</span>
</div><div
class='row-odd question-content'><p>
Given a sorted array of integers, find the starting and ending position
of a given target value.
</p><p>
Your algorithm's runtime complexity must be in the order of <i>O</i>(log
<i>n</i>).
</p><p>
If the target is not found in the array, return <code>[-1, -1]</code>.
</p><p> 
For example,<br
/> Given <code>[5, 7, 7, 8, 8, 10]</code> and target value 8,<br
/> return <code>[3, 4]</code>.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(34, "Search for a Range"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_34'>(link to this question)</a></span>
</div></div><div><div
id='question_33' class='row-even question-title'>
<span
class='accepted'></span><b>Search in Rotated Sorted Array</b><span
class='date' title='2012-03-03 01:44:58'>Mar 3 '12</span><span
class='stats' title='7237 accepted submissions out of 18907 (38%)'>7237
/ 18907</span>
</div><div
class='row-even question-content'><p>
Suppose a sorted array is rotated at some pivot unknown to you
beforehand.
</p><p>
(i.e., <code>0 1 2 4 5 6 7</code> might become <code>4 5 6 7 0 1
2</code>).
</p><p>
You are given a target value to search. If found in the array return its
index, otherwise return -1.
</p><p>
You may assume no duplicate exists in the array.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(33, "Search in Rotated Sorted Array"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_33'>(link to this question)</a></span>
</div></div><div><div
id='question_32' class='row-odd question-title'>
<span
class='none'></span><b>Longest Valid Parentheses</b><span
class='date' title='2012-03-01 00:47:00'>Mar 1 '12</span><span
class='stats' title='6113 accepted submissions out of 22070 (28%)'>6113
/ 22070</span>
</div><div
class='row-odd question-content'><p>
Given a string containing just the characters <code>'('</code> and
<code>')'</code>, find the length of the longest valid (well-formed)
parentheses substring.
</p><p> 
For <code>"(()"</code>, the longest valid parentheses substring is
<code>"()"</code>, which has length = 2.
</p><p> 
Another example is <code>")()())"</code>, where the longest valid
parentheses substring is <code>"()()"</code>, which has length = 4.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(32, "Longest Valid Parentheses"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_32'>(link to this question)</a></span>
</div></div><div><div
id='question_31' class='row-even question-title'>
<span
class='none'></span><b>Next Permutation</b><span
class='date' title='2012-02-25 16:40:00'>Feb 25 '12</span><span
class='stats' title='4805 accepted submissions out of 13610 (35%)'>4805
/ 13610</span>
</div><div
class='row-even question-content'><p> 
Implement next permutation, which rearranges numbers into the
lexicographically next greater permutation of numbers.
</p><p> 
If such arrangement is not possible, it must rearrange it as the lowest
possible order (ie, sorted in ascending order).
</p><p> 
The replacement must be in-place, do not allocate extra memory.
</p><p> 
Here are some examples. Inputs are in the left-hand column and its
corresponding outputs are in the right-hand column.<br
/> <code>1,2,3</code> → <code>1,3,2</code><br
/> <code>3,2,1</code> → <code>1,2,3</code><br
/> <code>1,1,5</code> → <code>1,5,1</code><br
/>
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(31, "Next Permutation"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_31'>(link to this question)</a></span>
</div></div><div><div
id='question_30' class='row-odd question-title'>
<span
class='none'></span><b>Substring with Concatenation of All
Words</b><span
class='date' title='2012-02-24 02:28:00'>Feb 24 '12</span><span
class='stats' title='5895 accepted submissions out of 21700 (27%)'>5895
/ 21700</span>
</div><div
class='row-odd question-content'><p> 
You are given a string, <b>S</b>, and a list of words, <b>L</b>, that
are all of the same length. Find all starting indices of substring(s) in
S that is a concatenation of each word in L exactly once and without any
intervening characters.
</p><p> 
For example, given:<br
/> <b>S</b>: <code>"barfoothefoobarman"</code><br
/> <b>L</b>: <code>["foo", "bar"]</code>
</p><p> 
You should return the indices: <code>[0,9]</code>.<br
/> (order does not matter).
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(30, "Substring with Concatenation of All Words"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_30'>(link to this question)</a></span>
</div></div><div><div
id='question_29' class='row-even question-title'>
<span
class='none'></span><b>Divide Two Integers</b><span
class='date' title='2012-02-18 19:23:00'>Feb 18 '12</span><span
class='stats' title='6447 accepted submissions out of 27837 (23%)'>6447
/ 27837</span>
</div><div
class='row-even question-content'><p> 
Divide two integers without using multiplication, division and mod
operator.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(29, "Divide Two Integers"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_29'>(link to this question)</a></span>
</div></div><div><div
id='question_28' class='row-odd question-title'>
<span
class='none'></span><b>Implement strStr()</b><span
class='date' title='2012-02-18 16:43:00'>Feb 18 '12</span><span
class='stats' title='7053 accepted submissions out of 22390 (32%)'>7053
/ 22390</span>
</div><div
class='row-odd question-content'><p> 
Implement strStr().
</p><p> 
Returns a pointer to the first occurrence of needle in haystack, or
<b>null</b> if needle is not part of haystack.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(28, "Implement strStr()"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_28'>(link to this question)</a></span>
</div></div><div><div
id='question_27' class='row-even question-title'>
<span
class='none'></span><b>Remove Element</b><span
class='date' title='2012-02-16 23:18:00'>Feb 16 '12</span><span
class='stats' title='6347 accepted submissions out of 13137 (48%)'>6347
/ 13137</span>
</div><div
class='row-even question-content'><p>
Given an array and a value, remove all instances of that value in place
and return the new length.
</p><p> 
The order of elements can be changed. It doesn't matter what you leave
beyond the new length.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(27, "Remove Element"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_27'>(link to this question)</a></span>
</div></div><div><div
id='question_26' class='row-odd question-title'>
<span
class='none'></span><b>Remove Duplicates from Sorted Array</b><span
class='date' title='2012-02-16 12:47:00'>Feb 16 '12</span><span
class='stats' title='6735 accepted submissions out of 14262 (47%)'>6735
/ 14262</span>
</div><div
class='row-odd question-content'><p> 
Given a sorted array, remove the duplicates in place such that each
element appear only <i>once</i> and return the new length.
</p><p> 
Do not allocate extra space for another array, you must do this in place
with constant memory.
</p><p> 
For example,<br
/> Given input array A = <code>[1,1,2]</code>,
</p><p> 
Your function should return length = <code>2</code>, and A is now
<code>[1,2]</code>.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(26, "Remove Duplicates from Sorted Array"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_26'>(link to this question)</a></span>
</div></div><div><div
id='question_25' class='row-even question-title'>
<span
class='none'></span><b>Reverse Nodes in k-Group</b><span
class='date' title='2012-02-16 02:09:00'>Feb 16 '12</span><span
class='stats' title='4578 accepted submissions out of 15390 (30%)'>4578
/ 15390</span>
</div><div
class='row-even question-content'><p> 
Given a linked list, reverse the nodes of a linked list <i>k</i> at a
time and return its modified list.
</p><p> 
If the number of nodes is not a multiple of <i>k</i> then left-out nodes
in the end should remain as it is.
</p><p>
You may not alter the values in the nodes, only nodes itself may be
changed.
</p><p>
Only constant memory is allowed.
</p><p> 
For example,<br
/> Given this linked list: <code>1-\>2-\>3-\>4-\>5</code>
</p><p> 
For <i>k</i> = 2, you should return: <code>2-\>1-\>4-\>3-\>5</code>
</p><p> 
For <i>k</i> = 3, you should return: <code>3-\>2-\>1-\>4-\>5</code>
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(25, "Reverse Nodes in k-Group"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_25'>(link to this question)</a></span>
</div></div><div><div
id='question_24' class='row-odd question-title'>
<span
class='none'></span><b>Swap Nodes in Pairs</b><span
class='date' title='2012-02-15 01:28:00'>Feb 15 '12</span><span
class='stats' title='6098 accepted submissions out of 13527 (45%)'>6098
/ 13527</span>
</div><div
class='row-odd question-content'><p> 
Given a linked list, swap every two adjacent nodes and return its head.
</p><p> 
For example,<br
/> Given <code>1-\>2-\>3-\>4</code>, you should return the list as
<code>2-\>1-\>4-\>3</code>.
</p><p> 
Your algorithm should use only constant space. You may <b>not</b> modify
the values in the list, only nodes itself can be changed.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(24, "Swap Nodes in Pairs"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_24'>(link to this question)</a></span>
</div></div><div><div
id='question_23' class='row-even question-title'>
<span
class='none'></span><b>Merge k Sorted Lists</b><span
class='date' title='2012-02-14 00:41:00'>Feb 14 '12</span><span
class='stats' title='6213 accepted submissions out of 20674 (30%)'>6213
/ 20674</span>
</div><div
class='row-even question-content'><p> 
Merge <i>k</i> sorted linked lists and return it as one sorted list.
Analyze and describe its complexity.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(23, "Merge k Sorted Lists"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_23'>(link to this question)</a></span>
</div></div><div><div
id='question_22' class='row-odd question-title'>
<span
class='none'></span><b>Generate Parentheses</b><span
class='date' title='2012-02-13 03:00:00'>Feb 13 '12</span><span
class='stats' title='6413 accepted submissions out of 14970 (43%)'>6413
/ 14970</span>
</div><div
class='row-odd question-content'><p> 
Given <i>n</i> pairs of parentheses, write a function to generate all
combinations of well-formed parentheses.
</p><p> 
For example, given <i>n</i> = 3, a solution set is:
</p><p> 
<code>"((()))", "(()())", "(())()", "()(())", "()()()"</code>
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(22, "Generate Parentheses"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_22'>(link to this question)</a></span>
</div></div><div><div
id='question_20' class='row-even question-title'>
<span
class='none'></span><b>Valid Parentheses</b><span
class='date' title='2012-01-30 12:56:00'>Jan 30 '12</span><span
class='stats' title='5976 accepted submissions out of 15549 (38%)'>5976
/ 15549</span>
</div><div
class='row-even question-content'><p>
Given a string containing just the characters <code>'('</code>,
<code>')'</code>, <code>'{'</code>, <code>'}'</code>, <code>'['</code>
and <code>']'</code>, determine if the input string is valid.
</p><p>
The brackets must close in the correct order, <code>"()"</code> and
<code>"()[]{}"</code> are all valid but <code>"(]"</code> and
<code>"([)]"</code> are not.
</p> 
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(20, "Valid Parentheses"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_20'>(link to this question)</a></span>
</div></div><div><div
id='question_19' class='row-odd question-title'>
<span
class='accepted'></span><b>Remove Nth Node From End of List</b><span
class='date' title='2012-01-28 01:57:00'>Jan 28 '12</span><span
class='stats' title='6630 accepted submissions out of 17308 (38%)'>6630
/ 17308</span>
</div><div
class='row-odd question-content'><p>
Given a linked list, remove the <i>n</i><sup>th</sup> node from the end
of list and return its head.
</p><p> 
For example,
</p><pre>
   Given linked list: <b>1->2->3->4->5</b>, and <b><i>n</i> = 2</b>.

   After removing the second node from the end, the linked list becomes <b>1->2->3->5</b>.
</pre><p> 
<b>Note:</b><br
/> Given <i>n</i> will always be valid.<br
/> Try to do this in one pass.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(19, "Remove Nth Node From End of List"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_19'>(link to this question)</a></span>
</div></div><div><div
id='question_17' class='row-even question-title'>
<span
class='none'></span><b>Letter Combinations of a Phone Number</b><span
class='date' title='2012-01-27 05:17:00'>Jan 27 '12</span><span
class='stats' title='5504 accepted submissions out of 16698 (33%)'>5504
/ 16698</span>
</div><div
class='row-even question-content'><p>
Given a digit string, return all possible letter combinations that the
number could represent.
</p><p> 
A mapping of digit to letters (just like on the telephone buttons) is
given below.
</p><p>
<img
src="http://upload.wikimedia.org/wikipedia/commons/thumb/7/73/Telephone-keypad2.svg/200px-Telephone-keypad2.svg.png" />
</p><pre>
<b>Input:</b>Digit string "23"
<b>Output:</b> ["ad", "ae", "af", "bd", "be", "bf", "cd", "ce", "cf"].
</pre><p> 
<b>Note:</b><br
/> Although the above answer is in lexicographical order, your answer
could be in any order you want.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(17, "Letter Combinations of a Phone Number"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_17'>(link to this question)</a></span>
</div></div><div><div
id='question_18' class='row-odd question-title'>
<span
class='none'></span><b>4Sum</b><span
class='date' title='2012-01-27 05:17:00'>Jan 27 '12</span><span
class='stats' title='6382 accepted submissions out of 19016 (34%)'>6382
/ 19016</span>
</div><div
class='row-odd question-content'><p>
Given an array <i>S</i> of <i>n</i> integers, are there elements
<i>a</i>, <i>b</i>, <i>c</i>, and <i>d</i> in <i>S</i> such that
<i>a</i> + <i>b</i> + <i>c</i> + <i>d</i> = target? Find all unique
quadruplets in the array which gives the sum of target.
</p><p>
<b>Note:</b><br
/>
<ul><li>
Elements in a quadruplet (<i>a</i>,<i>b</i>,<i>c</i>,<i>d</i>) must be
in non-descending order. (ie, <i>a</i> ? <i>b</i> ? <i>c</i> ? <i>d</i>)
</li><li>
The solution set must not contain duplicate quadruplets.
</li></ul></p><pre>
    For example, given array S = {1 0 -1 0 -2 2}, and target = 0.

    A solution set is:
    (-1,  0, 0, 1)
    (-2, -1, 1, 2)
    (-2,  0, 0, 2)
</pre>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(18, "4Sum"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_18'>(link to this question)</a></span>
</div></div><div><div
id='question_16' class='row-even question-title'>
<span
class='none'></span><b>3Sum Closest</b><span
class='date' title='2012-01-18 21:02:00'>Jan 18 '12</span><span
class='stats' title='6070 accepted submissions out of 15852 (38%)'>6070
/ 15852</span>
</div><div
class='row-even question-content'><p>
Given an array <i>S</i> of <i>n</i> integers, find three integers in
<i>S</i> such that the sum is closest to a given number, target. Return
the sum of the three integers. You may assume that each input would have
exactly one solution.
</p><pre>
    For example, given array S = {-1 2 1 -4}, and target = 1.

    The sum that is closest to the target is 2. (-1 + 2 + 1 = 2).
</pre>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(16, "3Sum Closest"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_16'>(link to this question)</a></span>
</div></div><div><div
id='question_15' class='row-odd question-title'>
<span
class='none'></span><b>3Sum</b><span
class='date' title='2012-01-18 01:33:00'>Jan 18 '12</span><span
class='stats' title='9830 accepted submissions out of 38290 (26%)'>9830
/ 38290</span>
</div><div
class='row-odd question-content'><p>
Given an array <i>S</i> of <i>n</i> integers, are there elements
<i>a</i>, <i>b</i>, <i>c</i> in <i>S</i> such that <i>a</i> + <i>b</i> +
<i>c</i> = 0? Find all unique triplets in the array which gives the sum
of zero.
</p><p>
<b>Note:</b><br
/>
<ul><li>
Elements in a triplet (<i>a</i>,<i>b</i>,<i>c</i>) must be in
non-descending order. (ie, <i>a</i> ? <i>b</i> ? <i>c</i>)
</li><li>
The solution set must not contain duplicate triplets.
</li></ul></p><pre>
    For example, given array S = {-1 0 1 2 -1 -4},

    A solution set is:
    (-1, 0, 1)
    (-1, -1, 2)
</pre>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(15, "3Sum"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_15'>(link to this question)</a></span>
</div></div><div><div
id='question_14' class='row-even question-title'>
<span
class='none'></span><b>Longest Common Prefix</b><span
class='date' title='2012-01-17 11:04:00'>Jan 17 '12</span><span
class='stats' title='6659 accepted submissions out of 18460 (36%)'>6659
/ 18460</span>
</div><div
class='row-even question-content'><p>
Write a function to find the longest common prefix string amongst an
array of strings.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(14, "Longest Common Prefix"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_14'>(link to this question)</a></span>
</div></div><div><div
id='question_13' class='row-odd question-title'>
<span
class='none'></span><b>Roman to Integer</b><span
class='date' title='2012-01-15 23:22:00'>Jan 15 '12</span><span
class='stats' title='3996 accepted submissions out of 8336 (48%)'>3996 /
8336</span>
</div><div
class='row-odd question-content'><p>
Given a roman numeral, convert it to an integer.
</p><p>
Input is guaranteed to be within the range from 1 to 3999.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(13, "Roman to Integer"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_13'>(link to this question)</a></span>
</div></div><div><div
id='question_12' class='row-even question-title'>
<span
class='none'></span><b>Integer to Roman</b><span
class='date' title='2012-01-15 23:21:00'>Jan 15 '12</span><span
class='stats' title='4166 accepted submissions out of 10195 (41%)'>4166
/ 10195</span>
</div><div
class='row-even question-content'><p>
Given an integer, convert it to a roman numeral.
</p><p>
Input is guaranteed to be within the range from 1 to 3999.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(12, "Integer to Roman"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_12'>(link to this question)</a></span>
</div></div><div><div
id='question_11' class='row-odd question-title'>
<span
class='none'></span><b>Container With Most Water</b><span
class='date' title='2012-01-09 01:17:00'>Jan 9 '12</span><span
class='stats' title='6382 accepted submissions out of 14504 (44%)'>6382
/ 14504</span>
</div><div
class='row-odd question-content'><p>
Given <i>n</i> non-negative integers <i>a<sub>1</sub></i>,
<i>a<sub>2</sub></i>, ..., <i>a<sub>n</sub></i>, where each represents a
point at coordinate (<i>i</i>, <i>a<sub>i</sub></i>). <i>n</i> vertical
lines are drawn such that the two endpoints of line <i>i</i> is at
(<i>i</i>, <i>a<sub>i</sub></i>) and (<i>i</i>, 0). Find two lines,
which together with x-axis forms a container, such that the container
contains the most water.
</p><p>
Note: You may not slant the container.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(11, "Container With Most Water"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_11'>(link to this question)</a></span>
</div></div><div><div
id='question_10' class='row-even question-title'>
<span
class='none'></span><b>Regular Expression Matching</b><span
class='date' title='2012-01-08 18:31:00'>Jan 8 '12</span><span
class='stats' title='7137 accepted submissions out of 26894 (27%)'>7137
/ 26894</span>
</div><div
class='row-even question-content'><p>
Implement regular expression matching with support for <code>'.'</code>
and <code>'\*'</code>.
</p><pre>
'.' Matches any single character.
'*' Matches zero or more of the preceding element.

The matching should cover the <b>entire</b> input string (not partial).

The function prototype should be:
bool isMatch(const char *s, const char *p)

Some examples:
isMatch("aa","a") ? false
isMatch("aa","aa") ? true
isMatch("aaa","aa") ? false
isMatch("aa", "a*") ? true
isMatch("aa", ".*") ? true
isMatch("ab", ".*") ? true
isMatch("aab", "c*a*b") ? true
</pre>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(10, "Regular Expression Matching"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_10'>(link to this question)</a></span>
</div></div><div><div
id='question_9' class='row-odd question-title'>
<span
class='accepted'></span><b>Palindrome Number</b><span
class='date' title='2012-01-04 23:18:00'>Jan 4 '12</span><span
class='stats' title='7619 accepted submissions out of 19000 (40%)'>7619
/ 19000</span>
</div><div
class='row-odd question-content'><p>
Determine whether an integer is a palindrome. Do this without extra
space.
</p><p
class="showspoilers">
<a
href="#" onclick="showSpoilers(this); return false;">click to show
spoilers.</a>
</p><div
class="spoilers">
<b>Some hints:</b>
<p>
Could negative integers be palindromes? (ie, -1)
</p><p>
If you are thinking of converting the integer to string, note the
restriction of using extra space.
</p><p>
You could also try reversing an integer. However, if you have solved the
problem "Reverse Integer", you know that the reversed integer might
overflow. How would you handle such case?
</p><p>
There is a more generic way of solving this problem.
</p></div>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(9, "Palindrome Number"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_9'>(link to this question)</a></span>
</div></div><div><div
id='question_8' class='row-even question-title'>
<span
class='accepted'></span><b>String to Integer (atoi)</b><span
class='date' title='2011-12-27 05:13:00'>Dec 27 '11</span><span
class='stats' title='7626 accepted submissions out of 35090 (22%)'>7626
/ 35090</span>
</div><div
class='row-even question-content'><p>
Implement <span
style="font-family:monospace">atoi</span> to convert a string to an
integer.
</p><p>
<b>Hint:</b> Carefully consider all possible input cases. If you want a
challenge, please do not see below and ask yourself what are the
possible input cases.
</p><p> 
<b>Notes:</b> It is intended for this problem to be specified vaguely
(ie, no given input specs). You are responsible to gather all the input
requirements up front.
</p><p
class="showspoilers">
<a
href="#" onclick="showSpoilers(this); return false;">spoilers alert...
click to show requirements for atoi.</a>
</p><div
class="spoilers">
<b>Requirements for atoi:</b>
<p>
The function first discards as many whitespace characters as necessary
until the first non-whitespace character is found. Then, starting from
this character, takes an optional initial plus or minus sign followed by
as many numerical digits as possible, and interprets them as a numerical
value.
</p><p>
The string can contain additional characters after those that form the
integral number, which are ignored and have no effect on the behavior of
this function.
</p><p>
If the first sequence of non-whitespace characters in str is not a valid
integral number, or if no such sequence exists because either str is
empty or it contains only whitespace characters, no conversion is
performed.
</p><p>
If no valid conversion could be performed, a zero value is returned. If
the correct value is out of the range of representable values, INT\_MAX
(2147483647) or INT\_MIN (-2147483648) is returned.
</p></div>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(8, "String to Integer (atoi)"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_8'>(link to this question)</a></span>
</div></div><div><div
id='question_7' class='row-odd question-title'>
<span
class='none'></span><b>Reverse Integer</b><span
class='date' title='2011-12-26 04:36:00'>Dec 26 '11</span><span
class='stats' title='8021 accepted submissions out of 14285 (56%)'>8021
/ 14285</span>
</div><div
class='row-odd question-content'><p>
Reverse digits of an integer.
</p><p
style="font-family:monospace"> 
<b>Example1:</b> x = 123, return 321<br
/> <b>Example2:</b> x = -123, return -321
</p><p
class="showspoilers">
<a
href="#" onclick="showSpoilers(this); return false;">click to show
spoilers.</a>
</p><div
class="spoilers">
<b>Have you thought about this?</b>
<p>
Here are some good questions to ask before coding. Bonus points for you
if you have already thought through this!
</p><p>
If the integer's last digit is 0, what should the output be? ie, cases
such as 10, 100.
</p><p>
Did you notice that the reversed integer might overflow? Assume the
input is a 32-bit integer, then the reverse of 1000000003 overflows. How
should you handle such cases?
</p><p>
Throw an exception? Good, but what if throwing an exception is not an
option? You would then have to re-design the function (ie, add an extra
parameter).
</p></div>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(7, "Reverse Integer"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_7'>(link to this question)</a></span>
</div></div><div><div
id='question_6' class='row-even question-title'>
<span
class='none'></span><b>ZigZag Conversion</b><span
class='date' title='2011-12-06 03:59:00'>Dec 6 '11</span><span
class='stats' title='6562 accepted submissions out of 18872 (35%)'>6562
/ 18872</span>
</div><div
class='row-even question-content'><p> 
The string <code>"PAYPALISHIRING"</code> is written in a zigzag pattern
on a given number of rows like this: (you may want to display this
pattern in a fixed font for better legibility)
<pre>
P   A   H   N
A P L S I I G
Y   I   R
</pre>
And then read line by line: <code>"PAHNAPLSIIGYIR"</code>
</p><p> 
Write the code that will take a string and make this conversion given a
number of rows:
<pre>string convert(string text, int nRows);</pre>
<code>convert("PAYPALISHIRING", 3)</code> should return
<code>"PAHNAPLSIIGYIR"</code>.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(6, "ZigZag Conversion"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_6'>(link to this question)</a></span>
</div></div><div><div
id='question_5' class='row-odd question-title'>
<span
class='none'></span><b>Longest Palindromic Substring</b><span
class='date' title='2011-11-11 10:07:00'>Nov 11 '11</span><span
class='stats' title='8767 accepted submissions out of 28389 (31%)'>8767
/ 28389</span>
</div><div
class='row-odd question-content'><p>
Given a string <i>S</i>, find the longest palindromic substring in
<i>S</i>. You may assume that the maximum length of <i>S</i> is 1000,
and there exists one unique longest palindromic substring.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(5, "Longest Palindromic Substring"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_5'>(link to this question)</a></span>
</div></div><div><div
id='question_2' class='row-even question-title'>
<span
class='none'></span><b>Add Two Numbers</b><span
class='date' title='2011-11-01 21:00:00'>Nov 1 '11</span><span
class='stats' title='9607 accepted submissions out of 32573 (29%)'>9607
/ 32573</span>
</div><div
class='row-even question-content'><p>
You are given two linked lists representing two non-negative numbers.
The digits are stored in reverse order and each of their nodes contain a
single digit. Add the two numbers and return it as a linked list.
</p><p
style="font-family:monospace"> 
<b>Input:</b> <code>(2 -\> 4 -\> 3) + (5 -\> 6 -\> 4)</code><br
/> <b>Output:</b> <code>7 -\> 0 -\> 8</code>
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(2, "Add Two Numbers"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_2'>(link to this question)</a></span>
</div></div><div><div
id='question_3' class='row-odd question-title'>
<span
class='accepted'></span><b>Longest Substring Without Repeating
Characters</b><span
class='date' title='2011-05-16 03:39:00'>May 16 '11</span><span
class='stats' title='11147 accepted submissions out of 33568 (33%)'>11147
/ 33568</span>
</div><div
class='row-odd question-content'><p>
Given a string, find the length of the longest substring without
repeating characters. For example, the longest substring without
repeating letters for "abcabcbb" is "abc", which the length is 3. For
"bbbbb" the longest substring is "b", with the length of 1.
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(3, "Longest Substring Without Repeating Characters"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_3'>(link to this question)</a></span>
</div></div><div><div
id='question_4' class='row-even question-title'>
<span
class='none'></span><b>Median of Two Sorted Arrays</b><span
class='date' title='2011-03-28 02:23:00'>Mar 28 '11</span><span
class='stats' title='7725 accepted submissions out of 38502 (20%)'>7725
/ 38502</span>
</div><div
class='row-even question-content'><p>
There are two sorted arrays A and B of size m and n respectively. Find
the median of the two sorted arrays. The overall run time complexity
should be O(log (m+n)).
</p>
<a
href='#' onclick='clearSavedJudgeCode(); setJudge(4, "Median of Two Sorted Arrays"); openConsole(); return false;'>?
Solve this problem</a><span
class='link-question'><a
href='#question_4'>(link to this question)</a></span>
</div></div><div><div
id='question_1' class='row-odd question-title'>
<span
class='none'></span><b>Two Sum</b><span
class='date' title='2011-03-14 05:13:00'>Mar 14 '11</span><span
class='stats' title='15259 accepted submissions out of 48327 (32%)'>15259
/ 48327</span>
</div><div
class='row-odd question-content'><p>
Given an array of integers, find two numbers such that they add up to a
specific target number.
</p><p>
The function twoSum should return indices of the two numbers such that
they add up to the target, where index1 must be less than index2. Please
note that your returned answers (both index1 and index2) are not
zero-based.
</p><p>
You may assume that each input would have exactly one solution.
</p><p
style="font-family:monospace"> 
<b>Input:</b> numbers={2, 7, 11, 15}, target=9<br
/> <b>Output:</b> index1=1, index2=2
</p>


