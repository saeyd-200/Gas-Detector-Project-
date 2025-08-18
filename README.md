MQ-2 Gas Detector with Arduino UNO

This project uses the MQ-2 gas sensor with an Arduino UNO to detect flammable gases (LPG, butane, propane, methane, alcohol, smoke) and trigger an alarm using a buzzer. Both analog and digital outputs of the sensor are used for demonstration.

Features

Reads analog values from MQ-2 (gas concentration level).

Reads digital values from MQ-2 (threshold detection via onboard potentiometer).

Activates a buzzer alarm when gas concentration exceeds safe level.

Prints live sensor data and status on Serial Monitor.

Components Used

# Arduino UNO

# MQ-2 Gas Sensor

# Active Buzzer (5V)

# Jumper wires

# Breadboard

How It Works

MQ-2 continuously senses the air for gases.

The analog pin (A0) outputs a value proportional to the gas concentration.

The digital pin (D2) outputs HIGH/LOW based on the preset threshold (set using onboard potentiometer).

If either analog threshold is crossed or digital pin indicates gas, the buzzer activates.

Serial Monitor shows live readings and status updates.

Applications

LPG gas leakage alarm

Smoke detector

Alcohol detection

Fire safety systems
