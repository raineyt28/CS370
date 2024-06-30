# CS370

Project Description

This project involves creating a reinforcement learning agent to solve a maze using deep Q-learning. The agent is designed to learn the optimal path to a goal (the treasure) within a maze environment by balancing exploration and exploitation. The project leverages neural networks to predict Q-values, which guide the agent's actions.
Work Done on the Project
Given Code

GameExperience.py: This file includes the GameExperience class, which handles the storage of episodes (states,           actions, rewards, and next states) for experience replay. This class allows the agent to learn from past             experiences by sampling and training on stored episodes.
TreasureMaze.py: This file includes the TreasureMaze class, representing the maze environment. The class defines         the maze structure, the agent's movements, rewards, and game status (win/lose conditions).

Created Code

   Q-Training Algorithm Implementation:
        Implemented the qtrain function to train the neural network using the Q-learning algorithm.
        Utilized the epsilon-greedy strategy to balance exploration and exploitation.
        Trained the model using experience replay and updated Q-values.
        Implemented logic to track win rates and adjust exploration rates.
        Designed the function to ensure efficient learning and stopping criteria based on performance.

Connecting Learning to the Larger Field of Computer Science
What Do Computer Scientists Do and Why Does It Matter?

Computer scientists solve complex problems by designing algorithms, developing software, and creating systems that enhance various aspects of life and industry. Their work matters because it drives innovation, improves efficiency, and creates solutions that address real-world challenges. From developing new technologies to improving existing ones, computer scientists play a critical role in advancing knowledge and capability in numerous fields, including healthcare, finance, education, and entertainment.
How Do I Approach a Problem as a Computer Scientist?

As a computer scientist, approaching a problem involves several key steps:

Understanding the Problem: Thoroughly analyzing the problem to understand its requirements, constraints, and             desired outcomes.
    Planning and Designing: Developing a strategic plan and designing algorithms or models that address the problem      efficiently.
    Implementation: Writing code and building systems to implement the designed solution.
    Testing and Debugging: Ensuring the solution works correctly through rigorous testing and debugging.
    Optimization: Refining the solution to improve performance, scalability, and efficiency.
    Evaluation: Continuously evaluating the solution to ensure it meets the desired objectives and making                adjustments as necessary.

Ethical Responsibilities to the End User and the Organization

As a computer scientist, ethical responsibilities include:

    Ensuring Privacy and Security: Protecting user data and ensuring secure systems to prevent unauthorized access       and data breaches.
    Fairness and Non-Discrimination: Designing systems that are fair and unbiased, avoiding discrimination based on       race, gender, age, or other factors.
    Transparency and Accountability: Being transparent about how systems work and taking responsibility for their        impact on users and society.
    Sustainability: Considering the environmental impact of technologies and striving to create sustainable and eco-     friendly solutions.
    User-Centric Design: Prioritizing the needs and well-being of users, ensuring systems are user-friendly,             accessible, and do not cause harm.
