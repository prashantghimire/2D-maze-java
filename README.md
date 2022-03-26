2D-Maze-Recursive Solution using Java
=================

- This program will recursively find a path from a starting point 'S' to an end point 'G' of a maze specified in a text
  file.
- The solution is written to a text file.

Example:

Input File:

<pre>
XXXXXXXXXXX
XX<span style="color: red">S</span>XXXXX XX
XX XXXXX XX
XX XXXXX XX
XX XXXXX XX
XX       XX
XX   XXX XX
XX       XX
XX  X XXXXX
XX  X XXXXX
XX XX XX XX
XX XX XX XX
XX X<span style="color: green">G</span>XXXXXX
XX   XXXXXX
XXXXXXXXXXX
</pre>

Output file:

<pre>
XXXXXXXXXXX
XX<span style="color:red">S</span>XXXXX XX
XX.XXXXX XX
XX.XXXXX XX
XX.XXXXX XX
XX.......XX
XX   XXX.XX
XX ......XX
XX .X XXXXX
XX..X XXXXX
XX.XX XX XX
XX.XX XX XX
XX.X<span style="color: green">G</span>XXXXXX
XX...XXXXXX
XXXXXXXXXXX
</pre>
