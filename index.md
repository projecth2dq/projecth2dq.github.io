## Project H2DQ

Traditionally, for maintaining Quality of Service (QoS) proportional fairness and max-min fairness policy services are used independently. In this project, we propose an optimisation followed by two-dimensional queue management policy, called Hierarchical Two Dimension Queue (H2DQ) integrating both proportional fairness and max-min fairness. Here proportional fairness criterion decides the traffic shaping parameters for ensuring QoS among different traffic classes, and max-min fairness criterion determines the actual routing paths and shaping policies for different traffic flows considering the service level fairness.

H2DQ has been implemented and tested over a network setup emulated by using MiniNet emulator platform. We are extending this work by implementing H2DQ over CloudLab to study the effect of internet latency on our management policy.

[Bhaumik, Sumitro & Chakraborty, Sandip. (2018). Hierarchical Two Dimensional Queuing: A Scalable Approach for Traffic Shaping using Software Defined Networking. 150-158. 10.1109/NETSOFT.2018.8460072.](https://ieeexplore.ieee.org/document/8460072)