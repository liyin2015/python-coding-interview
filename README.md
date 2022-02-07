# **Hands-on Algorithmic Problem Solving** [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Contributing
The book is written in latex, and all contents except the code is located under [**Easy-Book** folder](Easy-Book). Feel free to send me  [pull requests](https://github.com/liyin2015/python-coding-interview/pulls) or email (li.yin.gravity@gmail.com) to contribute contents. Before you start to improve the contents, it would be helpful to know the [high-level of the structure of the book](#about-this-book).


## A one-stop coding interview prep book!
<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->
<!-- display the social media buttons in your README -->

[![alt text][3.1]][3] [![Medium Blog][4.1]][4]
<!-- [![alt text][1.1]][1]
[![alt text][2.1]][2] -->

<!--[![alt text][5.1]][5]
[![alt text][6.1]][6]-->

<!-- links to social media icons -->
<!-- no need to change these -->

<!-- icons with padding -->

[1.1]: http://i.imgur.com/tXSoThF.png (twitter icon with padding)
[2.1]: http://i.imgur.com/P3YfQoD.png (facebook icon with padding)
[3.1]: https://www.iconfinder.com/icons/2329259/download/png/32 (google plus icon with padding)
[4.1]: https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white
<!--[4.1]: http://i.imgur.com/YckIOms.png (tumblr icon with padding)-->
<!--[5.1]: http://i.imgur.com/1AGmwO3.png (dribbble icon with padding)
[6.1]: http://i.imgur.com/0o48UoR.png (github icon with padding)-->

<!-- icons without padding -->

[1.2]: http://i.imgur.com/wWzX9uB.png (twitter icon without padding)
[2.2]: http://i.imgur.com/fep1WsG.png (facebook icon without padding)
[3.2]: http://i.imgur.com/VlgBKQ9.png (google plus icon without padding)
[4.2]: http://i.imgur.com/jDRp47c.png (tumblr icon without padding)
[5.2]: http://i.imgur.com/Vvy3Kru.png (dribbble icon without padding)
[6.2]: http://i.imgur.com/9I6NRUm.png (github icon without padding)


<!-- links to your social media accounts -->
<!-- update these accordingly -->
[1]: https://twitter.com/liyinscience
[2]: https://www.facebook.com/li.yin.355
[3]: https://www.linkedin.com/in/li-yin-00b0456b/
[4]: https://medium.com/algorithms-and-leetcode
[5]: https://www.liyinscience.com/

## About this book

<p align="center">
  <img src="figures/book_structure.png" alt="book_structure" width="500" height="300" title="Figure 1. Four umbrellas:  each row indicates corresponding parts as outlined in this book."/>
</p>


In short, this is a middle-to-high level algorithm book designed with cracking coding interviews at hearts. It offers a one-stop coding interview prep experience. The structure of the book: 
* **Preparation**: introduce the global picture of algorithmic problem solving and coding interviews, learn abstract data structures and highly related and useful math such as recurrence relation, and hands-on Python practice by relating the abstract data structures to Python data structures. *Coding is not just code after all.*, 
* **Principles**: we organize the design and principle here so that readers can use them as guidance while not seeking for peculiar algorithm for solving a problem. 
* **Classical algorithms**: We enhance our algorithm database via learning how to apply the core principles to a variety of classical problems. A database that we can quickly relate to when seeing problems.
* **Coding interview problem patterns**:  We close our book with the analyzing and categorizing problems by patterns. We address classical and best solutions for each problem pattern. 



Besides trying to make the content easy to follow, here summarizes the uniqueness of this book: (1) it offers Python source code that is tailored to be simple so that it would be natural for you to use in interviews (2) all the exercises and examples are from Leetcode problems so that you get to practise online (3) Classical algorithms are explained with design principles. No algorithm is magic. (Check out [advanced graph algorithms](https://github.com/liyin2015/Hands-on-Algorithmic-Problem-Solving/blob/master/chapters_pdf/chapter_advanced_graph_algorithm.pdf) as an example) (4) problem patterns to help you tackle coding interview questions topic by topic.
## How did I come up with this book?
Preparing for the coding interview is not easy! Cracking the coding interview? Nearly impossible for most of us! Luck does play a role in the outcome. So, let's just treat it as a learning process and have some fun!

Computer Science is really not just computer science. It is a combination of all fields; our normal interview problems fall into the enumerative combinatorics and our computer vision mostly consists of Linear Algebra. What really matters is our passion to learn and the ability to apply this knowledge to solve real-life problems. 

There are plenty of books out there focusing on either teaching algorithmic knowledge  (*Introduction to Algorithms*, *Algorithmic Problem Solving*, etc) or introducing the interview process and solving interview problems(*Cracking the Coding Interview*, *Coding Interview Questions*, etc), but none of these books truly combine the two. This is a book designed to make up this role in the categorization. Principle, Pattern, and Leetcode Problems make up the core of this book.

This is **NOT** a book that provides hiring statistics for each company or gives the reader quick tricks in order to pass a few coding interviews.  Its purpose is to show you the beauty of algorithmic problem solving in the hope that you will be more passionate and confident about software engineering; the interview questions just set up a playground where we strengthen what we learn. 


## Table of Contents

### Warm Up: Abstract Data Structures and Tools
* [Abstract Data Structures](chapters_pdf/Abstract_Data_Structures.pdf)
* Discrete Programming
* Recurrence Relation

### Get Started: Programming and Python Data Structures
* Iteration and Recursion
* Bit Manipulation
* [**Python Data Structures**](chapters_pdf/Python_Data_Structure.pdf)( [source code](Colab_Codes/chapter_python_datastrcutures.ipynb) )

### Core Principles: Algorithm Design and Analysis
* Complexity Analysis
* [Search Strategies](chapters_pdf/search_strategies.pdf)([source code: Graph Search](Colab_Codes/chapter_search_strategies.ipynb), [source code: Tree Traversal](Colab_Codes/chapter_tree_data_structure_and_traversal.ipynb))
* [Combinatorial Search](chapters_pdf/combinatorial_search.pdf)( [source code](Colab_Codes/chapter_combinatorial_search.ipynb))
* Reduce and Conquer

* **Decrease and Conquer**
> * [Binary Search, Binary Search Tree, and Segment Tree](chapters_pdf/decrease_and_conquer.pdf)( [source code](Colab_Codes/chapter_decrease_and_conquer.ipynb))
* [**Sorting and Selection**](chapters_pdf/sorting_algorithms_with_python3.pdf)( source code: [ sorting algorithms](Colab_Codes/chapter_sorting_and_selection_algorithms.ipynb),[ Python comparison and sort functions](Colab_Codes/chapter_python_comparison_sorting.ipynb))
* Dynamic Programming
* Greedy Algorithms

### Advanced Algorithms 
* Advanced Data Structures
* [**Advanced Search on Linear Data Structures**](chapters_pdf/advanced_search_on_linear_data_structures.pdf)( [source code](Colab_Codes/Advanced_Search_on_Linear_Data_Structures.ipynb))
* [Advanced Graph Algorithms](chapters_pdf/chapter_advanced_graph_algorithm.pdf)
* String Pattern Matches
* Math and Geometry Algorithms

### Problem Patterns
* Dynamic Programming Questions (15%)
* Array Questions (15%)
* Linked List, Stack, Queue, and Heap Questions (12%)
* String Questions (15%)
* [Tree Questions (10%)](unorganized_pdf/tree_questions.pdf)
* Graph Questions (15%)

*Note: everything is still in progress, so use it with caution.*

## Referring Books and Materials

* Skiena, Steven S. The algorithm design manual: Text. Vol. 1. Springer Science & Business Media, 1998.

* T. H. Cormen, Introduction to algorithms, MIT press, 2009.

* Manber, Udi. Introduction to algorithms: a creative approach. Addison-Wesley Longman Publishing Co., Inc., 1989.

* Kleinberg, Jon, and Eva Tardos. Algorithm design. Pearson Education India, 2006.

* Russell, Stuart J., and Peter Norvig. Artificial intelligence: a modern approach. Malaysia; Pearson Education Limited,, 2016. (**Best book ever in explaining searching problem-solving, differentiate tree-search and graph-search**)

* D. M. Beazley, Python essential reference, Addison-Wesley Professional,2009.

* S. Halim and F. Halim, Competitive Programming 3, Lulu Independent
Publish, 2013.

* B. Slatkin, Effective Python: 59 Specific Ways to Write Better Python,Pearson Education, 2015.

* H. hua jiang, “Leetcode blogs,” https://zxi.mytechroad.com/blog/category, 2018, [Online; accessed 19-July-2018].

* B. Baka, “Python data structures and algorithms: Improve application performance with graphs, stacks, and queues,” 2017.

* “Competitive  Programming,”https://cp-algorithms.com/,  2019, [Online; accessed 19-July-2018].

* “cs  princeton,”https://aofa.cs.princeton.edu/60trees/,  2019,
[Online; accessed 19-July-2018]
* https://stanford-cs161.github.io/winter2021/schedule/

## Tools
* Graph Visualize with [graphviz](http://www.webgraphviz.com/). [Examples](https://graphs.grevian.org/example). [Tutorial to use Python](https://graphviz.readthedocs.io/en/stable/manual.html)

## Mocking Interviews
Practice is important. Schedule some mocking interviews with [interviewing.io](https://interviewing.io/). If you cant manage to register, you can join us in [discord server](https://discord.gg/ZXnSag7fMP) and ask peers for practice interview.

## Community
**Join me on discord server: https://discord.gg/ZXnSag7fMP, for early access of the book and a supportive community**

## Feedback
If you have ideas to improve the book, about formatting, more contents, or correct the errors, do not hesitate to let me know. 

<!---## Copyright
The book is copyrighed and protected, please do not spread without permission. ---!>
