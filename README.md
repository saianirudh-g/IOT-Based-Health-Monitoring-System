# IOT-Based Health Monitoring System

## Overview
The Internet of Things (IoT) is a rapidly growing technology where smart objects and devices are connected to the internet for effective communication. This project aims to decrease the death rate by detecting chronic diseases such as cancer and heart diseases, and to reduce human-dependent healthcare. It utilizes networked sensor devices, either worn on the body or embedded in living environments, to gather rich information to evaluate a patient's physical and mental health[cite: 1]. The system records health-related information like blood pressure, body temperature, sugar levels, and breathing patterns, delivering this data to the concerned hospital or caretaker for further action.

## Hardware Components
The system's core block diagram includes the following components:
*   **Microcontroller**: Arduino
*   **Input Sensors**: Heartbeat Sensor, Temp Sensor, and Humidity sensor
*   **Output/Connectivity Modules**: LCD Display, Buzzer, and Wi-Fi Module

## Sensor Categories
Medical sensors and wearables used in this system are divided into two main categories:
*   **On-body Contact Sensors**:
    *   *Monitoring sensors*: Used for physiological behavior (ECG, EMG, EEG), chemical analysis (sweat, glucose, saliva), and optical measurements (Oximetry, tissue properties).
    *   *Therapeutic sensors*: Used for medication (drug delivery patches), stimulation (chronic pain relief), and emergency response (defibrillators).
*   **Peripheral Non-contact Sensors**:
    *   *Monitoring fitness*: Measure fitness via motion (physical activity, calorie count) and location tracking (GPS, indoor localization).
    *   *Behavioural monitoring*: Track activity (falls, sleep, exercise), emotion (anxiety, stress, depression), and diet (calorie intake, eating habits).

## System Architecture
The application scenario connects the patient to stakeholders through various networking layers:
1.  Wearable Sensors attached to the patient collect biological data.
2.  Data is transmitted to a local Gateway.
3.  Information is passed through Wireless or Cellular Networks to the Internet.
4.  Data is securely accessed by stakeholders, including Doctors, Smart Vehicles (ambulances), and caregivers.

## Applications
*   **Health Monitoring**: Captures vital signs like blood pressure, blood glucose, weight, ECG, heart rate, and body temperature to monitor pediatric and aged persons.
*   **Personal Fitness Monitoring**: Wearable sensors help track personal fitness programs.
*   **Chronic Disease Monitoring**: Predicts chronic conditions such as heart attacks ahead of time.
*   **Medication Monitoring**: Assists in tracking and managing medication intake.

## Limitations and Challenges
*   **Security & Privacy Issues**: Healthcare devices and applications capture private health data and are connected to the internet for anytime, anywhere access, which may attract hackers.
*   **Device Designing Issues**: IoT devices used in healthcare are tiny sensors that feature low computing power processors, low storage capacity, and limited battery power.
*   **Trust and Reliability**: Data generated and delivered by medical devices is prone to security attacks. Information might be infected or corrupted by malware during data transmission, leading caregivers to make incorrect life-and-death treatment decisions.

## Team and Institution
This project was developed at **VISHNU Universal Learning** by the following team members:
*   D. SAI SRINIVAS
*   E. HEMANTH
*   G. SWATHI
*   G. GOWRI SATISH
*   G. VARAPRASAD
*   G. RAVICHANDRA
*   G. SAIANIRUDH
*   G. SUDHAMAI

**Guided By**: Mr. K. N. S. Durga Prakash, M.Tech, (Ph. D), EEE Department VIT
