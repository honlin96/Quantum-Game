--------------Introduction----------------
Qubit Tic Tac Toe is a quantum game designed to develop quantum mechanics intuition. 
We quantize tic tac toe by replacing the marking with qubit.
We also introduce unitary moves and measurement. 
Player wins by forming a straight line with classical marking. 

--------------Moves ---------------
1. Prepare a qubit/ Place a quantum marking
Players can prepare a pure state qubit in an empty board.
Player 1's quantum marking is |O>, while player 2's quantum marking is |X>.

2. Hadamard gate/Create superposition
Players can use hadamard gate on any qubit. 

3. Pauli X gate
Players can use X gate on any qubit.

4. Measurement
Players can perform measurement Z basis on any qubit. 
The qubit will collapse according to the probability amplitude

------------ Special Rule---------------
If the game has not ended after Round 10, all the qubits will collapse to classical bits. 
