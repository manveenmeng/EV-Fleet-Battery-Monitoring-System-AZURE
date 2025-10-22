# EV-Fleet-Battery-Monitoring-System-AZURE
Real-time battery management system for electric vehicle fleets using Azure IoT Hub and Azure Storage.



## 🚗 Project Overview

An enterprise-level IoT system that monitors battery health across a fleet of electric vehicles in real-time. Built for automotive manufacturing environments like Stellantis Windsor Assembly Plant.

## ✨ Features

- **Real-Time Monitoring**: Track 10+ vehicles simultaneously
- **Battery Analytics**: SOC, SOH, voltage, current, temperature monitoring
- **Predictive Alerts**: Automatic anomaly detection
- **Cloud Integration**: Azure IoT Hub + Azure Table Storage
- **Professional Dashboard**: Live web-based fleet management interface

## 🏗️ Architecture
EV Vehicle Simulators
↓
Azure IoT Hub (Cloud)
↓
Azure Table Storage (Cloud)
↓
Flask Web Dashboard



## 🛠️ Technologies Used

- **Cloud Platform**: Microsoft Azure
  - Azure IoT Hub (Device messaging)
  - Azure Table Storage (Data persistence)
- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **IoT**: Azure IoT SDK

## 📊 Key Metrics

- Monitors 10 electric vehicles
- Real-time telemetry every 10 seconds
- Automatic anomaly detection
- Fleet-wide health analytics

## 🚀 Setup Instructions

### Prerequisites
- Python 3.8+
- Azure Account (Free tier works!)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/manveenmeng/EV-Fleet-Battery-Monitoring-System-AZURE

