# Sleep Tracker with Arduino Uno & Grove RGB LCD

This project is a simple **Sleep Tracker** built using an Arduino Uno, a Grove RGB LCD display, and additional Grove components like a touchpad and button. The system tracks sleep cycles and displays the time, with a user-friendly interface using the LCD.

## Features
- Track sleep time with real-time clock updates.
- Visual display of time in hours, minutes, and seconds.
- Modes for day and night with adjustable background color.
- User interaction through a button and touchpad for starting/stopping the timer.

## Components
- **Arduino Uno**
- **Grove RGB LCD Display**
- **Grove Touchpad**
- **Grove Button**
- **Wires and connectors**

## Setup Instructions
1. Connect the Grove RGB LCD to the I2C port on the Grove Shield.
2. Attach the touchpad to digital pin **D2** and the button to digital pin **D3**.
3. Upload the code from `sleep_tracker.ino` to the Arduino Uno using the Arduino IDE.
4. Power the Arduino and observe the LCD display for tracking sleep time.

## Usage
- The LCD will show a welcome message initially.
- Use the **touchpad** to start and interact with the timer.
- Press the **button** to reset or navigate through time settings.
- The display color changes to indicate different modes (e.g., sleep mode with dark purple background).

## Libraries Required
- **Wire.h** for I2C communication.
- **rgb_lcd.h** for controlling the Grove LCD.
- **TimeLib.h** for handling time calculations.
