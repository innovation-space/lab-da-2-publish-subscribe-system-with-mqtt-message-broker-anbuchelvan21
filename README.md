AnbuChelvan S
22MID0312

Smart Campus Monitoring using MQTT and Node-RED
Objective
To design and implement a publish–subscribe system using MQTT Broker and Node-RED.

MQTT Broker
test.mosquitto.org (Port 1883)

Publishers
campus/temperature (QoS 1)
campus/Humidity (QoS 2)

Wildcard Subscriber
Subscribed using: campus/+

Status Topic
campus/status
Retained message enabled to store latest system state.

QoS Demonstration
QoS 1 → Repeated every 5 seconds
QoS 2 → Repeated every 5 seconds

Dashboard
Temperature Gauge
Humidity Line Chart
System Status Display
Conclusion
This project demonstrates MQTT publish–subscribe architecture with QoS levels, wildcard subscriptions, retained messages, and live dashboard visualization.
