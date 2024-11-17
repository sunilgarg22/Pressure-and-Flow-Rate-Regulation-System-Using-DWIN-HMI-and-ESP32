# Data Regulation and Monitoring System Using DWIN HMI Display and ESP32
This repository contains the source code and implementation details for a medical monitoring system that utilizes the **DWIN HMI Display** and **ESP32 microcontroller** to regulate and display pressure and flow-rate data. The system also includes features for managing irrigation data and maintaining patient records, making it an efficient solution for medical applications.  

## Features  

- **Pressure and Flow-Rate Monitoring**: Real-time monitoring and display of pressure and flow-rate data using DWIN HMI.  
- **Irrigation Management**: Tracks and regulates irrigation pressure and flow-rate for medical or healthcare purposes.  
- **Patient Data Records**: A simple interface to input, display, and store patient-related data securely.  
- **ESP32 Integration**: Uses ESP32 for data processing and communication with peripheral sensors and devices.  
- **User-Friendly Interface**: DWIN HMI provides an intuitive and customizable graphical interface for seamless operation.  

## Project Components  

### Hardware  
1. **DWIN HMI Display**  
   - Provides a graphical interface for real-time monitoring and data input.  
2. **ESP32 Microcontroller**  
   - Handles sensor data acquisition, processing, and communication with the display.  
3. **Sensors**  
   - Pressure and flow-rate sensors for monitoring.  

### Software  
- **Programming Language**: C/C++ (Arduino Framework for ESP32)  
- **Libraries Used**:  
  - `DWIN` library for HMI integration  
  - `ESP32` libraries for sensor communication and data processing  

## How It Works  

1. **Data Acquisition**: Sensors collect pressure and flow-rate data, which are processed by the ESP32.  
2. **HMI Display**: The processed data is sent to the DWIN HMI display for real-time visualization and user interaction.  
3. **Irrigation Control**: The system regulates irrigation parameters based on sensor input.  
4. **Patient Record Management**: The interface allows users to input and retrieve patient data directly on the HMI.  

## Getting Started  

### Prerequisites  
- **Hardware Setup**:  
  - Connect sensors to the ESP32.  
  - Interface the DWIN HMI display with the ESP32 using UART communication.  
- **Software Requirements**:  
  - Arduino IDE with ESP32 board package installed.  
  - Required libraries (install via Arduino Library Manager):  
    - `TFT_eSPI` for display  
    - `Wire` for sensor communication  

### Installation  

1. **Upload Code to ESP32**:  
   - Open the project in Arduino IDE.  
   - Configure the serial port and board settings for ESP32.  
   - Upload the code.  

2. **Connect Hardware**:  
   - Assemble the ESP32, sensors, and DWIN display as per the circuit diagram.  

3. **Run the System**:  
   - Power up the hardware and interact with the HMI interface for real-time data monitoring.  

## Usage  

- **Monitoring**: Visualize real-time pressure and flow-rate data on the DWIN HMI display.  
- **Irrigation**: Adjust and control irrigation settings via the display interface.  
- **Patient Data**: Add and manage patient records through the graphical interface.  

## Circuit Diagram  

![image](https://github.com/user-attachments/assets/7256b1e9-1cf1-4847-a3bf-5d13a6bffa2d)
  
![image](https://github.com/user-attachments/assets/b6deccde-a566-4317-936e-b075aab322cc)
 
