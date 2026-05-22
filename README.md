**The paper was published in IEEE SSRR 2025 and won "Rising Star Award":**
*U. Cakar, "Comparative Gait Performance Study in Biomimetic Snake Robots for Post-Earthquake Search and Rescue Tasks," 2025 IEEE International Symposium on Safety Security Rescue Robotics (SSRR), Galway, Ireland, 2025, pp. 209-214, doi: 10.1109/SSRR68451.2025.11391294.*

The research simulation pipeline and 3D-printed mobile robotic system created by Umut Cakar to analyze the performance of modular snake robots on virtual post-earthquake disaster zones. Features "lateral undulation" and "sidewinding" locomotion gaits, and "rubble" and "ramp" terrains.

Simulation Guide:
- Select the locomotion gait and terrain type. 
- Use manual steering to follow the task trajectory and complete the obstacle course. 
- Collect and process performance data.

Hardware & Software Specs:
- Two biomimetic locomotion gates available, namely lateral undulation and sidewinding.
- Chassis is designed with OnShape and 3D-printed with PLA+ through 4 rounds of physical durability testing.
- Main electronic hardware includes Arduino Uno microcontroller, ESP32 Cam Module (OV2460), 3S 11.1V LiPo Battery and 300W Buck Converter.
- Utilizing 6-12 MG995 servo motors to create periodic oscillation of body links and forward propulsion.
- Current version uses passive wheel rails to inflict anisotropic friction.
- Robot firmware coded in C++. Simulation & data analysis in Python.
