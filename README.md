# Blinking LED with Arduino Nano 💡🔁

A simple Arduino Nano project that blinks an LED (built-in **L LED** on **D13** or an external LED). Great for beginners who want to learn Arduino basics 🚀

---

## Features ✅
- Blinks the Arduino Nano built-in LED (pin **D13**) ✨
- Works with an external LED too 🔌
- Super easy to upload and run 🧠

---

## Requirements 🧰
- Arduino Nano 🟦
- USB cable 🔌
- (Optional) LED 💡
- (Optional) 220Ω–330Ω resistor 🎛️
- (Optional) Breadboard + jumper wires 🧩

---

## Wiring 🔧 (Optional External LED)
If you want to use an external LED:
- **D13 → Resistor (220Ω–330Ω) → LED (+)**
- **LED (–) → GND**

⚠️ Make sure the LED direction is correct (long leg = +).

---

## How to Upload 🚀
1. Open **Arduino IDE** 💻
2. Connect the Arduino Nano via USB 🔌
3. Go to **Tools → Board → Arduino Nano**
4. Select the correct **Port** ✅
5. Open `blinking.ino` 📄
6. Click **Upload** ⬆️

If upload fails on clone boards, try:
- **Tools → Processor → ATmega328P (Old Bootloader)** 🛠️

---

## Code Explanation 🧾
- `pinMode(LED_PIN, OUTPUT);` → sets the pin as output 📤  
- `digitalWrite(LED_PIN, HIGH);` → LED ON 💡  
- `digitalWrite(LED_PIN, LOW);` → LED OFF 🌑  
- `delay(1000);` → waits 1 second ⏳  

---

## Pictures / Demo 📸
![Project](https://github.com/user-attachments/assets/11816832-991c-4fbb-b904-a1e09e8fb8b6)


### Video 🎥
Project Video:
**[Video](https://github.com/touhidulislam1999/LED-Blinking-with-ARDUINO-Nano/blob/main/IMG_3597.mov)**


---

## Author 👤
Touhidul Islam 🇧🇩  
GitHub: https://github.com/touhidulislam1999
