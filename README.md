# PROJECT_02 keypad 4x4 using bare-metal 
- Write a program that detect when key is pressed and print character.
****

## Project Structure
- the project has structure like this: 
```

├── Inc/
│   └── stm32f411re.h          # Memory map & register definitions (RCC, GPIO, etc.)
├── Src/
│   ├── main.c                 # main function
│   └── startup.c              # Vector table, stack initialization & Reset Handler
├── STM32F411RE_FLASH.ld       # Linker script defining Flash/RAM memory regions
└── README.md                  # Project documentation
```
****
## Hardware using
- in this project, i using ***NUCLEO-F411RE (STM32F411RET6)*** like a main microcontroller.
- A keypad 4x4 
- Debugger: On-board ST-LINK/V2-1 via Mini-USB cable.

****
## Software using
- IDE: STM32CubeIDE
- Compiler Toolchain: Integrated GNU Arm Embedded Toolchain.
****
## Hand-on Practice
1. Identifying the Required Register Addresses
- There are 5 register addresses that we need to identify, include:

