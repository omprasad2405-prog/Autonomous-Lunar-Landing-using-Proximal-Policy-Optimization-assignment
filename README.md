# Autonomous-Lunar-Landing-using-Proximal-Policy-Optimization-assignment
Autonomous Lunar Landing using Proximal Policy Optimization (PPO)
A Deep Reinforcement Learning project focused on training an autonomous spacecraft agent to safely land on a designated landing pad using the Box2D physics engine physics simulator.

Developer Information
Name: Akshat Garg
Registration Number: 23BCE10641
Development Environment: macOS (Apple Silicon M2 Pro/Max/Base architecture)
Project Objective
The goal of this implementation is to leverage the Actor-Critic framework via PPO to master the continuous flight control dynamics of the LunarLander environment[cite: 1]. Instead of utilizing hand-crafted rule-based physics equations, the agent organically derives an optimal thrust policy through active exploration and cumulative reward maximization[cite: 1].

Environment Specifications
Environment Name: LunarLander-v3[cite: 1]
Observation Space: 8-Dimensional continuous vector tracking positions (
x
,
y
), velocities (
v
x
,
v
y
), tilt angle, angular velocity, and left/right leg ground contact assertions[cite: 1].
Action Space: Discrete (4) representing: Do nothing, fire left orientation engine, fire main engine, or fire right orientation engine[cite: 1].
