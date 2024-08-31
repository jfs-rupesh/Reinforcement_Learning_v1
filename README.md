

# Reinforcement Learning Project

This project applies various RL algorithms to two environments: Cartpole and Humanoid.

## Environment 1: Cartpole

- **DQN:** Adjusted parameters like learning rate, batch size, and target update interval led to consistent max scores of 500.
- **PPO:** Achieved max score of 500 without needing parameter tuning.

### Comparison:
- **PPO:** Stable performance without tuning.
- **DQN:** Required tuning but showed strong results, more sample-efficient.

## Environment 2: Humanoid

- **SAC:** Faster convergence, balances exploration and exploitation effectively.
- **TD3:** Slower to converge, but robust for continuous action spaces.

### Comparison:
- **SAC:** Converges faster.
- **TD3:** Needs more episodes but stable.

## References:
- DQN, PPO, SAC, TD3 Documentation
- Hugging Face


This version is concise and focuses on key points.
