**Agentforce Embodied AI Simulation**
**Isaac Sim World Lobby Scene with Cobalt AI Robot**

**Overview**

This repository contains a Universal Scene Description (USD) file showcasing the integration of Agentforce's Atlas Reasoning Engine with Cobalt AI robotics in a simulated enterprise office environment. Built in NVIDIA Isaac Sim, this digital twin demonstrates how autonomous agents extend beyond digital interactions into physical automation for facilities management and Field Service operations.

![Lobby Scene](/images/Lobby.png)

**Technical Implementation**

**Scene Architecture**

The World Lobby scene represents a photorealistic enterprise office environment complete with furniture, equipment, safety stations, and navigable pathways. The environment serves as a proving ground for testing Agentforce reasoning capabilities in real world spatial contexts before hardware deployment.

**Cobalt AI Robot Integration**

Converting Cobalt's native ROS xamco format to URDF enabled full physics simulation within Isaac Sim. The robot model includes:

- **Kinematic Joints**: Prismatic and revolute connections between manipulator arms, sensor arrays, and mobile base platform
- **Material Properties**: Friction coefficients assigned to contact surfaces for realistic object manipulation and floor transition navigation
- **Mobility Parameters**: Wheel diameter specifications and rotational axis definitions ensuring authentic differential drive dynamics with proper acceleration profiles and turning radiuses

**OmniGraph Action Graph**

The OmniGraph action graph orchestrates the integration between Agentforce Atlas Reasoning Engine and robot control systems. This graph manages:

- **Perception Pipeline**: NVIDIA Cosmos VLM integration for visual equipment detection and scene understanding
- **Decision Logic**: Atlas reasoning engine outputs translated into robot navigation commands and manipulation sequences
- **Field Service Integration**: Automated case creation workflows triggered when safety equipment violations are detected

**Animation Graphs**

Character animation graphs bring life to the simulation with autonomous agents representing facility occupants. These graphs drive:

- **Human Motion**: Realistic walking patterns, workspace interactions, and environmental responses
- **Behavioral Variety**: Multiple character archetypes exhibiting different movement patterns and facility usage
- **Collision Avoidance**: Dynamic pathfinding ensuring characters and robots navigate shared spaces safely

**Use Cases**

This simulation validates Agentforce capabilities for autonomous facility inspections, security patrols, equipment monitoring, and compliance verification before deploying to production robotics hardware.

**Presentation**

This work will be demonstrated at NVIDIA GTC 2026, showcasing the future of agentic robotics where reasoning engines meet physical automation.
