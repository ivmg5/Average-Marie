# **Statistical Mean Program in MARIE**
> *A program to calculate the statistical mean of 10 data inputs in the MARIE system.*

## **Introduction**
This project implements a program in MARIE assembly language that calculates the mean of 10 user-input values. The program stores the data in an array, calculates the sum, and then obtains the average using successive subtraction.

## **Project Description**
- **Main functionality:** Receives 10 data inputs from the user, calculates their mean, and displays it on the output port.
- **Technologies used:** MARIE assembly language.
- **Challenges faced:** Limitations of the MARIE system for division operations, which was addressed by using successive subtractions.
- **Future improvements:** Optimize the calculation process for different array sizes and improve handling of division precision.

## **Table of Contents**
1. [Introduction](#introduction)
2. [Project Description](#project-description)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Testing](#testing)
6. [License](#license)

## **Installation**
No additional installation is required. The code is designed to run on the MARIE simulator.

1. **Prerequisites**:
   - **MARIE Simulator** - [Download here](https://www.mcs.sdsmt.edu/marietool/).

2. **Clone the repository:**
   ```bash
   git clone https://github.com/ivmg5/Average-Marie.git
   cd Average-Marie
   ```

3. **Load the code in MARIE Simulator:**
   Open the file in the MARIE simulator and run the program.

## **Usage**
1. Run the program in the MARIE simulator.
2. Enter the 10 values one by one into the data input.
3. Once all data has been entered, the program will calculate the mean and display the result on the output port.

**Example Usage:**
Upon entering the values, the system will accumulate the data and calculate the statistical mean using successive subtractions.

## **Testing**
To verify functionality, run the program in the MARIE simulator and input test data. Ensure that the output matches the expected mean value.

```bash
# There are no automated testing commands in MARIE, so testing is manual.
```

## **License**
This project is licensed under the MIT License.
