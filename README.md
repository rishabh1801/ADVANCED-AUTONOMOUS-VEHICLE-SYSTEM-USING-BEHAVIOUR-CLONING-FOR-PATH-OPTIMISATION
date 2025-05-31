# 🚗 Advanced Autonomous Vehicle System
**Using Behaviour Cloning for Path Optimisation**

> A cost-effective, vision-based autonomous driving system built using deep learning techniques like Convolutional Neural Networks (CNNs), Behavioural Cloning, and Reinforcement Learning. Trained and tested in simulators (Udacity, CARLA), this project mimics human driving behavior with high accuracy and real-time responsiveness.

---

## 📘 Project Overview

This project presents a scalable and affordable alternative to traditional sensor-heavy autonomous systems. Instead of relying on costly LiDARs or radar, it uses only camera input, applying behavioural cloning and reinforcement learning to train a self-driving AI model in simulated environments.

**Key Technologies Used:**
- CNN for visual perception
- Behavioural Cloning for supervised learning
- Reinforcement Learning for adaptability
- Simulators: Udacity & CARLA
- Deep Learning Libraries: TensorFlow, PyTorch, OpenCV

---

## 👨‍💻 Team Members

| Name             | USN           |
|------------------|---------------|
| Patel Muhammad   | ENG21CS0290   |
| Amar Kumar       | ENG21CS0030   |
| Ganesh           | ENG21CS0135   |
| Rishabh Singh    | ENG21CS0331   |

**Supervisor:** Dr. Gousia Thahniyath

---

## 🎯 Objectives

- Train a model to imitate human driving from visual input
- Achieve real-time, image-based autonomous navigation
- Test in simulated environments for various real-world conditions
- Minimize dependency on expensive hardware
- Open-source modular design for research and academic use

---

## 🔍 Problem Statement

> Current autonomous vehicles depend on expensive multi-sensor fusion systems which limit scalability. This project uses cost-effective, vision-based AI to enable path optimization through behavioural cloning.

---

## 🧠 System Architecture

1. **Input:** Camera images (center, left, right)
2. **Processing:** CNN for feature extraction and decision prediction
3. **Training:** Supervised with behavioural cloning, optionally fine-tuned with reinforcement learning
4. **Output:** Steering angle predictions for navigation

---

## 🧪 Experimentation & Results

| Metric                     | Result       |
|----------------------------|--------------|
| Lane-Keeping Accuracy      | 95%          |
| Obstacle Detection Rate    | 98%          |
| Collision Rate             | 1%           |
| Inference Time             | 50 ms        |

Tested under various conditions:
- ✅ Urban daylight
- 🌙 Night driving
- 🌧️ Wet/reflective roads
- 🚧 Obstacle avoidance
- 🏞️ Sharp curves & slopes

---

## 🔧 Tech Stack

- **Frameworks:** TensorFlow, PyTorch
- **Tools:** OpenCV, Docker (optional)
- **Simulators:** Udacity, CARLA
- **Cloud:** AWS, Google Cloud
- **Languages:** Python

---

## 📦 Features

- End-to-end CNN architecture for steering prediction
- Balanced dataset with preprocessing and augmentation
- Optional RL module for adaptive decision-making
- Modular, open-source architecture
- Recovery mechanisms for deviation handling

---

## 🚀 Future Enhancements

- Integrate real-world datasets (e.g., KITTI, BDD100K)
- Add multi-sensor fusion (LiDAR, GPS)
- Deploy on real hardware (Jetson Nano, Raspberry Pi)
- Implement advanced RL-based decision modules
- Domain adaptation (sim-to-real transfer)

---

## 📂 Project Structure

```bash
├── data/                  # Collected simulator data
├── model/                 # CNN model and weights
├── scripts/               # Training, testing, preprocessing code
├── logs/                  # Training/validation logs
├── results/               # Evaluation metrics, plots
├── Dockerfile             # (Optional) Containerization
└── README.md              # You're here!
