# Fuzzy Logic System for Battery Health Diagnosis

## Project Overview
This project implements a Fuzzy Logic System to diagnose the health condition of a battery based on three parameters: voltage, current, and temperature.

## Features
- **Input Parameters:**
  - **Voltage:** Measured in volts, ranging from 0 to 15V.
    - Low
    - Medium
    - High
  - **Current:** Measured in amperes, ranging from 0 to 100A.
    - Low
    - Medium
    - High
  - **Temperature:** Measured in degrees Celsius, ranging from 0 to 100°C.
    - Low
    - Medium
    - High

- **Output:**
  - The health status of the battery is estimated as a percentage, with higher values indicating better health.

## Dependencies
- **NumPy**: Used for numerical data processing.
- **Scikit-Fuzzy**: For creating the fuzzy logic system and defining membership functions.
- **Matplotlib**: For graphical display of results.
- **Tkinter**: For building a graphical user interface.

## How to Run
1. Install the required libraries:
   ```
   pip install numpy scikit-fuzzy matplotlib tkinter
   ```
2. Run the main script that inputs the battery voltage, current, and temperature to estimate the battery’s health status.

## Implementation Steps
1. Define the input variables: battery voltage, current, and temperature.
2. Create fuzzy membership functions using triangular shapes.
3. Build the fuzzy rule base using diagnostic rules.
4. Implement the model using Python with Scikit-Fuzzy and NumPy libraries.
5. Evaluate the system using test data to assess performance with a reported accuracy of 93%.

## System Performance
- **Accuracy:** 93%
- **Error Rate:** 7%
- Testing shows good diagnostic performance with slight deviations in predicted versus actual values.

## References
1. "Fuzzy Logic: Intelligence, Control, and Information" by John Yen and Reza Langari
2. "Fuzzy Logic with Engineering Applications" by Timothy J. Ross
3. "Introduction to the Theory of Fuzzy Subsets" by Witold Pedrycz and Fernando Gomide
4. "Fuzzy Logic for Embedded Systems Applications" by Ahmad M. Ibrahim

