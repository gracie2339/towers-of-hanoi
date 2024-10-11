This was a guided project from Codecademy.com.

Here we implemented a terminal game version of Towers of Hanoi, consisting of while loops, for loops, and the data structure: Stacks.

SAMPLE GAME:

Let's play Towers of Hanoi!!

How many disks do you want to play with?
4

The fastest you can solve this game is in 15 moves



...Current Stacks...
Left Stack: [4, 3, 2, 1]
Middle Stack: []
Right Stack: []

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
L

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
M



...Current Stacks...
Left Stack: [4, 3, 2]
Middle Stack: [1]
Right Stack: []

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
L

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
R



...Current Stacks...
Left Stack: [4, 3]
Middle Stack: [1]
Right Stack: [2]

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
M

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
R



...Current Stacks...
Left Stack: [4, 3]
Middle Stack: []
Right Stack: [2, 1]

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
L

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
M



...Current Stacks...
Left Stack: [4]
Middle Stack: [3]
Right Stack: [2, 1]

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
R

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
L



...Current Stacks...
Left Stack: [4, 1]
Middle Stack: [3]
Right Stack: [2]

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
R

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
M



...Current Stacks...
Left Stack: [4, 1]
Middle Stack: [3, 2]
Right Stack: []

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
L

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
M



...Current Stacks...
Left Stack: [4]
Middle Stack: [3, 2, 1]
Right Stack: []

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
L

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
R



...Current Stacks...
Left Stack: []
Middle Stack: [3, 2, 1]
Right Stack: [4]

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
M

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
R



...Current Stacks...
Left Stack: []
Middle Stack: [3, 2]
Right Stack: [4, 1]

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
M

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
L



...Current Stacks...
Left Stack: [2]
Middle Stack: [3]
Right Stack: [4, 1]

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
R

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
L



...Current Stacks...
Left Stack: [2, 1]
Middle Stack: [3]
Right Stack: [4]

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
M

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
R



...Current Stacks...
Left Stack: [2, 1]
Middle Stack: []
Right Stack: [4, 3]

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
L

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
M



...Current Stacks...
Left Stack: [2]
Middle Stack: [1]
Right Stack: [4, 3]

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
L

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
R



...Current Stacks...
Left Stack: []
Middle Stack: [1]
Right Stack: [4, 3, 2]

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
M

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
R


You completed the game in 15, and the optimal number of moves is 15