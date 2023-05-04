Download Link: https://assignmentchef.com/product/solved-csce-629-analysis-of-algorithms-assignment-2
<br>






<strong>(</strong>

<ol>

 <li>Design algorithms for Min(<em>H</em>), Insert(<em>H,a</em>), and Delete(<em>H,i</em>), where the set <em>H </em>is stored in a heap, <em>a </em>is the element to be inserted into the heap <em>H</em>, and <em>i </em>is the index of the element in the heap <em>H </em>to be deleted. Analyze the complexity of your algorithms.</li>

</ol>

<strong>Remark. </strong>In the following questions, you can assume that your graphs are connected.

<ol start="2">

 <li>Write the psuedo-code for the Dijstra’s algorithm that solves the Single-Source Shortest Path Analyze the complexity of the algorithm (you can assume that the algorithm uses a heap for fringes and you can use your results in Question 1 directly). Give a formal proof that the algorithm works correctly when the edge weights are all non-negative.</li>

 <li>Develop a linear-time (i.e., <em>O</em>(<em>m</em>)-time) algorithm that solves the Single-Source Shortest Path problem for graphs whose edge weights are positive integers bounded by 10. ( You can either modify Dijstra’s algorithm or consider using Breath-First-Search.)</li>

 <li>Consider an extended version of the Shortest-Path Suppose that you want to traverse from city <em>s </em>to city <em>t</em>. In addition, for some reason, you also need to pass through cities <em>x</em>, <em>y</em>, and <em>z </em>(in any order) during your trip. Your objective is to minimize the cost of the trip. The problem can be formulated as a graph problem as follows: Given a positively weighted directed graph <em>G </em>and five vertices <em>s</em>, <em>t</em>, <em>x</em>, <em>y</em>, <em>z</em>, find a path from <em>s </em>to <em>t </em>that contains the vertices <em>x</em>, <em>y</em>, <em>z </em>such that the path is the shortest over all paths from <em>s </em>to <em>t </em>that contain <em>x</em>, <em>y</em>, <em>z</em>, assuming that these paths are allowed to contain repeated vertices and edges. Develop an <em>O</em>(<em>m</em>log<em>n</em>)-time algorithm for this problem.</li>

</ol>


