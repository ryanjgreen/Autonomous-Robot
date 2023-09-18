## Ocean Networks Canada Autonomous Underwater Vehicle (AUV) Challenge

### Project Overview

This repository documents the design and development of an autonomous underwater vehicle (AUV) prototype, which was completed as part of the Ocean Networks Canada AUV Challenge. The challenge aimed to create a robot capable of positioning a debris cleaning/removing device on top of underwater cameras and sensors in a controlled dry lab environment. The project was undertaken by [Your Engineering Consulting Company] and is presented here as a summary of our work and accomplishments.

### Project Achievements

#### 1. Design and Fabrication

Our team successfully designed and fabricated an AUV prototype capable of completing the specified tasks in the challenge:

- **Search Area:** Our AUV effectively navigates a 2.29 meters by 2.29 meters search area, respecting the minimum 5 cm tall wall boundaries.

- **Starting Position and Direction:** The AUV's initial placement and orientation can be randomly set, and the robot consistently completes the task from any direction.

- **Interaction with Walls:** We incorporated obstacle detection sensors and collision avoidance algorithms to ensure that our AUV never gets wedged next to walls or corners.

- **Target Detection:** Our AUV accurately detects the infrared light source simulating the underwater sensor and can distinguish it from background radiation.

- **Simulated Cleaning:** The AUV successfully deposits a ping pong ball on top of the target without causing damage or knocking it over.

- **Robot Recovery:** After task completion, our AUV autonomously moves to the arena edge and stops within 5 cm, with the front side parallel to the edge.

- **Robot Locomotion:** Our AUV demonstrated efficient locomotion, with a good balance between speed, turning radius, and adherence to dry lab simulation parameters.

- **Job Completion Signal:** The AUV signals task completion, which is essential for real-world applications and remote operation.

#### 2. Innovation and Originality

Our team invested time in creating an innovative solution. Notably:

- We implemented a novel approach for object placement on the target, which distinguishes our AUV from traditional solutions.

- Our obstacle avoidance and wall detection algorithms showcase our creativity in solving real-world challenges.

- The AUV's efficient locomotion is a testament to our original design concepts.

#### 3. Time Efficiency

Our AUV consistently completed the task in a time-efficient manner, demonstrating its practicality for addressing data transmission interruptions in underwater observatories.

#### 4. Cost-Effectiveness

We have been mindful of cost-effectiveness throughout the design process. The components used in the AUV are readily available and budget-friendly, ensuring that the robot meets Ocean Networks Canada's financial considerations.

### Future Developments

While the AUV prototype successfully meets the challenge specifications in a dry lab environment, further refinements and testing in a simulated underwater setting are recommended. Additionally, adapting the AUV for deployment in real underwater environments and ensuring its robustness in handling various conditions will be the focus of future development.

### Conclusion

Our AUV prototype represents a significant step toward addressing the critical need for underwater observatory sensor maintenance. We look forward to potential collaboration with Ocean Networks Canada to further refine and adapt this technology for real-world deployment.

For more details on our AUV's design, development, and performance, please refer to the provided documentation and code in this repository.
