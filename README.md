# 🌐 Wemos D1 Mini – Connect to Wi-Fi

This repository contains sample code and instructions to connect a **Wemos D1 Mini (ESP8266)** to a Wi-Fi network. It’s a perfect starting point for Wi-Fi-based IoT projects like smart home systems, remote monitoring, and automation.

---

## 🚀 Features

- 📶 Connect Wemos to any 2.4GHz Wi-Fi network
- 🛠️ Minimal setup with Arduino IDE
- 🖥️ Serial output for debugging
- 🔌 Easy to expand for web servers, APIs, or cloud IoT platforms

---

## 🧰 Hardware Required

| Component         | Quantity |
|------------------|----------|
| Wemos D1 Mini    | 1        |
| Micro USB Cable  | 1        |
| Wi-Fi Router     | 1 (2.4GHz) |
| Arduino IDE      | Installed |

---

## 🧪 Software Setup

### 1. Install ESP8266 in Arduino IDE

- Open Arduino IDE.
- Go to `File` → `Preferences`.
- In the "Additional Board Manager URLs", add:
  - Go to `Tools` → `Board` → `Boards Manager`, search for **ESP8266** and click **Install**.

### 2. Select the Board

- Navigate to: `Tools` → `Board` → **LOLIN(Wemos) D1 R2 & Mini**

### 3. Install Required Libraries

- No additional libraries are required for basic Wi-Fi connection.

🔧 Troubleshooting

⚠️ Wemos only supports 2.4GHz Wi-Fi, not 5GHz.

🔌 Make sure USB cable supports data, not just charging.

🔁 Try resetting the board or restarting the router.

