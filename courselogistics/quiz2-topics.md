CS4102 - Quiz 2 Topics and Information 
===============================

[Back to Main Page](../index.html)

<a name="introduction"></a>Overview
---------------------------------------

Module 2's quiz is on lectures and readings from March 1 through March 17.  The following topic list is a guide, and we may update it before the quiz in response to student questions.  See the slides and recordings for more details and readings associated with these topics.  A basic rule we'll try to follow is this: if it's in the readings, but we didn't mention it in lecture, it will *not* be on the quiz.

Document Version: 1.0, March 24, 11:30am


How the Quiz Will Be Given and Other Rules
----------------------------------------------

*Check back later!*  We are going to try to use GradeScope for quizzes instead of Collab. We're working on details and will announce what's happening by Thursday afternoon.


Honor Policy for this Quiz
---------------------------------
Before you take our quiz, we’d like to remind you about our rules and the Honor Pledge (as documented in the document linked above), and your commitment to your own personal integrity. With education moving online across the country, reports of cheating on exams are in the news at UVA and everywhere.

It’s hard to explain how disappointing cheating is for a professor who’s worked hard to make a fair and reasonable exam that can be delivered online to students given this current unfortunate situation with the pandemic. The world is a tough place right now, but how individuals react, the decisions they make, and the actions they take in hard times help define who someone is. Of course we instructors would be disappointed to learn of cheating in the course, but frankly it’s not about us but about you. What you do says something (to you, to others) about the kind of person you believe you are and the kind of person you want to be.

So we urge you to be the right kind of person. You can be, you ought to want to be, you probably are all or most of the time. But making the wrong decision when you’ve been asked to commit to and pledge that you’ve followed rules for academic integrity is a mistake that damages your personal integrity in return for a grade in a class. In the long term, a grade matters much less than the kind of person you believe you are and what your actions show you to be.

We've put in a fair bit of thinking and effort to make things easier for you this term with our system of grading, the chance to re-take quizzes, etc. We need to balance the need to get an accurate assessment of your success in learning with making your lives reasaonably bearable. To take advantage of us as we're trying to do things the right way is wrong and does you damage.

All the best in these difficult times of pandemic and online learning!  We hope you do great on quizzes, projects, etc., but what we want more is for you to be good people. We believe you can be and want to be, so be that!


Sample Questions, Practice Quiz
-------------------------------------------------
(Under Construction!)

Here are some sample questions:

*Sample Q1:* TBD

Topics that will be covered on the quiz include:
-------------------------------------------------


- Graphs
    - No specific questions on review from earlier courses, adjacency list vs. matrix, etc., but understanding these topics may be needed in other questions
    
- BFS
    - The strategy and algorithm, including use of queue, marking nodes, levels of the tree, non-tree edges, time-complexity
    - BFS and shortest path to nodes in terms of edge weights
    
- Kruskal's Minimum Spanning Tree Algorithm
    - The strategy and algorithm, how to find next edge to add to solution, use of sorting or heap
    - The need and use of set operations Union and Find in Kruskal's
    - The Find/Union data structure: the basics, union-by-rank, path-compression
    - Time complexity for Kruskal's with Find/Union and its optimizations
    
- DFS
    - The strategy and algorithm, including use of recursion, marking nodes, levels of the tree, non-tree edges, discovery/finish times, time-complexity, recognizing back-edges
    - No questions on version that uses stack, only recursive approach
    - Using DFS-sweep() to process all nodes, find connected components, etc.
    - For undirected graphs:  back-edges mean cycles; only tree and back-edges
    - For directed graphs: only back-edges mean cycles; also cross and descendant edges (know these don't indicate cycles, but you don't know how to distinguish between cross and descendent)
    - Using DFS and/or BFS for problems: is graph acyclic, finding connected components, other relatively simple problems done in lecture etc.
    
- Topological Sorting and SCCs in a Digraph
    - What the problem is Topological Sorting about, how its used to modify dependencies
    - Solution using DFS based on finish times
    - Strongly connected components: what they are, how we use DFS and a graph's transpose to find these, relation to topological sorting
    
- Dijkstra's SP and Prim's MST algorithm
    - For both, the overall strategy, use of priority-queue, update connections to nodes that might be selected next, differences between the two
    - Why decrease-key operation affects our time-complexity
    - How to use indirect heaps to make decrease-key more efficient
    - Overall time-complexity for Dijkstra's and Prim's
    - Possibly questions on proof strategy for these, including exchange argument approach    
    

Topics that will *not* be covered on the quiz include:
-------------------------------------------------
- Questions based on the Advanced HW assignments or the programming assignments

- Why Dijkstra's and Prim's are greedy algorithms
- You don't know how to distinguish between cross and descendent edges in DFS
