![image](https://github.com/user-attachments/assets/acb1e754-d911-4132-921f-f3a278c94dcf)

 
 Arduino Pocket PC with OLED HACK_UPDT
===============================

This project turns an Arduino into a mini multifunctional pocket PC using a 0.96 inch SSD1306 OLED display. Inspired by VOLOS PROJECTS, this custom version features a normal calculator, a mini arcade game, stopwatch, calendar, phonebook, and a buzzer sound system — all operated with just three buttons and a potentiometer.

   FEATURES
  =========================
- Basic Calculator – Simple arithmetic calculations with a button-based interface.
- Mini Game – Ball-and-paddle arcade gameplay with block enemies.
- Stopwatch – Track time with start/stop/reset options.
- Calendar – View the date and navigate through months.
- Phonebook – Store and scroll through basic contact info.
- Buzzer – Sound feedback using digital pin 9.


HARDWARE REQUIREMENTS
  =========================
- Arduino UNO or compatible board
- 0.96 inch SSD1306 OLED display (I2C interface)
- 3 Push buttons
- 1 Potentiometer (connected to A0)
- 1 Buzzer (connected to digital pin 9)
- Breadboard or custom PCB

![image](https://github.com/user-attachments/assets/e1cf1c99-66b7-4a5c-8aa3-553b1ed43d6c)

Buttons:
--------
- UP button     → Digital pin 4
- DOWN button   → Digital pin 5
- SELECT button → Digital pin 6

Potentiometer:
--------------
- Middle pin → A0
- Side pins  → GND and 5V

Buzzer:
-------
- Signal     → Digital pin 9
- Other pin  → GND

OLED Display (I2C):
-------------------
- SDA  → A4
- SCL  → A5
- VCC  → 5V
- GND  → GND


INSTALLATION
=====================
1. Open 'OledPC.ino' in the Arduino IDE.
2. Ensure the following libraries are installed:
   - Adafruit_GFX
   - Adafruit_SSD1306
3. Upload the code to your Arduino board.
4. Use the buttons and potentiometer to navigate and interact with the interface.


CREDITS
===================
Original idea and inspiration by VOLOS PROJECTS.
Check them out on YouTube for more amazing electronics projects.
