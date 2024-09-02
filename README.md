## Bearing Fault Detection Using CWRU Bearing Dataset
### Overview

This project focuses on developing a machine learning model to detect bearing faults using the CWRU Bearing Dataset. The dataset consists of vibration measurements collected from normal bearings and bearings with different types of single-point defects. The goal is to create a predictive model that can accurately classify bearing conditions based on extracted features from vibration data, thus facilitating early fault detection and preventive maintenance in industrial machinery.
### Dataset

The CWRU Bearing Dataset provides vibration data collected at different sampling rates (12,000 and 48,000 samples per second) and under various motor load conditions. For this project, a subset of data recorded at 48,000 samples per second under a constant 1 horsepower external load was used. The dataset includes both normal bearings and bearings with faults on the inner race (IR), outer race (OR), and ball, with varying severity levels.

### Data Details
- Sampling Rate: 48 kHz
- Fault Types: Inner Race (IR), Outer Race (OR), Ball
- Fault Severity Levels: 0.007 inches, 0.014 inches, 0.021 inches
- Operational Condition: Constant 1 horsepower load
