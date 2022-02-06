# Dice Roller
A dice roller tool for use with TTRPGs, intended to speed up GM calculations but also useful for players!

Output includes the dice rolled, the individual dice values, the sum of each kind of dice, the modifier (if present), and the total sum of all dice rolled and the modifier.

# Instructions:
Enter your desired dice quantity and number of sides, followed by a modifier if desired, in the format: QUANTITYdSIDES+/-MODIFIER

Use 'q' or 'quit' to exit
  
# Examples:
To roll two twenty-sided dice, enter the following: 2d20

Output:

    Dice Rolled: 2d20

    Result(s):
      2d20 = [15, 9]; Sum = 24

    Total: 24

To roll three six-sided dice and two four-sided dice, enter the following: 3d6+2d4

Output:

    Dice Rolled: 3d6+2d4

    Result(s):
      3d6 = [4, 3, 5]; Sum = 12
      2d4 = [3, 1]; Sum = 4

    Total: 16

To roll two four-sided dice with a '+3' modifier, enter the following: 2d4+3

Output:

    Dice Rolled: 2d4+3

    Result(s):
      2d4 = [4, 3]; Sum = 7
      Modifier = ['+3']

    Total: 10

To roll one twenty-sided dice with a '-1' modifier, enter the following: 1d20-1

Output:

    Dice Rolled: 1d20-1

    Result(s):
      1d20 = [11]; Sum = 11
      Modifier = ['-1']

    Total: 10