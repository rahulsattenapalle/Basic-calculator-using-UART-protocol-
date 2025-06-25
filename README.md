# Basic Calculator Using UART Protocol

## Project Overview:
This project implements a simple calculator using UART communication. The user sends arithmetic expressions (e.g., 6+2 or 9*3) from a serial terminal. The LPC2129 microcontroller receives this input over UART, parses the expression, performs the calculation, and sends back the result via UART.

## Working Principle:
- User sends a string like "8+2" through UART.
- The microcontroller reads characters via serial input.
- It identifies the operator and operands.
- Performs the arithmetic operation.
- Sends the result back to the serial terminal.

## Components Used:
- LPC2129 Microcontroller
- MAX232 IC (for UART level shifting)
- RS232 Cable / USB-to-Serial Converter
- Serial Terminal Software (like Tera Term or PuTTY)
- Power Supply

## Technologies Used:
- Embedded C (Keil µVision)
- UART Communication (9600 baud)
- Flash Magic (for burning code)

## Features:
- Supports +, -, *, /
- Command-based input/output via UART
- Real-time serial interaction

## Future Scope:
- Add multi-digit support
- Include error handling and floating-point math
- Expand to scientific calculator functions

---

**Project Developed By:**  
**Rahul Sattenapalle**
