# 🚕 Performance Comparison of RL Methods on Taxi-v3

This project presents a comprehensive comparison of multiple reinforcement learning (RL) algorithms applied to the classic **Taxi-v3** environment from OpenAI Gym. It includes both foundational and advanced methods, aiming to analyze and compare their performance under similar conditions.

## 📌 Project Overview

The goal is to evaluate and compare the effectiveness of various RL algorithms in solving the Taxi-v3 problem. This environment involves a taxi agent navigating a grid to pick up and drop off passengers at specific locations with the least number of steps and penalties.

### Algorithms Implemented:

- **Policy Iteration**  
- **Q-Learning**  
- **Function Approximation using Linear SARSA** *(implemented manually)*  
- **Policy Gradient Methods** *(implemented manually)*  

Special focus is placed on the implementation and tuning of **Function Approximation** and **Policy Gradient** techniques to explore potential performance improvements over traditional tabular approaches.

## 🧪 Environment: Taxi-v3

- Discrete 5x5 grid world
- Fixed pickup/drop-off locations
- Stochastic transitions
- Rewards for successful delivery and penalties for illegal actions

## 📊 Performance Evaluation

Each method was trained and evaluated over multiple episodes. Metrics used for comparison include:

- Average rewards
- Episode lengths
- Convergence speed
- Policy stability


