This project celebrates the **95th Saudi National Day** 🎉 by displaying a custom animation on a **128x64 SSD1306 OLED display** using an **ESP8266 (ESP-12E / NodeMCU)**, a breadboard, and jumper wires.
![OLED Animation Demo](images/ScreenShot.png)

---

# Features
- Plays a National Day animation on the OLED screen.
- Simple hardware: ESP8266 + OLED + breadboard + jumper wires.
- Custom frames converted from images to simulate a GIF-like animation.
- Adjustable frame delay to control animation speed.

---

# Hardware Used
- **ESP8266 NodeMCU (ESP-12E)**
- **SSD1306 OLED Display (128x64, I²C)**
- **Breadboard**
- **Jumper Wires**

---

# Wiring

| OLED Pin | ESP8266 Pin |
|----------|-------------|
| VCC      | 3.3V        |
| GND      | GND         |
| SDA      | D2 (GPIO4)  |
| SCL      | D1 (GPIO5)  |

⚠️ The ESP8266 is **3.3V only** → connect OLED VCC to **3.3V**, not 5V.
