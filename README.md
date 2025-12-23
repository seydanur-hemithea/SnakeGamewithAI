# SnakeGamewithAI
“A classic Snake game re-staged with reinforcement learning — rival snake learns its choreography live.”


Snake Game with Reinforcement Learning
🎮 Overview
This project is a redesigned version of the classic Snake game, enhanced with a rival snake powered by Reinforcement Learning (RL).
While the player controls their snake in the traditional way, the rival snake learns from its environment, adapting its moves step by step.
✨ Features
- Classic gameplay: Move, eat, grow — the timeless Snake mechanics.
- Rival AI snake: Learns through RL, making decisions based on states, actions, and rewards.
- Dynamic competition: The rival snake improves over time, sometimes even outperforming the player.
- Windows Forms UI: Simple, clear interface with scoreboards and labels.
🧠 Reinforcement Learning Logic
The rival snake follows a learning loop:
- State → Position of the snake head relative to the food.
- Action → Choose direction (up, down, left, right).
- Reward → Positive if closer to food, negative if farther.
- Update → Q-table is updated, improving future decisions.
This cycle allows the rival snake to gradually refine its strategy, turning each game into a rehearsal where it learns its choreography.
🚀 How to Run
- Clone or download this repository.
- Navigate to bin/Release folder.
- Run WindowsFormsApp6.exe.
- Enjoy the duel between player and rival snake!
📦 Distribution
- Share the entire bin/Release folder (including .exe and .dll files).
- The game runs on Windows without additional setup.
📜 License
This project is licensed under the MIT License — feel free to use, modify, and share, with attribution.
🎭 Credits
Developed by Şeyda, blending technical precision with dramaturgical storytelling.
Every move of the snake is not just logic, but part of a performance.
