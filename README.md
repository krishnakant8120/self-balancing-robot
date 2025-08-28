# 🤖 Self-Balancing Robot

A two-wheeled **self-balancing robot** built using **Arduino Nano, MPU6050 sensor, NEMA 17 stepper motors, A4988 motor drivers, and a PID control algorithm**.  
The robot maintains balance in real time and can be controlled wirelessly with an **HC-05 Bluetooth module** and a smartphone.  

---

## 📂 Repository Structure
- **docs/** → Report and documentation  
- **src/** → Arduino source code (PID control, sensors, motors)  
- **circuit/** → Circuit diagram and wiring connections  
- **hardware/** → Mechanical frame design and component details  
- **README.md** → Project documentation  
- **LICENSE** → Open-source license (MIT)  

---

## ⚙️ Components Used
- Arduino Nano  
- MPU6050 Gyro + Accelerometer  
- NEMA 17 Stepper Motors × 2  
- A4988 Stepper Drivers × 2  
- HC-05 Bluetooth Module  
- LiPo Battery 2200mAh  
- MDF Board, Threaded Rods, Nuts & Bolts  

---

## 🛠️ Working Principle
1. **Sensor Input** → MPU6050 measures tilt angle & angular velocity  
2. **Controller** → Arduino Nano processes sensor data using PID algorithm  
3. **Motor Control** → A4988 drivers move NEMA 17 motors to maintain balance  
4. **Remote Control** → HC-05 enables smartphone-based wireless control  

---

## 🚀 How to Run
1. Assemble hardware (frame, motors, electronics) as per circuit diagram  
2. Connect MPU6050, A4988 drivers, motors, and HC-05 module to Arduino Nano  
3. Upload Arduino sketch (`src/main.ino`) using Arduino IDE  
4. Pair HC-05 with smartphone and control via a Bluetooth app  
5. Tune PID parameters in code for stable balancing  

---

## 📊 Applications
- Robotics education & projects  
- Control systems and mechatronics demonstration  
- Autonomous self-balancing systems  
- Assistive robotics research  

---

## 📜 License
This project is released under the **MIT License**.  

---

## 👥 Authors
- Anushka Singh  
- Krishnakant Lodhi  
- Gyanendra Singh  
