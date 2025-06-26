# cs370-pirate-dql-maze-solver
Pirate AI maze solver using Deep Q-Learning (CS370 Project 2). 

Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?
For this project, my professor provided us with the finished python modules for the maze enviornment and the game experience. I was provided the basic code architecture for the ipynb file, and I had to code the q training algorithm.

This required desiging:
- ε-greedy exploration (ε=0.1 decaying to 0.05)
- Programmed reward structure: +1.0 (treasure), -0.75 (walls), -0.04/step
- Trained agent using Bellman equation and batch updates
I then conducted an analysis of the performanc of the AI agent against the performance of a human, and wrote this analysis in a design defense.

Connect your learning from throughout this course to the larger field of computer science:
- What do computer scientists do and why does it matter
  Computer scientists solve and automate complex problems. In this project I solved the problem of maze navigation by an artificially intelligent agent.
- How do I approach a problem as a computer scientist?
  I started with q learning and then added neural networks (dqn). I then adjusted hyperparameters based on performance.
- What are my ethical responsibilities to the end user and the organization?
  Ethical responsibility to the end user is to design an AI agent with the expected and promised utility functions. To organization, responsibiility is to document process, suceed in goal, and limit costs. To society, ressponsubiility is to avoid misuse and avoid accidental doomsday scenerios.
