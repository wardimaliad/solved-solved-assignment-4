Download Link: https://assignmentchef.com/product/solved-solved-assignment-4
<br>
Program A: Number Counting (counting.c):John has some files with a lot of numbers in them. He often likes to do super complicated mathematical analysis on these numbers, so he really likes these files. However, he’s realized one downside of working with such large files of numbers: it takes a long time to read what is potentially pages full of numbers, many of which are duplicates that are not easy to count by eye. Luckily, there is at least some level of organization to these numbers: they are sorted in order from smallest to largest. Also, there are a lot of duplicate numbers (each number with duplicates is together with all of its other duplicates, since the list is sorted).Your goal is to condense these series of duplicate values into a more readable list. They should be ouput in the format ” v X c “, where v is the number and c is the number of times it occurs. For example, if the file contains the numbers:1 1 2 3 4 4 4 4 5 5 7 then for these numbers, you should output to standard output:1×2 2×1 3×1 4×4 5×2 7×1The filename you should read from is “counting.txt” (remember, you will need to create this file and put numbers in it for testing on your own computer). The first number in this file will be a positive integer, N , the number of numbers to follow in that file. N numbers will follow in the file: the sorted list of numbers you should process. As always, don’t forget to make some of your own test inputs, also.Sample Run (run using “counting.txt” contents below):1×2 2×1 3×1 4×4 5×2 7×1Contents of this example “counting.txt”:111 1 2 3 4 4 4 4 5 5 7

Program B: Point Plotter (plotter.c):In math, its often useful to visualize points on a graph (with an X and Y axis). Its also possible to take this even further, graphing lines, equations, etc, but we’ll stick with just a point for now to keep things easy. Since we don’t have any complicated drawing interfaces, let stick to drawing with ASCII character pictures.Given the X and Y coordinates of a single point, plot that point. X and Y will both be integers between 1 and 9 (inclusive). Your graph should have each axis of size 9. See the samples for clarification of what this should look like.For easier modification, you should use constants for the width (X axis size) and height (Yaxis size):#define WIDTH 9#define HEIGHT 9Sample Run (User input in bold and italics):3 4++++++++++9 | | | | | | | | | |++++++++++8 | | | | | | | | | |++++++++++7 | | | | | | | | | |++++++++++6 | | | | | | | | | |++++++++++5 | | | | | | | | | |++++++++++4 | | | X | | | | | | |++++++++++3 | | | | | | | | | |++++++++++2 | | | | | | | | | |++++++++++1 | | | | | | | | | |++++++++++1 2 3 4 5 6 7 8 9Note: yes I know the axis lines are usually drawn on the values, not between them. It would be a relatively minor change to do that (there would be no complication in the code, just a modification of exactly which characters it outputs where). But as I felt this would be a bit clearer visually, I chose this format instead. This is what you should submit, but after that, I do challenge you to try it the other way, too.

Program C: Savings (savings.c):You’re interested in starting a savings account, but you want to know how much money it will make over time. Each month, you will add a constant amount of money, and the account will earn interest.Output the total amount the account will have at the end of every year to standard output. In addition, for more detailed reference, output the monthly balance of the account for every month to the file “savings.txt”.Sample Run (User input in bold and italics):Enter your initial amount.10000Enter your monthly deposit.100Enter the annual interest rate (compounded monthly).6.5Enter the number of years to calculate.31 $11906.122 $13939.903 $16109.88Contents of “savings.txt” after running this sample:1 $10154.172 $10309.173 $10465.014 $10621.705 $10779.236 $10937.627 $11096.868 $11256.979 $11417.9510 $11579.7911 $11742.5212 $11906.1213 $12070.6114 $12236.0015 $12402.2716 $12569.4517 $12737.5418 $12906.5319 $13076.4420 $13247.2721 $13419.0322 $13591.7223 $13765.3424 $13939.9025 $14115.4126 $14291.8727 $14469.2828 $14647.6629 $14827.0030 $15007.3131 $15188.6032 $15370.8733 $15554.1334 $15738.3835 $15923.6336 $16109.88Disclaimer: this is an oversimplification of real life savings. Please do not use this description or program as reference for any reallife financial decisions.Deliverables:Please submit three separate .c files for your solutions to these problems via WebCourses bythe designated due date:Program A: counting.cProgram B: plotter.cProgram C: savings.c