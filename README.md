💡 Raspberry Pi LED Control using GPIOZero

This project demonstrates basic LED control using Python and the GPIOZero library on a Raspberry Pi. It covers simple blinking, brightness control using PWM, and button-controlled LED operation.

📌 Overview

The program uses the gpiozero library to interface with GPIO pins on the Raspberry Pi. An LED is connected to GPIO pin 17, and in the final example, a button is connected to GPIO pin 2. The project showcases three different ways to control an LED:

Basic blinking

PWM brightness control

Button-controlled LED operation

🔹 Features
1️⃣ Basic LED Blinking

Turns the LED ON for 1 second

Turns the LED OFF for 1 second

Repeats continuously

2️⃣ PWM LED Brightness Control

Uses PWMLED to control brightness levels

OFF (0)

Half brightness (0.5)

Full brightness (1)

Each state lasts 1 second

3️⃣ Button Controlled LED

LED turns ON when button is pressed

LED turns OFF when button is released

Uses event-driven programming

🛠️ Hardware Requirements

Raspberry Pi

LED

220Ω resistor

Push button (for third example)

Breadboard & jumper wires

⚙️ Technologies Used

Python

GPIOZero library

Raspberry Pi GPIO pins

🎯 Learning Outcomes

Understanding GPIO pin control

Implementing PWM for brightness control

Using input devices (button) with event handling

Building basic embedded systems projects# LED-ON-
