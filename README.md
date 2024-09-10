# Advanced Classification Radar

## Overview
This project aims to develop an AI-powered radar system capable of detecting, classifying, and tracking objects behind walls in real-time. The system utilizes a radar sensor and microcontroller, coupled with machine learning algorithms for object classification, and integrates this into an interactive user interface (UI) for real-time data visualization and control.

---

## Hardware Setup
- **Radar Sensor**: BGT24MTR11 ($13) Might need to spend more for gator detection
- **Microcontroller**: Raspberry Pi

### Steps:
1. 

---

## Data Collection & Preprocessing
- **Data Collection**: Capture radar reflection data from objects behind walls.
- **Preprocessing**:
  - Filter out noise.
  - Extract relevant features.

---

## Model Development
- **Objective**: Train a machine learning model to classify objects and movements based on the radar data.
  
### Steps:
1. **Choose Model**: Train or fine-tune a model using a **Convolutional Neural Network (CNN)** or **decision trees**.
2. **Training**: Use the preprocessed data to train the model.
3. **Validation/Testing**: Validate and test the model to ensure it accurately classifies objects.

---

## Integration
- Integrate the trained model with the hardware to enable **real-time detection** and classification of objects.
- Ensure smooth communication between the radar sensor, microcontroller, and model for continuous data processing.

---

## User Interface (UI)

### Real-Time Object Detection Display:
- **2D or 3D Visualization**: Display a real-time map of detected objects behind walls.
  - Objects are represented by icons (e.g., human, pet, furniture) based on the AI classification.
- **Distance & Location Info**: Show the approximate distance and location of each detected object relative to the radar sensor.
- **Movement Tracking**: Visualize real-time object movements with directional arrows to show speed and movement paths.

### Object Classification:
- **Labels**: Assign labels to each detected object (e.g., human, pet) based on the classification model.
- **Confidence Scores**: Display the AI's confidence level for each classification (e.g., 90% sure it's a human).

### Signal Strength Visualization:
- **Heatmap or Signal Intensity Graph**: Provide a visual representation of signal strength across different areas to help users understand the system's effectiveness through walls.
  - Useful for identifying weak areas or interference in the detection process.

### Control & Calibration Options:
- **Sensitivity Controls**: Adjust system sensitivity to detect smaller or more distant objects.
- **Environment Selection**: Calibrate the system for different wall types and materials (e.g., drywall, concrete).
- **Signal Type Settings**: For systems with multiple signal types (e.g., radar frequencies), allow users to switch between or optimize the signal.

### Alerts & Notifications:
- **Motion Alerts**: Notify the user when unexpected movement is detected.
- **Custom Triggers**: Let users set specific conditions, such as alerts when a human is detected behind a wall.

### Data Logging:
- **History Tracking**: Log detected object data over time for later review or analysis.
  - Useful for long-term monitoring applications, such as security or wildlife tracking.

--- 

## Technologies Used
- **Radar Sensor**: BGT24MTR11
- **Microcontroller**: Raspberry Pi
- **Programming Languages**: Python, JavaScript (for UI)
- **Machine Learning Libraries**: TensorFlow
- **UI Tools**: Tkinter, PyQt (Python) or React (JavaScript)

---

## Goals
- Detect and classify objects in real-time through walls using radar and AI.
- Provide a user-friendly interface for visualization and control.
- Maybe integrate with gators if possible.
