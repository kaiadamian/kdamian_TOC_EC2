# kdamian_TOC_EC
1. What was the extra work? <br />
For this extra credit, I added on to the Project02 requirements by not only building a tree of configurations but also tracing back to find the accepting path. I did this by making a new function, tracing_tree(), which creates a List[List[str]] of previous configurations. I use this function to trace backwards through the tree of configurations and find the accepting path of configurations, if any. 

2. Why did you choose it (i.e. in what area did you feel deficient and how did this work help improve your understanding) You can point to specific homeworks or problem types on exams. <br />
I chose this extra credit because, for me, tracing NTMs by using configurations was really hard. I would always get confused what state I am supposed to be in, what symbol should be replaced, and where the head should be. In addition, I was also super confused about how the accepting path was actually formed, as I was confused about the depth-first vs. breadth-first search. <br />
By writing this program, I was able to test myself on tracing TMs until I found an accepting configuration, which really helped me practice TM configurations to study for the exam. It also helped me to understand the depth-first search that occurs when going down a single path (of acceptance).

3. What files are what? <br />
Aside from this README, I have the files below: <br />
path_to_acc.py: program that traces all the paths that an NTM takes, and finds and prints its accepting path, if any <br />
output.txt: example of output of program. <br />
check_equal_abs.csv: test NTM file that checks if an input string has equal as and bs. <br />
