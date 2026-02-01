# IOT-Based-Vehicle-Health-Monitoring-and-Driver-Alert-System
Smart Vehicle Health Monitoring System monitors real-time vehicle parameters using STM32 and ESP32. Sensors measure temperature, vibration, and fuel level. Data is transmitted over CAN, displayed on LCD, and uploaded to AWS cloud for remote monitoring, fault detection, and future predictive maintenance. Designed for automotive applications.

Project Overview

The Smart Vehicle Health Monitoring System is an embedded automotive system designed to monitor critical vehicle parameters such as engine temperature, vibration, fuel level, and driver touch status in real time.
The system uses CAN communication to transmit sensor data between controllers and uploads vehicle health data to the AWS cloud for remote monitoring.

This project demonstrates automotive-grade communication, embedded firmware design, and cloud integration, making it suitable for core embedded / automotive job profiles.

Objectives

Monitor real-time vehicle health parameters

Detect abnormal engine conditions early

Use CAN protocol for reliable automotive communication

Display data locally on LCD

Upload vehicle data to cloud (AWS) for remote access

Design a scalable architecture for future automotive features

System Architecture

The system is divided into two embedded nodes connected via CAN bus:

🔹 Node 1 – Vehicle Sensor Node

Controller: STM32F407VGT6

Collects sensor data

Sends data over CAN bus

🔹 Node 2 – Gateway & Cloud Node

Controller: ESP32

Receives CAN data

Displays data on LCD

Sends data to AWS cloud via Wi-Fi
