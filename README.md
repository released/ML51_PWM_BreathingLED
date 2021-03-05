# ML51_PWM_BreathingLED
ML51_PWM_BreathingLED

update @ 2021/03/05

1. initial P0.3 (PWM0_CH2) , test breathing LED (connnect with external LED) with ML51PC EVM 

2. breathing LED scenario :

- target : within 1.5 sec (duty from 0 to 100 or from 100 to 0)

with duty resolution : 100 , change duty per 15 ms , total duty change timing : 15*100 = 1500 ms

- target : within 2 sec (duty from 0 to 1000 or from 1000 to 0)

with duty resolution : 1000 , change duty per 2 ms , total duty change timing : 2*1000 = 2000 ms

by connect PWM pin and covert with RC for DC voltage , below is waveform capture (1.5 sec low to high , 1.5 sec high to low)

![image](https://github.com/released/ML51_PWM_BreathingLED/blob/main/LED_15ms.jpg)

by connect PWM pin and covert with RC for DC voltage , below is waveform capture (2 sec low to high , 2 sec high to low)

![image](https://github.com/released/ML51_PWM_BreathingLED/blob/main/LED_2ms.jpg)

3. behavior refer to video (IMG_1447.MOV) in repo.

![image](https://github.com/released/ML51_PWM_BreathingLED/blob/main/IMG_1447.gif)

4. PWM freq : 10K

![image](https://github.com/released/ML51_PWM_BreathingLED/blob/main/IPWM_10K.jpg)


