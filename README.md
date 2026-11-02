<div align="center">

# Hi, I'm Cédric 👋

<a href="https://github.com/itsaxelc">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3500&pause=1200&color=58A6FF&center=true&vCenter=true&width=700&lines=Aerospace+Engineering+Student;Real-Time+Embedded+Systems;RTOS+Kernel+%7C+Flight+Control+%7C+Avionics" alt="Typing SVG" />
</a>

</div>

I'm a final-year engineering student at **ENSA Safi, Morocco**, specializing in Aeronautical Engineering and Space Technologies.

My interests lie at the intersection of **avionics, real-time embedded systems, and flight control**, with a focus on reliable low-level software and autonomous aerial systems.

- 🔭 Building an RTOS kernel from scratch and bare-metal STM32 drivers.
- ✈️ Interested in flight dynamics, control laws, UAVs, and avionics.
- ⚙️ Exploring real-time systems, microcontroller architecture, and hardware interfaces.
- 🎯 **Seeking a 4–6 month internship starting in February 2027** in embedded systems.

---

## 💼 Experience

### Embedded Systems Intern — RTOS Kernel Team Lead
**SPACEBORN Pvt. Ltd.** · Remote (Chennai, India) · *July 2026 – September 2026*

- Led a team of **4 interns** developing an RTOS kernel from scratch for ARM Cortex-M4/M7, supporting up to **20 tasks** with a **513-cycle (6.4 µs @ 80 MHz)** context switch.
- Implemented scheduling, inter-task communication, synchronization, stack management, watchdog, and fault handling.
- Validated the kernel with **40+ unit and integration tests** on target hardware (latency, race conditions, priority inheritance). Full test firmware (kernel + HAL + tests) fits in **24 KB of Flash**.
- Coordinated software interfaces with the FSM, Control Logic, and Sensor Stack teams.
- Applied deterministic design, robustness, and **MISRA C** practices.

**Stack:** C, ARM Cortex-M4/M7, STM32, ARM GCC/GDB, CMake, OpenOCD, Ninja, Git, MISRA C

### Aircraft Maintenance Intern
**Air Burkina SA** · Ouagadougou, Burkina Faso · *July 2025 – August 2025*

- Assisted technicians with **Boeing 737** maintenance: lighting inspections, minor repairs, engine servicing.
- Helped repair a hydraulic leak during overnight maintenance to minimize aircraft-on-ground (AOG) time.

---

## 🎓 Education

### Engineering Degree — Aerospace Engineering
**Cadi Ayyad University, ENSA Safi** · *2024 – Present*
🏅 High Honors (Years 1–2)
*Embedded Systems, Electronics, Aerodynamics & Flight Mechanics, Aircraft Electrical Systems and Control*

### Preparatory Engineering Program — Sciences and Technologies
**Mohammed 1st University, ENSA Oujda** · *2022 – 2024*
🏅 High Honors 
*Analog Electronics, Algorithms, C Programming, MATLAB, Mathematics for Physics*

---

## 🧰 Tech Stack

**Languages**

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)

**Embedded & RTOS**

![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![ARM Cortex-M](https://img.shields.io/badge/ARM%20Cortex--M4%2FM7-0091BD?style=for-the-badge&logo=arm&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-4EA64C?style=for-the-badge)
![Teensy](https://img.shields.io/badge/Teensy%204.1-E4003A?style=for-the-badge)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)

**Protocols**

![I2C](https://img.shields.io/badge/I%C2%B2C-555555?style=for-the-badge)
![SPI](https://img.shields.io/badge/SPI-555555?style=for-the-badge)
![UART](https://img.shields.io/badge/UART-555555?style=for-the-badge)
![CAN](https://img.shields.io/badge/CAN-555555?style=for-the-badge)

**Toolchain & Debug**

![GCC](https://img.shields.io/badge/GCC-A42E2B?style=for-the-badge&logo=gnu&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Ninja](https://img.shields.io/badge/Ninja-000000?style=for-the-badge)
![GDB](https://img.shields.io/badge/GDB-A42E2B?style=for-the-badge&logo=gnu&logoColor=white)
![OpenOCD](https://img.shields.io/badge/OpenOCD-555555?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?style=for-the-badge&logo=platformio&logoColor=white)

**Control & Design**

![PID](https://img.shields.io/badge/PID%20%2F%20MPC-6E40C9?style=for-the-badge)
![MPC](https://img.shields.io/badge/PID%20%2F%20MPC-6E40C9?style=for-the-badge)
![Kalman](https://img.shields.io/badge/Kalman%20Filter-6E40C9?style=for-the-badge)
![Proteus](https://img.shields.io/badge/Proteus-0A5EA8?style=for-the-badge)

**AI & Vision**

![TensorFlow](https://img.shields.io/badge/TensorFlow%20Lite-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

---

## 🚀 Featured Projects

### 1. Real-Time Operating System — ARM Cortex-M
Kernel for ARM Cortex-M4/M7 focused on deterministic execution (built during my Spaceborn internship).

- Task scheduling and context switching (513 cycles, 6.4 µs @ 80 MHz)
- Inter-process communication and synchronization, priority inheritance
- Stack management and watchdog mechanisms
- Fault handling, 40+ on-target tests

**Technologies:** C, ARM Cortex-M, GCC, GDB, CMake, OpenOCD, MISRA C

### 2. Fixed-Wing VTOL UAV — Flight Control and Integration
- Designed a **950 mm wingspan, 1.2 kg** VTOL UAV in SolidWorks: fuselage, NACA 4415 wings, tilt mechanism
- Cascaded PID at **2 kHz** with adaptive hover-to-cruise transition on Teensy 4.1
- MPU-9250 inertial measurements with Madgwick attitude estimation

**Technologies:** Embedded C/C++, Teensy 4.1, MPU-9250, PID, Madgwick filter, SolidWorks

### 3. Quadcopter Drone — Embedded Flight Control
- Embedded C on STM32L476 with STM32CubeMX and a CMake-based build
- Register-level SPI/I²C drivers for IMU and environmental sensors
- Software structured around sensor acquisition, attitude estimation, and real-time flight control

**Technologies:** STM32L476, Embedded C, SPI, I²C, CMake, GCC, Ninja

### 4. Bare-Metal STM32 Drivers
Peripheral drivers written directly against memory maps, registers, and reference manuals.

- I²C and SPI drivers, SD card communication experiments
- MPU-9250 and AK8963 sensor interfacing
- Register-level configuration and status/error handling

**Technologies:** C, STM32, ARM Cortex-M, datasheets, reference manuals

### 5. Smart Pitot — Embedded Sensor System
- Multi-sensor system: Arduino Uno, 2× BMP280, 1× DHT22 over I²C
- Real-time computation of **6 flight parameters** with temperature compensation
- Validated in Proteus, with bilingual technical documentation

**Technologies:** Arduino, Embedded C/C++, BMP280, DHT22, I²C multiplexer, Proteus

---

## 📚 Current Learning Focus

- DMA architecture and peripheral data transfers
- Reliable, MISRA-compliant embedded software design
- Inertial sensing and attitude estimation
- Flight dynamics and advanced control strategies (MPC, EKF)

---

## 🗣️ Languages

English (B2) · French (C1)

---

## 💬 Words I Build By

> *"Simplicity is prerequisite for reliability."*
> — **Edsger W. Dijkstra**

> *"Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away."*
> — **Antoine de Saint-Exupéry**, aviator and writer

> *"Premature optimization is the root of all evil."*
> — **Donald Knuth**

> *"Osons inventer l'avenir."* (*"Let us dare to invent the future."*)
> — **Thomas Sankara**

---

## 🤝 Let's Connect

I'm interested in **aerospace research, flight dynamics and control, avionics, and real-time and safety-critical embedded software**.

- GitHub: [@itsaxelc](https://github.com/itsaxelc)
- LinkedIn: [Cédric Compaore](https://www.linkedin.com/in/cedriccompaore/)
- Email: compaorecedric123@gmail.com

---

*Developing reliable embedded software and control solutions for aerospace.*
