# DSAN-6650-Project

## Project Overview
This project examines the effectiveness of various reinforcement learning (RL) algorithms in the context of a blackjack simulation, facilitated by the OpenAI Gym environment. The study tests multiple strategies, including Monte Carlo (MC) on-policy and off-policy, SARSA, Q-learning, and Deep Q-Network (DQN), to determine which method most effectively minimizes losses in a traditional game of blackjack.

## Features
- **Range of RL Methods**: Analysis includes Monte Carlo (MC) both on-policy and off-policy, SARSA, Q-learning, and DQN.
- **Simulation Environment**: Utilizes the blackjack environment provided by OpenAI Gym, offering a consistent and controlled setting for evaluation.
- **Performance Comparison**: Compares the average payout of each method to assess their relative effectiveness and strategy optimization.
- **Insightful Conclusions**: Provides valuable insights into the practical implications of each RL strategy, highlighting the inherent difficulty of achieving a positive return in blackjack.

## Results
- **Monte Carlo (MC) On-policy**: Emerged as the most effective method with the highest average payout, indicating its suitability for this specific game environment.
- **Limitations Noted**: Despite the superior performance of some strategies, all methods resulted in a negative expected return, confirming the challenging nature of consistently winning against the casino.

## Conclusion
This analysis underscores the complexities of applying RL strategies to blackjack. Although the on-policy Monte Carlo method demonstrated the best performance, no strategy ensured a positive long-term return, reflecting the game's built-in house advantage. This study contributes to a deeper understanding of strategic decision-making in adversarial gaming environments and provides a benchmark for future explorations of RL applications in similar contexts.

## Website

Check the [Webpage](https://hyf112.github.io/DSAN-6650-Project/) for more details.