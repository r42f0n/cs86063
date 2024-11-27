java c
Formal Methods in AI and Robotics: Assignment#4
Objective: Learn and implement planning algorithms for deterministic systems with reachability and invariance properties.
• Please submit your answers as a PDF file and python files.
For this homework, you will have to use the code snippets provided on Canvas in Files→ FMlib→ Python project.
Problem 1
(50 points) The code snippet ‘TransSysPlanner.py’ is the planner that you will be implementing. This code consists of 2 functions that you will have to write.
• The first function ‘Attr’ takes the input deterministic transition system along with the set of final states to output the winning states Attr(F) and a deterministic winning policy π. Implement the controllable attractor computation for this function.
• The second function ‘AttrUC’ requires you to implement the uncontrollable attractor AttrUC (F). After implementing ‘AttrUC’ function, you can implement the ‘SolverSafety’ that computes the winning region for a set F with respect to “always stay in F”. This function should call ‘AttrUC’ function.
Problem 2
(30 points) Usi代 写Formal Methods in AI and Robotics: Assignment#4Python
代做程序编程语言ng the code snippet ‘deter plan ex.py’ validate the above functions written by you.
• Use the code snippet to generate a random graph and its transition system. Consider a random subset of states as F1 and compute the controllable attractors for it. Similarly, consider a random subset of states as F2 and compute the uncontrollable attractors for it.
• Consider a random generated subset fo states as F3 and compute the safety strategy to stay in F3 and the winning region for the safety property “Always in F3’, ’G in(F3).
Problem 3
(20 points) Given two sets F1 and F2, let Attruc(F1) and Attruc(F2) be the two uncontrollable attractors of F1 and F2, respectively, and Attruc(F1 ∪ F2) be the uncontrollable attractors of F1 ∪ F2. determine if Attruc(F1) ∪ Attruc(F2) = Attruc(F1 ∪ F2)? If not, is it
• Attruc(F1) ∪ Attruc(F2) ⊇ Attruc(F1 ∪ F2), or
• Attruc(F1) ∪ Attruc(F2) ⊆ Attruc(F1 ∪ F2).
Give your reasoning (ideally a proof). An answer without any reasoning will receive 0 with probability 1/3 and 1 point with probability 2/3.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
