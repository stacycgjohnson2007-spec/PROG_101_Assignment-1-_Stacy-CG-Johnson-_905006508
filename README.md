# PROG_101_Assignment-1-_Stacy-CG-Johnson-_905006508
FloodWatch SL – Flood Early-Warning and Community Alert System

Course: PROG101 – Introduction to Programming
Institution: Limkokwing University of Creative Technology
Student: Stacy Johnson
Project: Assignment 1
Country: Sierra Leone

1. Project Overview

FloodWatch SL is a proposed flood early-warning and community alert system designed to help protect communities in Sierra Leone from flooding.

The system monitors rainfall measurements and river water levels to identify possible flood risks. Based on the readings received, it classifies the situation into different alert levels and sends warning messages to registered communities.

The main aim of this project is to demonstrate how programming concepts, pseudocode, decision-making, loops, functions, and validation can be used to solve a real-life problem.

2. Objectives

The objectives of FloodWatch SL are to:

- Monitor rainfall and river water levels.
- Validate readings to ensure that they are within acceptable ranges.
- Identify possible flood risks.
- Classify flood conditions into four alert levels.
- Send warning messages to registered communities.
- Support community volunteers during serious flood situations.
- Help improve community awareness and emergency preparedness.

3. Alert Levels

The system uses four alert levels:

Alert Level| Meaning
GREEN| Normal conditions; no immediate flood warning.
YELLOW| Watch level; communities should remain alert.
ORANGE| Warning level; communities should prepare for possible flooding.
RED| Severe danger; urgent action and emergency response may be required.

4. Main Features

- Reading Validation: Checks whether rainfall and river-level readings are within the permitted limits.
- Flood Classification: Determines the appropriate alert level using predefined conditions.
- Phone Number Validation: Checks whether community phone numbers follow the required format.
- Warning Messages: Builds alert messages for communities, with support for Krio translation.
- SMS Alerts: Sends warning messages to registered community contacts.
- Volunteer Coordination: Contacts a volunteer coordinator when a RED alert occurs and some alerts fail.
- Event Logging: Records monitoring activities and alert events.

5. Programming Concepts Used

This project demonstrates the following programming concepts:

- Variables and constants
- Data types
- Input and output
- Conditional statements ("IF", "ELSE")
- Loops ("WHILE" and "REPEAT")
- Functions and procedures
- Arrays
- Boolean logic
- Input validation
- Error handling

6. System Functions

The pseudocode is organised into five main functions:

1. "validateReading()" – Checks rainfall and river-level readings.
2. "classifyAlert()" – Determines the flood alert level.
3. "isValidPhone()" – Validates community phone numbers.
4. "buildMessage()" – Creates warning messages for communities.
5. "sendAlerts()" – Sends alerts and counts failed messages.

The main program controls the monitoring process, receives readings, validates them, classifies the flood risk, sends alerts where necessary, and records events.

7. System Monitoring Process

The system follows this general process:

1. Load registered community information.
2. Receive rainfall and river-level readings.
3. Validate the readings.
4. Display an error if the readings are invalid.
5. Classify the flood risk if the readings are valid.
6. Send community alerts when necessary.
7. Record the monitoring event.
8. Wait for the next monitoring interval.
9. Continue until monitoring is stopped.

8. Project Diagrams

The project includes flowcharts to illustrate the system's logic and decision-making process.

- Main Program Flowchart
- "classifyAlert()" Function Flowchart
- "sendAlerts()" Function Flowchart

These diagrams help explain how the system operates step by step.

9. Technologies and Tools

- Pseudocode
- Programming logic and algorithm design
- Flowcharts
- Microsoft Word
- GitHub for project documentation and submission

10. Expected Benefits

FloodWatch SL is intended to:

- Improve early awareness of possible flooding.
- Help communities prepare for emergencies.
- Support faster communication of flood warnings.
- Reduce the risks associated with delayed warnings.
- Encourage the use of technology to address community problems.

11. Limitations

This assignment presents a proposed system using pseudocode and flowcharts. It is not yet a fully implemented application.

Actual operation would require rainfall and river-level sensors or reliable data sources, an SMS gateway, a community contact database, translation support, and emergency-response coordination.

12. Conclusion

FloodWatch SL demonstrates how programming logic can be applied to a real-world problem in Sierra Leone. By monitoring environmental readings, classifying flood risks, and communicating warnings to communities, the proposed system aims to support flood preparedness and public safety.

This project has helped demonstrate the importance of algorithms, pseudocode, functions, conditional statements, loops, and problem-solving in programming.

---

Author: Stacy Johnson
Course: PROG101 – Introduction to Programming
Institution: Limkokwing University of Creative Technology
