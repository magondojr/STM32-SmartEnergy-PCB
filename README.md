# 🔋 Smart Energy Management System (SEMS)  
**Designed & Developed by: Tadiwa Magondo**  

## 🚀 Project Overview  
The **Smart Energy Management System (SEMS)** is an **IoT-driven embedded solution** designed to optimize **energy usage, reduce costs, and improve grid efficiency**. It integrates **solar power, utility grids, and smart automation** to enable seamless **real-time energy monitoring and remote control**.  

This project showcases my expertise in:  
✅ **Embedded Systems Development (STM32, ESP8266, FreeRTOS)**  
✅ **PCB Design & Hardware Integration (EasyEDA, Altium, KiCad)**  
✅ **IoT Communication (MQTT, MODBUS, RS485, CAN Bus)**  
✅ **Energy Analytics & Optimization (AI-driven load balancing)**  
✅ **Cloud & Mobile Integration (Google Home, AWS IoT, Blynk, React Native)**  

## 🎯 Real-World Problem Solved  
In Southern Africa, **power outages, load shedding, and inefficient energy use** increase operational costs for businesses and households. **SEMS provides:**  
- **Automated power switching** between grid, solar, and battery.  
- **Data-driven energy optimization** to prevent power wastage.  
- **Predictive maintenance** using AI to forecast energy demand.  

---

## 🛠️ **Technical Breakdown**  

### **1️⃣ Hardware & PCB Design**  
| Component  | Description |
|------------|------------|
| **Microcontroller** | STM32F407VGT6 (ARM Cortex-M4) |
| **Wireless Communication** | ESP8266 (WiFi) |
| **Energy Metering** | ADE7758 / ATM90E36 |
| **Voltage & Current Sensors** | ZMPT101B, ACS712 |
| **Communication Interfaces** | RS485 (MAX485), CAN Bus (SN65HVD230D) |
| **Power Management** | LM2596S-12, TPS54200DDCT |

💡 *Designed a multi-layer PCB in EasyEDA for efficient power management & noise reduction.*  

### **2️⃣ Firmware & Embedded Software**  
- **Developed firmware using C & FreeRTOS** (Real-Time Task Scheduling).  
- **Optimized ADC & DMA for energy readings** (10-bit precision).  
- **Implemented IoT communication protocols** (MQTT for real-time updates).  
- **Integrated MODBUS RTU over RS485** for industrial sensor support.  

### **3️⃣ IoT Cloud & Web/Mobile Development**  
- **IoT Platforms:** Home Assistant, AWS IoT, Blynk.  
- **Web Dashboard:** Built with **Node.js, React.js** for energy analytics.  
- **Mobile App:** Developed in **React Native** for remote control.  

---

## 📡 **Communication & Protocols**  
- **WiFi (ESP8266):** Cloud connectivity.  
- **RS485 (MODBUS):** Industrial energy metering.  
- **CAN Bus:** Sensor board communication.  
- **MQTT:** Secure energy data transmission.  

---

## 🚀 **How It Works (Step-by-Step)**  

### **1️⃣ Hardware Setup**  
1. Connect STM32F407VGT6 to ESP8266 & energy sensors.  
2. Power the system using **12V DC with regulated outputs**.  
3. Connect **ADE7758 energy meter** via **SPI/UART**.  

### **2️⃣ Firmware Deployment**  
1. Install **STM32CubeIDE**.  
2. Clone the firmware repository:  
   ```bash
   git clone https://github.com/yourusername/SEMS.git
   cd SEMS/Firmware
