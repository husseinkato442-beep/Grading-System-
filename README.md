# UNEB A-Level Grading System

## Overview

This Java project automates the grading process for **Bukoto Comprehensive School**'s MOCK A-Level examinations. The grading follows **Uganda National Examinations Board (UNEB)** standards for A-Level, based on student scores out of 100.

The program:
- Accepts scores for 5 students.
- Assigns grades (1 to 9) and remarks (Distinction, Credit, Pass, Fail).
- Displays individual results.
- Prints a grade distribution summary after processing all students.

## UNEB A-Level Grading Scale

| Marks Range | Grade | Remark      |
|-------------|--------|-------------|
| 80 – 100    | 1      | Distinction |
| 75 – 79     | 2      | Distinction |
| 66 – 74     | 3      | Credit      |
| 60 – 65     | 4      | Credit      |
| 50 – 59     | 5      | Credit      |
| 45 – 49     | 6      | Credit      |
| 35 – 44     | 7      | Pass        |
| 30 – 34     | 8      | Pass        |
| 0 – 29      | 9      | Fail        |

## Features

- Uses `if-else-if` logic for accurate grading
- Processes 5 students using a `while` loop
- Displays detailed report per student
- Outputs grade distribution summary

## Getting Started

### Prerequisites

- Java JDK 8 or higher
- Any text editor or IDE

### How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/uneb-grading-system.git
   cd uneb-grading-system
