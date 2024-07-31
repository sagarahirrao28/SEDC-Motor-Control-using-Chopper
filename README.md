# SEDC-Motor-Control-using-Chopper
![Screenshot 2024-07-31 205331](https://github.com/user-attachments/assets/217f1cc0-8456-4721-b33f-e3d13cb11237)<br>

## About the project
This project focuses on the control of a separately excited DC motor using a chopper as a converter. 
The objective is to regulate the motor's speed within its rated limits by employing a chopper firing 
circuit and a Proportional-Integral (PI) type controller. The control system consists of two loops: 
one for current control and the other for speed control. Initially, a transfer function of SEDC motor
 is derived and then the PI controller, in conjunction with the modulus hugging technique, is employed
 to optimize the speed control loop for stable and efficient motor control. The complete layout of the 
DC drive system, including the chopper, is designed and implemented. MATLAB/Simulink is utilized for 
the modeling and simulation of the DC drive system. The simulation is performed under varying speed and
 load torque conditions, including rated speed and load torque, half the rated load torque and speed, 
step speed and load torque, and stair case load torque and speed. The simulation results demonstrate 
the successful control of the DC motor's speed, showcasing the effectiveness of the proposed control
 system.
