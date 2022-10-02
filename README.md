# Tic tac toe endgame

For this assignment, we will be using the Tic-Tac-Toe Endgame dataset located in the Irvine’s Machine Learning Repository located at:
https://archive.ics.uci.edu/ml/index.php<br>
https://archive.ics.uci.edu/ml/datasets/Tic-Tac-Toe+Endgame <br>
<br>
This tic-tac-toe data file under the Tic-Tac-Toe Endgame folder encodes the complete set of 958 board configurations at the end of all possible tic-tac-toe games, where X is assumed to have played first. The target concept is a win for X. Namely, the classification is positive if X has one of eight possible ways to create a “three-in-a-row”; otherwise, the classification is negative.
<br>
There are nine attributes, each of which represents one of the nine possible squares of the tic-tac-toe-board. These attributes are (in the order they appear in tic-tac-toe data):<br>
1.	top-left-square<br>
2.	top-middle-square<br>
3.	top-right-square<br>
4.	middle-left-square<br>
5.	middle-middle-square<br>
6.	middle-right-square<br>
7.	bottom-left-square<br>
8.	bottom-middle-square<br>
9.	bottom-right-square<br>

Each attribute can take on one of three values:<br>
1.	x	Player X has claimed that square.<br>
2.	o	Player O has claimed that square.<br>
3.	b	No player has claimed that square. It is blank.<br>

You are tasked with implementing the ID3 algorithm to create a decision tree to distinguish between the winning and losing Tic-Tac-Toe boards for the player X. Your program must additionally output the resulting decision tree in some meaningful and easy to discern way so that it can be seen and evaluated. This does not have to be graphical, but it must be understandable.
