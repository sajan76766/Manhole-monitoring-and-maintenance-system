#  Smart Anti-Overflow Manhole System with Flow Diversion and Blockage Management using Real-Time IoT
# Overview
 The project outlines a smart manhole monitoring and overflow prevention system for
 urban flood management. This system design integrates real-time sensors, machine
 learning, and hydraulics to identify, predict, and prevent manhole overflows. The
 system architecture comprises flow, depth, pressure, and turbidity sensors, which are
 real and replica nodes designed for blocked system robustness testing. Sensor data is
 sent to a cloud dual-layer machine learning system and is analyzed for trend detection
 and flood risk prediction. This is accomplished using a Heltec ESP32 LoRa-based hub.
 To as we see in the case of cloud outages which are a common feature of severe
 weather the network also includes a local AIML module as a part of the hub. This
 edge fallback system does trust scoring, sensor fusion, anomaly detection, and short term
 forecasting which in turn enables autonomous operation during disconnections. We use
 solenoid valves which the hub controls for dynamic flow diversion which in turn prevents
 overflows. The solution is scalable, cost effective and puts into play in today’s smart city
 infrastructure.
# Purpose
 This project is to develop what we have designed as a smart and reliable manhole
 monitoring system which is to identify and put an end to urban flooding caused by
 manhole overflows. We are to use IoT sensors, real time data analysis, and machine
 learning to do early detection of blockages and which in turn will enable us to do
 automatic flow diversion thus which in turn reduces infrastructure damage, traffic
 disruptions and public health risks. Also we are to present a cost effective, scalable and
 resilient solution which will run continuously even during network failures which makes
 it a perfect fit for modern smart city infrastructure.
