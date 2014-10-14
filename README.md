A tree diagram (SVG) generation tool in JavaScript
==================================================

This tool creates SVG (Standard Vector Graphics) files to illustrate information
stored in a basic tree data structure.

![Simple tree image](doc/simple_tree.png)

Here I define *tree* as an ordered graph without loops where every node has zero
or one outgoing edges (i.e. to a 'parent' node in the same tree).

It's a very common structure in computing and will be familiar to most as the
structure of folders on a personal computer (as seen in the 'Unix' example).
It's also the structure of classes in a single-inheritance object oriented
programming language (as seen in the 'Java' example).

Lots of real world data can be formatted this way too. For instance an 'org
chart' of the hierarchy of an organization (because everyone has a boss, apart
from the boss of the company).

See the [Wikipedia article](http://en.wikipedia.org/wiki/Tree_%28data_structure%29)
on trees


Method
------

Relative values are assigned for the widths of nodes and the spaces between sibling nodes (nodes that share the same parent) and cousin nodes (nodes that are the same distance from their roots but don't share the same parent).


Customization
-------------

Each graph can be customized 


Heading
=======

Sub-heading
-----------
