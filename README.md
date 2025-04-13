# KungFu Master A3C Implementation

## Project Overview
This project implements the Asynchronous Advantage Actor-Critic (A3C) algorithm to train an AI agent to play the classic Atari game KungFu Master. The implementation demonstrates expertise in deep reinforcement learning, parallel computing, and computer vision.

![KungFu Master Agent Demo](video.mp4)

## Technical Skills Demonstrated
- **Deep Reinforcement Learning**: Implementation of A3C algorithm, one of the most sophisticated RL algorithms
- **PyTorch**: Advanced usage of neural networks, including CNN architecture and parallel processing
- **Computer Vision**: Real-time frame preprocessing using OpenCV
- **Parallel Computing**: Multi-process training using PyTorch's multiprocessing
- **Gymnasium (OpenAI Gym)**: Environment management and interaction

## Key Features
- Custom CNN architecture for processing game frames
- Frame preprocessing pipeline for optimal learning
- Multi-process training for faster convergence
- Actor-Critic network implementation
- Real-time performance visualization

## Technical Implementation Details
### Neural Network Architecture
- 3 Convolutional layers with ReLU activation
- Separate policy (Actor) and value (Critic) heads
- Input: 4 stacked frames (42x42 pixels)
- Output: 14 possible actions + state value

### Training Process
- Parallel training using multiple processes
- Shared network parameters across processes
- Asynchronous gradient updates
- Frame preprocessing including:
  - Grayscale conversion
  - Resolution reduction
  - Frame stacking
  - Normalization

## Results
The trained agent demonstrates strong performance in the KungFu Master environment, showing:
- Effective combat strategies
- Good spatial awareness
- Quick reaction to enemies
- Consistent high scores

## Dependencies
- PyTorch
- Gymnasium
- OpenCV (cv2)
- NumPy
- Atari ROMs

## Skills Highlighted for Recruiters
1. **Deep Learning**: Advanced neural network design and implementation
2. **Reinforcement Learning**: Understanding and implementation of state-of-the-art algorithms
3. **Parallel Computing**: Efficient multi-process training implementation
4. **Computer Vision**: Real-time image processing and analysis
5. **Python Programming**: Clean, efficient, and well-structured code
6. **Problem Solving**: Complex system design and optimization

## Video Demo
The included video demonstrates the trained agent's performance, showing:
- Sophisticated fighting techniques
- Strategic movement
- Efficient enemy handling
- Consistent scoring ability
