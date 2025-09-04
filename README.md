# Portfolio

This portfolio showcases selected projects from my academic and personal work.

---

## Featured Projects

### [Swarm Navigation in ARGOS Simulator](https://github.com/nolangroves/SwarmNavigation)
*Directionally aided swarm navigation in ARGoS3 with RAB-based message passing and a sparse-swarm fallback.*  
- **Tech:** C++, ARGoS3  
- **Highlights:**  
	- Decentralized navigation with local Range-and-Bearing (RAB) communication  
	- Roles: navigator, beacon, and relay; parameters configurable via XML  
	- Fallback uses last known heading to reduce wandering at low densities  
	- Results and analysis summarized in the linked project report  


https://github.com/user-attachments/assets/df02d012-5640-4c4e-9669-8fd1a7f8d3b7




---

### [Robotic Arm Motion Planner](https://github.com/nolangroves/RRTMotionPlanner)
*RRT-based pick-and-place planner in MuJoCo with IK and collision checking (Panda/xArm7).*  
- **Tech:** MuJoCo, Python  
- **Highlights:**  
	- Configuration-space RRT with step-size and goal-threshold tuning  
	- Inverse kinematics adapted from dm_control for precise end-effector targets  
	- Randomized scenes with obstacles, target, and goal generation  
	- Multi-phase motion: approach, grasp, transfer, release  
	- Supports multiple robot models (Franka Panda, xArm7)  


https://github.com/user-attachments/assets/6992fafd-2032-4852-a9cb-f24e28fab1cc


---

### [Potential-field based area coverage](https://github.com/nolangroves/SwarmNavigation)
*Potential-field controller that spreads a swarm to cover an unknown 2D area.*  
- **Tech:** Python, pygame  
- **Highlights:**  
	- Attractive/repulsive fields for even dispersion and boundary repulsion  
	- Real-time 2D visualization with adjustable gains and timestep  
	- Simple obstacle primitives and collision avoidance  
	- Minimal, readable implementation for experimentation/teaching  



https://github.com/user-attachments/assets/5215bf37-d43e-446b-8c7d-c32e2eebc2d5




---

### [Augmented Reality display](https://github.com/nolangroves/AugmentedRealityLaneNavigation)
*Detect the road’s vanishing point and project a stabilized 3D guidance arrow onto video.*  
- **Tech:** Python, OpenCV  
- **Highlights:**  
	- Lane isolation via HSV masks + Canny; intersections from Hough line segments  
	- Robust vanishing-point estimate stabilized with a 2D Kalman filter  
	- FOV-derived intrinsics to project a 3D arrow onto the road plane  


https://github.com/user-attachments/assets/1753f8dd-c82c-4d65-8739-3a227d04e80e


---

## Skills & Tools
- **Languages:** Python, C++, JavaScript  
- **Robotics/AI:** ROS, PyTorch, TensorFlow, OpenCV, numpy  
- **Tools:** Git, Docker, Linux, MATLAB, MuJoCo  

---

## Resume
[Download PDF](https://github.com/nolangroves/Resume/raw/main/Resume.pdf)  


---

## Contact
- 🔗 LinkedIn: [linkedin.com/in/nolangroves](https://linkedin.com/in/nolangroves)

---

### Notes
This is a curated portfolio. Each linked repository includes:  
- Clear README with setup instructions  
- Screenshots or demos  
