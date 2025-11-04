---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: page
---

![Julian_Millan](assets/images/website_photo.jpg)

I am a first year Master of Science in [Mechanical Engineering](https://www.meche.engineering.cmu.edu/) at [Carnegie Mellon University](https://www.cmu.edu/). I am currently doing research on Human-Robot Interaction in the [Robotics Institute](https://www.ri.cmu.edu/) with the [Robotic Caregiving and Human Interaction (RCHI) lab](https://rchi-lab.github.io/), focusing on assistive robotics and communication of robotic intent.

I previously graduated from the [California Institute of Technology (Caltech)](https://www.caltech.edu/) with a Bachelor of Science in Mechanical Engineering. During my time at Caltech, I conducted Robotic Machine Learning research with the [Autonomous Robotics and Controls Lab (ARCL)](https://aerospacerobotics.caltech.edu/) and Robotic Hardware research with the [Advanced Mechanical Experimental Robotics (AMBER) Lab](http://www.bipedalrobotics.com/).

---

## Contact

**Email**: [julian.millan729@gmail.com](mailto:julian.millan729@gmail.com)

**Linkedin**: [www.linkedin.com/in/julian-millan-hri](www.linkedin.com/in/julian-millan-hri)

**Github**: [https://github.com/julian-millan](https://github.com/julian-millan)

**Hackaday**: [https://hackaday.io/jmillan](https://hackaday.io/jmillan)

---

## Research

### Curent Master's Research (August 2025 - Present)
My current research with the RCHI Lab focuses on bidirectional communication between assistive robots and their users. My focus is on improving the capability of assistive robots to navigate roadblocks they encounter in their tasks. 

### Training a Biped to Walk with Behavior Cloning and Reinforcement Learning (June - September 2024)
I worked with Caltech Professor Soon-Jo Chung on researching how to use machine learning to control a bipedal robot's walking behavior in a novel direction. The novel direction chosen was to use behavior cloning on a capture-point inverse kinematics system and inverse dynamics system.

The concepts primarily used in this project were types of Machine Learning (ML). I used Conservative Q-Learning (CQL), a form of Offline Reinforcement Learning (RL), and Behavior Cloning (BC) to attempt to create a bipedal walking algorithm for the robot. The simulation would run a little slow using the simple BC policy format, so I used a different policy saving format known as an "mlpfile" which both improved simulation speed and model performance. 

Further work included improving post-simulation data visualization, fixing the broken model training pipeline, collecting robust training data, reviewing and implementing CQL, and tuning/improving model parameters. The end result was a 20% improvement in model accuracy. Differences in the performance can be observed with the [slower](https://youtu.be/nL_OXZj_FPo) previous version and the newer [faster](https://youtu.be/hKPzngbcWBk) version I designed. For more detail, the final report can be viewed <a href="/assets/2024 SURF Final Report.pdf" class="btn" target="_blank">here. (PDF)</a>

### Designing an Optimized Robotic Ankle for a Bipedal Robot (June - September 2023)
I worked with Caltech Professor Aaron Ames in the Caltech AMBER lab on robotic hardware design. This was my first experience in research, and I had the task of designing an actuated ankle for a bipedal robot with a passive toe joint. I gained a lot of valuable experience in understanding robotic hardware and how to apply my mechanical knowledge in a robotics sense. I leveraged my skills in FEA and 3D CAD to iteratively design the ankle to be lightweight and compatible with rotary motors. I learned about the value of the speed and precision rotary motors have compared to the convenience of linear actuators.
