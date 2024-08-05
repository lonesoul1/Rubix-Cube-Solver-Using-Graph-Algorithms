Terminology
Let’s start with some standard Rubik’s cube terminologies. These are common in the Rubik’s cube world and will come in handy throughout the project.

Cubie: One of the 26 mini-cubes that make up the whole cube. Each cubie can have either one, two, or three sides coloured.
Center Cubie: Cubies with only one side coloured and are present at the center of each side of the Rubik’s Cube. There are a total of 6 Center Cubbies. It is important to note that all center cubbies are statically positioned. No matter how you rotate/twist the Rubik’s Cube, the center cubbies will not change their positions relative to each other.
Edge Cubie: Cubbies which are coloured on two of their sides. There are a total of 12 edge cubbies. Eg: Red-Yellow Edge
Corner Cubie: Cubbies with three of their sides coloured. There are a total of 8 corner cubbies. Eg: White-Red-Blue Corner Cubie
Face: A side of a Rubik’s Cube made up of 9 cubies: 1 center, 4 edges, and 4 corners. There are six faces: front, back, left, right, up, and down.
Operations and Notation
After understanding all the terminologies, let’s get started with some standard operations and their notations that can be performed on a Rubik’s Cube.

To understand the operations, imagine holding a Rubik’s Cube in your hand (or actually holding one), with a White face facing you and a Red face facing up.

Since there are 6 sides/faces of a Rubik’s cube, you can perform 6 rotations by rotating any one of the 6 sides clockwise.



Now if you have correctly held the cube, we can label the faces as follows:

The face facing you would be Front (or F), in your case, it should be White.
The face facing up would be Up (or U), in your case, it should be Red.
The face facing down would be Down (or D), in your case, it could be Orange.
The face facing away from you, that is, the face opposite to the White face is Back (or B), in your case it could be Yellow.
The faces left and right to the White face are Left (or L) and Right (or R), in your case it could be Blue and Green respectively.
 
Now Look at the following Rotations



The above image shows twisting the Up (Red, in your case) side clockwise once.

 

We can rotate any of the faces clockwise once, thus, giving us 6 unique rotations. We denote these rotations by the first letter of the face, that is, F, U, L, D, R, B.

 

Notation	Meaning
F	Clockwise rotation of Front face
R	Clockwise rotation of Right face
U	Clockwise rotation of Up face
B	Clockwise rotation of Back face
L	Clockwise rotation of Left face
D	Clockwise rotation of Down face

 

Prime Rotations: We can rotate any of the 6 faces counter-clockwise once, thus, giving us 6 more rotations, denoted by the first letter of the Face and an apostrophe. These are F’, U’, L’, D’, R’, B’.
Double Rotation: Rotating a face clockwise (or anti-clockwise) will give another 6 rotations, denoted by a face letter followed by the number 2. These are F2, U2, L2, D2, R2, B2. 
Note that rotating the face clockwise twice and rotating the face anti-clockwise twice are the same thing. It'll result in the same type of face. So, without loss of generality, we're considering the double rotation operation as rotating the face twice clockwise.


 

This gives us a list of 18 possible moves we can make on a Rubik’s Cube:
 

F, F’, F2,

U, U’, U2,

L, L’, L2,

D, D’, D2,

R, R’, R2,

B, B’, B2


 

For trying out the simulation of rotations, you can go to:

https://ruwix.com/the-rubiks-cube/notation/advanced/

 

Planar Representation of a Rubik’s Cube
It’s difficult to visualize a 3D object (like a Rubik’s Cube) on a 2D surface like a monitor screen or paper. Therefore, we try to represent the Rubik’s Cube in a planar form as follows:



If you keep the Rubik’s Cube with White facing up and Red face facing you and then try to imagine as if the Rubik’s Cube is unfolding itself, an image similar to the above will be formed.

 

Look at the following example.


 




 

This planar representation is particularly helpful when we will try to print the Rubik’s Cube in our programs.

