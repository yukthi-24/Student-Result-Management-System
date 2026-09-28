# Student Result Management System

A Python-based Student Result Management System that calculates grades, credits, percentage, SGPA, overall result status, and class rankings from student marks.

## Features

- Accepts student details and subject-wise marks
- Calculates internal and external marks
- Determines total marks and grades
- Calculates grade points and credits earned
- Calculates percentage and SGPA
- Determines overall PASS/FAIL status
- Generates student rankings based on SGPA
- Displays results in a structured table using `tabulate`

## Subjects

The system currently handles:

- Mathematics
- Physics
- Chemistry
- Biology
- Python

## Technologies Used

- Python
- Tabulate

## SGPA Calculation

SGPA is calculated using the weighted grade points of subjects based on their respective credits.

Failed subjects contribute zero earned credits.

## How to Run

1. Clone the repository.
2. Install the required dependency:

```bash
pip install tabulate
