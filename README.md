# AI Camera School Zone Safety Assistant

## Overview
This project utilizes AI cameras to enhance safety in school zones by controlling traffic signals and pedestrian barriers.
![Instant noodle water level sensor device for the visually impaired](https://raw.githubusercontent.com/felixkim0719/ai_camera/main/public/picture.jpg)

## Key Features
1. AI Camera-based Central Line Traffic Light Control
   - Detects pedestrians in the school zone
   - Changes central line LED signals based on pedestrian presence

2. Automatic Crosswalk Safety Barrier Control
   - Synchronizes with crosswalk traffic lights
   - Controls safety barriers to manage pedestrian and vehicle movement
   - Integration of AI camera with crosswalk barrier control
   - 
## Components
- AI Camera: HuskyLens Pro
- Central Line Signal: Neopixel LED
- Crosswalk Signals: Green and Red LEDs
- Safety Barrier: Servo Motor
- Control System: Arduino Uno

## How It Works
1. The AI camera detects pedestrians in the school zone.
2. If pedestrians are present, the central line LED turns red; otherwise, it remains yellow.
3. Crosswalk signals control the safety barriers:
   - Red light: Barrier blocks pedestrian movement
   - Green light: Barrier blocks vehicle movement

## Expected Benefits
- Reduces accident risks between pedestrians and vehicles in school zones
- Enhances driver awareness of pedestrian presence
- Provides 24/7 school zone safety without human traffic guards
- Cost-effective compared to potential accident damages

## Challenges Overcome
- Switched from ESP32-CAM to HuskyLens Pro for improved recognition and offline functionality
- Resolved system instability by using two Arduino boards instead of one

## Contact
For more information or collaboration proposals, please contact [felixkim0719@gmail.com].
