=> Que 1 of the Project is Implemented.

=> Each Folder is Named according to the respective Question and Contains the Controller File, Test Bench, Simulation and Schematic for the problem.

=> A Single ALU is used for all the 8 problems.

=> Output 'X' represent Don't Care.

=> In output "No Result" = "00000000".

=> Output Starts from 0 ns.

=> In problem  1(f) term "remaining clock periods" has been interpreted as all the clock periods after 6th i.e. for 7,8,9,10,11,12,13,14,15.... clock periods output is "No Result".

=> In 1(g) the similar interpretation of printing the "Don't Care" Condition after the first 8 cycles/clock periods.

=> The "choose" line in ALU is for making the output to be "No Result".

=> In 1(b), the interpreted and implemented output is like = A*B*ABA*B*AB.... here A* represents inv(A) or A bar.

=> Time Period Of the Clock: 100 ns (For all the sub problems).

=> The Chosen Values:
	A = "01011001"         (Integer Value = 89)
	B = "01100111"         (Integer Value = 103)

=> Result of Operations:

	Sum = "0 11000000"        (Carry = 0)

	Diff(A-B) = "1 00001110"  (Carry = 1 as the difference is negative)

	OR = "01111111"

	AND = "01000001"

	NAND= "10111110"

	XOR = "00111110"

	INV(A) = "10100110"

	INV(B) = "10011000"


