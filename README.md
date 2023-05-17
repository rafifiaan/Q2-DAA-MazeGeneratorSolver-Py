# **Quiz2-DAA-H-MazeGeneratorSolver**
Repository for Design & Analysis of Algorithms Secondary Quiz.

## **Group Members**
| Name                              | Student ID | Class  |
| ----------------------------------|------------|:------:|
| Akmal Ariq Romadhon               | 5025211046 | DAA G  |
| Sandyatama Fransisna Nugraha      | 5025211196 | DAA H  | 
| Rafi Aliefian Putra Ramadhani     | 5025211234 | DAA H  |

# **Question**
<p style='text-align: justify;'>You are free to make any computer program for your group project (e.g., game, start-up,
etc.). However, you have to implement any algorithms (e.g., DFS, BFS, DAG, Prim-Jarnik,
Kruskal, etc.) that have been taught in our lectures. For instance, a game that determines
the closest distance, a minesweeper game or a web application that examines the
minimum distance for sending the goods from one point to another point.</p>


# **Answer**
The following is the result of our work based on the questions above.

## **Main Topic Problem**
<p style='text-align: justify;'>Using Prim's (Minimum Spanning Trees) and Depth First Search algorithms to create a maze generator program, and then solving it using the Depth First Search Algorithm.</p>


## **Maze Problem Preview**
Here is the visualization for Maze Problem:

![Maze](https://cdn.discordapp.com/attachments/1083730715113426985/1108425060206784523/image.png)

## **Maze Description**
<p style='text-align: justify;'>Maze is a puzzle-like structure composed of interconnected passages or paths that challenges navigational skills. It serves various purposes such as entertainment, education, and research. Mazes can be created in different shapes and sizes and can be two-dimensional or three-dimensional. The objective is usually to find a path from a starting point to a finishing point while navigating through complex twists and turns, which can include obstacles like dead ends, false paths, and traps. Mazes have a long history and have been used for spiritual, entertainment, and educational purposes. Today, they are commonly used in theme parks and video games. Mazes can be created using various methods and require careful planning and consideration of factors such as the purpose, level of difficulty, and target audience.


## **Implementation**
The following is a brief explanation of the algorithm used. To see a more complete explanation, you can visit [this page](https://docs.google.com/document/d/1rBJiJ0srbW19zWIxvrYbQuQJzs4kif04ugv55M70GMg/edit?usp=sharing) or via the following link: <br>https://its.id/m/DAA-Quiz-Report
<style>body {text-align: justify}</style>

- **Maze Generator (Prim's MST and DFS Algorithm)** <br>
<p style='text-align: justify;'> To create a maze, combine Prim's algorithm and DFS. Prim's algorithm starts with a grid where all cells are walls. It randomly selects a starting cell, adds it to visited cells, and adds neighboring cells to the unvisited list. The algorithm selects the cell with the minimum weight, removes it from the unvisited list, and marks walls as passages. This continues until all cells are visited, resulting in a connected maze. DFS adds complexity to the generated maze. It starts at a random cell and explores neighboring cells recursively. It removes walls, creates passages, and continues exploring until reaching a dead end. The algorithm backtracks and explores other unvisited neighboring cells. DFS ensures all cells are interconnected, creating a challenging maze. Combining Prim's algorithm and DFS generates diverse mazes in Python. </p>


- **Maze Solver (Depth First Search Algorithm)** <br>
<p style='text-align: justify;'>DFS is a widely used algorithm for maze problem solving. It explores the maze by going as deep as possible along each branch before backtracking. To apply DFS to a maze, we start at the entrance and mark it as visited. Then, we recursively explore neighboring cells that haven't been visited. If we encounter a dead end, we backtrack to the previous cell and explore other paths. DFS uses a stack to keep track of the current path and allows us to search for alternative routes. Although DFS doesn't guarantee the shortest path, it efficiently solves mazes by systematically exploring interconnected cells until finding a path from entrance to exit. </p>

## **Preview** 
- **Home**

![Home](https://media.discordapp.net/attachments/1083730715113426985/1108432085829554186/image.png?width=646&height=701)

- **Maze-Making Process**

![Process](https://media.discordapp.net/attachments/1083730715113426985/1108432198324981882/image.png?width=646&height=701)

- **Solved with DFS**

![Solved](https://media.discordapp.net/attachments/1083730715113426985/1108432271310073997/image.png?width=642&height=701)


# **Contribution List**
The following is the division of tasks and the percentage contribution of each member in working on Quiz 2.
## **Percentage**
| Name                              | Student ID | Work Contribution  |
| ----------------------------------|:----------:|:------------------:|
| Akmal Ariq Romadhon               | 5025211046 |       33.33%       | 
| Sandyatama Fransisna Nugraha      | 5025211196 |       33.33%       | 
| Rafi Aliefian Putra Ramadhani     | 5025211234 |       33.33%       |

## **Work Structural**
**Akmal Ariq Romadhon:** <br>
- Make problem Analysis 
- Compiling reports 
- Help develop generator program ideas (structural and completion solutions)
- Edit and help complete the README.md

**Sandyatama Fransisna Nugraha:**
- Create Design Problems
- Develop a conclusion, concept, or idea
- Completing the program (main)
- Edit and help compile README.md

**Rafi Aliefian Putra Ramadhani:**
- Arranging Implementation Problems
- Making Conclusions, finish reports
- Develop the program structure and complete the generator program
- Compile and complete README.md.
