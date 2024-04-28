# Automated-Stock-Trading-using-Reinforcement-Learning
This repository contains the implementation of an advanced stock trading system using reinforcement learning (RL). The system employs several RL algorithms, including Deep Q-Networks (DQN), Advantage Actor-Critic (A2C), and Twin Delayed Deep Deterministic Policy Gradient (TD3), to navigate the complexities of the stock market and maximize financial returns.

## Introduction
Trading stocks effectively in the highly volatile and unpredictable financial markets requires innovative approaches beyond traditional methods. Our project utilizes reinforcement learning to dynamically adapt trading strategies based on real-time market data, aiming to outperform standard trading benchmarks.

## Key Features
<ul>
<li>Multiple RL Algorithms: Implements DQN, A2C, and TD3, comparing their effectiveness in stock trading.
<li>Dynamic Strategy Adaptation: The system learns optimal trading actions directly from market interactions, adapting to changing conditions without human intervention.
<li>Real-World Data Application: Uses historical stock data from Larsen & Toubro (LnT) provided by Zerodha, covering the period from August 2011 to February 2024.
</ul>

## Model Architecture
The architecture is based on three main components:
<ol>
<li>Data Preprocessing: Converts raw stock data into a format suitable for RL training, including technical indicators like SMA and EMA.
<li>RL Environment Setup: Defines the state space, action space, and reward function critical for training the RL agents.
<li>RL Agents: Implements three distinct RL algorithms to train and evaluate different trading strategies.
</ol>

For an in-depth explanation of the methodologies, architectures, and findings of this project, please refer to our detailed report available <a href=https://github.com/rajtulluri/Automated-Stock-Trading-using-Reinforcement-Learning/blob/main/Automated_Stock_Trading_using_Reinforcement_Learning.pdf>here</a>.