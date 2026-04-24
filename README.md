# CS 370 Portfolio Submission: Pirate Intelligent Agent

## Project Overview

For this project, I worked on a pirate intelligent agent that uses reinforcement learning and neural networks to navigate a maze and find treasure. The project was based on a treasure hunt game environment where the agent had to learn the best path through trial and error. The goal was to apply deep Q-learning so the pirate could improve its decisions over repeated episodes instead of following a fixed, hard-coded path.

The starter code provided the overall game structure, including the maze environment and supporting classes such as the experience memory used during training. I was given the foundation for how the maze worked, how states and rewards were represented, and how the agent could interact with the environment. The main code I created myself was the deep Q-learning training logic inside the `qtrain()` function. This included selecting actions, storing experiences, using exploration versus exploitation, training the neural network from experience batches, tracking win rates, and stopping training once the agent reached the target completion rate.

## Connection to Computer Science

Computer scientists solve problems by designing systems that process information, make decisions, and produce useful outcomes. This matters because computer science is not only about writing code; it is about building reliable tools that can improve how people work, learn, communicate, and solve complex problems. In this project, reinforcement learning showed how a computer system can improve through feedback instead of being directly programmed for every possible situation. That idea connects to many real-world applications, such as robotics, route planning, recommendation systems, game AI, and automation.

My approach to this problem as a computer scientist was to first understand the environment, then identify what the agent needed to learn. I had to think about the maze as a set of states, actions, rewards, and outcomes. Instead of only focusing on whether the code ran, I had to evaluate whether the agent was actually learning. That meant paying attention to training progress, win rate, loss values, and whether the agent could consistently find the treasure. This project helped me understand the importance of breaking a larger problem into smaller parts, testing each part, and using results to improve the solution.

## Ethical Responsibilities

My ethical responsibilities to the end user and the organization include building systems that are reliable, transparent, and safe to use. Even though this project was a game-based example, the same ideas apply to real AI systems. If an intelligent agent is used in a real-world setting, poor training data, bad reward design, or lack of testing could cause the system to make harmful or unfair decisions. Developers have a responsibility to test AI systems carefully and explain their limitations honestly.

For an organization, ethical responsibility also means not overstating what an AI system can do. A model that performs well in a controlled environment may not perform the same way in a real-world environment with changing conditions. For the end user, the system should behave predictably, protect user data when applicable, and include human oversight when decisions have real consequences. This project reinforced that responsible AI development requires both technical skill and careful judgment.

## AI Use Acknowledgment

I used ChatGPT to help organize and revise the written reflection for this README. The project code and learning concepts are based on my CS 370 coursework and Project Two work.
