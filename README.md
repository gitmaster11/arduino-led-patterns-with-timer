# Arduino Timer1 LED Toggle

This project demonstrates how to control multiple LEDs using **Timer1 interrupts**
in **CTC mode** without using `delay()`.

## 🚀 Features
- Timer1 interrupt every 1 second
- Non-blocking LED control
- LED toggle logic
- Clean and beginner-friendly embedded structure

## 🧠 Concepts Used
- Timer1 (CTC mode)
- Interrupt Service Routine (ISR)
- GPIO control
- Toggle logic using `digitalRead()`

## 🔧 Hardware
- Arduino Uno / Nano
- 3 LEDs
- 3x 220Ω resistors

## ⏱ Behavior
- LED1 toggles at 1 second
- LED2 toggles at 2 seconds
- LED3 toggles at 3 seconds
- Cycle repeats continuously

## 📂 Files
- `timer_led_toggle.ino` – main Arduino source code

## 📌 Author
Bekmurod360
