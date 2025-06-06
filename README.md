# digital-control-system-project
The main purpose of this project is to use an STM32 microcontroller for motor control. By writing software to implement a digital controller, the motor can be made to operate according to the desired specifications.

In Lab 1, we use ARM's Keil Studio as the development platform to ensure that the code can be successfully flashed onto the development board(STM32F446) and make the LED blink at a specified frequency.

In Lab 2, we have two main tasks. The first is to convert an analog control voltage into a digital PWM duty cycle signal, since the STM32 does not support analog output. The second task is to input the PWM signal and the motor speed data read from the encoder into MATLAB Simulink for system identification, in order to obtain the motor's transfer function.

In Lab 3, now that we have obtained the transfer function of the motor, the next step is to determine whether the motor can meet our specifications. We will then implement a digital controller using a difference equation to provide compensation.
