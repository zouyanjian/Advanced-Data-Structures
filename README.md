# Data-Structures-2
Implementations of some exotic data structures.

I am currently taking a "Data Structures 2" course at the university.<br/>
We will have a bunch of homeworks and a project. So the purpose of this repo is to store them. <br/>

I have not decided if I am going to use Java ot C++.<br/>
I feel more comfortable with Java, but I desire to learn C++ and I believe implementing all these data structures will be a very good experience. SO, I'm starting with C++ and we'll see how it goes...


<ul>
<li>
Treap - this is a hybrid between Binary Search Tree and Heap. Every node holds some key and priority value, which is randomly generated number. The treap arranges its elements like BST by their key value and like Heap by the priority. The idea is to keep it somehow balanced.
<br/>http://en.wikipedia.org/wiki/Treap
</li>
<li>
Day-Stout-Warren algorithm - This algorithm is used to make from normal Binary Tree -> complete Binary Tree.<br/>
<a href="http://en.wikipedia.org/wiki/Day%E2%80%93Stout%E2%80%93Warren_algorithm">http://en.wikipedia.org/wiki/Day-Stout-Warren_algorithm</a>
</li>
<li>
AVL Tree - This is a balanced binary tree. I am given an interface and some tests and I must implement insert(), delete() and find() operations. <br/>
<a href="http://en.wikipedia.org/wiki/AVL_tree">http://en.wikipedia.org/wiki/AVL_tree</a><br/>
I found this site to be very usefull: <a href="https://www.cs.usfca.edu/~galles/visualization/AVLtree.html">check it out</a>
</li>
<li>
Splay Tree - This is a binary tree, that keeps as root the last element, operated with (last inserted, last searched for, parent of deleted). The idea is that like in the cache - if you are searching for something - there's a probability you'll search for it again!<br/>
http://en.wikipedia.org/wiki/Splay_tree
</li>
<li>
Skew Heap - Heap-ordered binary tree or self-adjusting version of leftist heap.<br/>
http://en.wikipedia.org/wiki/Skew_heap
</li>
<li>
HashMap - I think it's needless to say what this is.
</li>
</ul>
