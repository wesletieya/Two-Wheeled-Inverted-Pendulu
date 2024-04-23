# Two-Wheeled-Inverted-Pendulum
You can access the full presentation via the link below : 
https://www.canva.com/design/DAGCfzghco0/c8IOaK-BY9OCZEnV3wlmRw/edit?utm_content=DAGCfzghco0&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

In this project we experimented with self balancing-robots that use the two wheeled inverted pendulum TWIP system.
This project's objective is to stabilize the robot in a closed loop using the PID(Proportional-Integral-Derivative) regulator .
We started with a simplified mathematical model of the system to understand the model's requirements and challenges .

![image](https://github.com/wesletieya/Two-Wheeled-Inverted-Pendulum/assets/129344878/25d78771-adb8-4bf7-8d77-7d5a8ece0344)

We proceeded to the conception of the robot using the Arduino Uno card , the MPU 6050 sensor and other electrical components.
The electrical wiring of the robot is as such :

![Untitled](https://github.com/wesletieya/Two-Wheeled-Inverted-Pendulum/assets/129344878/79cc8022-d09a-4621-b283-f57ab8a55942)


This is a picture of the prototype we created :

![IMG_4496](https://github.com/wesletieya/Two-Wheeled-Inverted-Pendulum/assets/129344878/dbdad588-1cb8-43a3-b364-e7d78c1796a9)

Then we proceeded to implementing the PID regulator with an Arduino code .

Below is a a bloc diagram detailing the overall fuction of the regulator :

![image](https://github.com/wesletieya/Two-Wheeled-Inverted-Pendulum/assets/129344878/425d979d-162b-46a6-bad7-04ad05f88d53)

We implemented the same regulator in LabView in order to visualise in real-time the variation of the error in the system , we also created a LabvView graphical interface for better visualization.

![Untitledvideo-MadewithClipchamp11-ezgif com-video-to-gif-converter](https://github.com/wesletieya/Two-Wheeled-Inverted-Pendulum/assets/129344878/9a606a80-0385-478b-ac78-10a356bd0bc7)![ezgif com-optimize](https://github.com/wesletieya/Two-Wheeled-Inverted-Pendulum/assets/129344878/0817af25-324d-461f-8878-84a45718c22e)



