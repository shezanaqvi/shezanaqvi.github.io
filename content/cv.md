---
title: "Curriculum Vitae"
layout: "cv"
type: "page"
slug: "cv"
bodyClass: "wide-layout"  
description: "Robotics & AI Researcher | Electrical Engineering Undergrad at LUMS"
image: "img/avatar.png"
comments: false
menu:
    main:
        weight: 3
---

# Sheza Abbas Naqvi
**Robotics & Perception Researcher** *Islamabad/Lahore, Pakistan* | *[26100161@lums.edu.pk](mailto:26100161@lums.edu.pk)* | *[LinkedIn](https://linkedin.com/in/sheza-naqvi)*

---

## 🔬 Research Interests
**Robust State Estimation & Control** | **Multi-Modal Sensor Fusion (SLAM)** | **Distributed Multi-Agent Systems** | **Learning-Based Control**

---

## 🎓 Education
**Lahore University of Management Sciences (LUMS)** | *Sept 2022 – May 2026* **BS Electrical Engineering** (Minor in Computer Science)  
* **Relevant Coursework:** Mobile Robotics, Dynamic Programming & RL, Machine Learning, Feedback Control Systems, Signals & Systems, Network-Centric Computing.

---

## 🛠 Technical Skills
* **Robotics:** ROS/ROS2, FAST-LIO2, ArduPilot/PX4, MoveIt, Gazebo, LiDAR Processing.
* **Languages:** C++ (Strong), Python (Advanced), MATLAB, SQL.
* **AI & Vision:** OpenCV, PyTorch, TensorFlow, Keras, Agisoft Metashape.
* **DevOps/Tools:** Linux (Ubuntu), Docker, Git, SolidWorks.

---

## 💼 Research & Experience

### **Autonomous UAV-Based Crop Growth Mapping (Senior Year Project)** *May 2025 – Present*
Leading a multimodal data campaign for wheat phenotyping to address food security.
* **Hardware:** Architected a 500mm carbon-fiber quadcopter (Pixhawk 6C, Odroid N2+, Livox Mid-360).
* **Autonomy:** Developed a real-time stack on Linux integrating **FAST-LIVO2** LiDAR odometry and **ArduPilot EKF3** fusion.
* **Mapping:** Generated high-fidelity 3D orthomosaics using Agisoft Metashape & Open3D for spatial-temporal analysis.

### **Safe Multi-Agent RL for Cooperative Navigation** *Sept 2025 – Dec 2025*
*Developed a safe navigation framework combining reinforcement learning with control-theoretic safety.*
* Built a custom Python simulation to train a decentralized **Soft Actor-Critic (SAC)** model with a centralized attention critic.
* Integrated a hybrid **MPC safety shield** (ACADOS) to guarantee collision constraints during training, achieving **66.5% success** in obstacle-dense environments.
* Implemented a three-stage curriculum learning strategy to progressively learn formation control and obstacle avoidance.

### **Stochastic Utility-Aware Multi-Robot Task Allocation** *Sept 2025 – Dec 2025*
*Designed a unified warehouse coordination system for conflict-free multi-agent planning.*
* Proposed a hybrid architecture combining **SCOBA** for utility-based task allocation and **PM-CBS** for conflict-free path planning.
* Implemented **EKF localization** with a beam-based LiDAR model to robustly track trajectories under sensing noise.
* Achieved **zero collisions** and superior utility efficiency compared to Greedy A* and Q-learning baselines in simulation.

### **Visual-to-Motion Robotic Drawing** *Jan 2025 – April 2025*
*Developed a vision-guided sketching system for an **Interbotix Widow X 250s** arm.*
* Designed a pipeline: Image contour extraction → Trajectory generation → Real-time execution via **MoveIt**.
* Performed extrinsic calibration using RGB-D cameras (RealSense D455) and projective geometry.

### **Real-Time Age & Gender Prediction** *Jan 2025 – April 2025*
*Built a dual-head **ResNet** deep learning system for simultaneous age regression and gender classification.*
* Implemented **Bayesian inference** with Monte Carlo dropout to quantify predictive uncertainty.
* Deployed via **TensorFlow.js** for real-time in-browser inference.

---

## 👩‍🏫 Teaching Experience
* **TA - Communication Systems (EE380):** (Sept 2025 – Present) Conducted tutorials and graded for 30+ students.
---

## 🏆 Honors & Media
* **Featured Research:** "Smarter Farming, Lower Cost" – Center for Water Informatics (WIT), 2025.
* **Writing:** Authored "CYTE Foundation: Educating Pakistan's Future" & Co-Editor-in-Chief of *SuperNova Gazette*.