# FromMLtoDeepRL 🚀

Welcome to **FromMLtoDeepRL** – a curated journey through the world of **Artificial Intelligence**, covering the fundamentals of **Machine Learning**, diving deep into **Deep Learning**, and venturing into the dynamic realm of **Reinforcement Learning**.

This repository documents my learning and experimentation through:
- 📘 Assignments focused on key algorithms and concepts  
- 🧪 Mini-projects applying those ideas to practical problems  
- 🏁 A capstone project that brings it all together in a real-world scenario

---

## 📘 Topics Covered

### 1. **Introduction to Data Science and Machine Learning**
   - Understanding data preprocessing, feature engineering, and model evaluation.
   - Implementing algorithms like linear regression, decision trees, and clustering.

### 2. **Introduction to Deep Learning**
   - Exploring neural networks, backpropagation, and architectures like CNNs and RNNs.
   - Hands-on projects using frameworks like TensorFlow and PyTorch.

### 3. **Introduction to Sequential Decision Making and Reinforcement Learning**
   - Grasping the basics of RL, including agents, environments, rewards, and policies.
   - Implementing simple algorithms like Q-learning.

### 4. **Reinforcement Learning Algorithms**
   - Diving deeper into advanced RL algorithms such as Deep Q-Networks (DQN), Policy Gradient methods, and Proximal Policy Optimization (PPO).
   - Experimenting with various environments and tuning hyperparameters.

### 5. **RL Applications to Autonomous Systems**
   - Applying RL to control tasks like balancing a pole (CartPole), walking agents (BipedalWalker), and robotic manipulation.
   - Developing agents capable of learning complex behaviors through trial and error.

---

## 🧠 OpenAI Gym Environments

Throughout this journey, I've utilized various OpenAI Gym environments to train and evaluate reinforcement learning agents. Here are some of the environments explored:

### 1. **CartPole-v1**
- **Objective**: Balance a pole on a moving cart.
- **Challenge**: Prevent the pole from falling over by applying forces to the cart.


### 2. **MountainCar-v0**
- **Objective**: Drive a car up a steep hill.
- **Challenge**: The car's engine is not powerful enough to drive up the hill in a single pass; it must first go down the hill to build momentum.


### 3. **Pendulum-v0**
- **Objective**: Balance an inverted pendulum.
- **Challenge**: Control the torque applied to the pendulum to keep it upright.


### 4. **LunarLander-v2**
- **Objective**: Land a spacecraft on the moon's surface.
- **Challenge**: Control the spacecraft's orientation and velocity to land safely on the landing pad.

> 🧠 *The LunarLander environment involves firing orientation and main engines at the right time to land gently. A great intro to more complex RL problems with sparse rewards.*

---

## 🧩 MuJoCo Environments

MuJoCo (Multi-Joint dynamics with Contact) is a physics engine designed for simulating realistic robotic movements and dynamic tasks. These environments involve continuous control and are widely used for research in reinforcement learning.

### 1. **Ant-v4**
- **Objective**: Control a 3D quadruped robot to move forward.
- **Challenge**: Coordinate the robot’s limbs to achieve stable and efficient locomotion.


### 2. **Hopper-v4**
- **Objective**: Make a 2D one-legged robot hop forward without falling.
- **Challenge**: Balance hopping motion while staying upright.



