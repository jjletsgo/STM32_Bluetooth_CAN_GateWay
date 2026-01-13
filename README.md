# STM32_Bluetooth_CAN_GateWay
Develping Bluetooth_CAN_GateWay with STM32F446 now 
(actually, it's part of PBL Project making tactical UGV)

# HW
+ MCU : STM32F446 (specific name of the board : NUCLEOF446RE)
+ Bluetooth Module : HC06
+ CAN Tranceiver : SN65HVD230
+ for the CAN Controller, I'm using dual CAN in STM32F446 (built in CAN Controller in STM32F446)

# Additional Info
+ STM32 communicates with HC06 via UART Communication (as far as I know, 115200 bps is the max baudrate)
+ u can set basic parameter of bluetooth com via UART Communication as well (u can find related inforamtion at Datasheet of HC06)  
Before using this , I highly recommend you to read reference manual of STM32F446 describing built-in CAN Controller.


