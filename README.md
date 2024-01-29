# Exercise: BMI Calculator with Input Validation

Here is how the World Health Organization has categorized Body Mass Index:
In this exercise, your goal is to implement user input validation techniques for an extended version of the BMI (Body Mass Index) calculator using JavaScript. Strengthen your programming skills by mastering the art of validating and processing user inputs with precision.

## World Health Organization BMI Categories

- **Severely Underweight:** Below 16 kg/m²
- **Underweight:** 16.0 to 18.4 kg/m²
- **Normal Weight:** 18.5 to 24.9 kg/m²
- **Overweight:** 25.0 to 29.9 kg/m²
- **Moderately Obese:** 30.0 to 34.9 kg/m²
- **Severely Obese:** 35.0 to 39.9 kg/m²
- **Morbidly Obese:** ≥40.0 kg/m²

## Instructions:
# Exercise: Building a Robust BMI Calculator

## Objective:
Create an advanced BMI (Body Mass Index) calculator in JavaScript, incorporating robust user input validation to ensure accurate and reliable results. The implementation will involve calling the `getValidNumberInput` function, which guarantees that the user input is a valid number greater than 0. This function will continuously prompt the user until a valid input is provided or the user cancels the input.

## Instructions:

### Step 1: Prompt for Height
- Call the `getValidNumberInput` function to prompt the user for their height in centimeters.
- The function will ensure that the provided input is a valid number greater than 0.
- If the user cancels the input, display an alert indicating that the BMI calculation was canceled. Terminate the program or provide a farewell message.

### Step 2: Prompt for Weight
- Utilize the `getValidNumberInput` function again to prompt the user for their weight in kilograms.
- Follow the same validation process to guarantee a valid number greater than 0.

### Step 3: Calculate BMI
- Implement the BMI calculation using the validated height and weight inputs.
- Display the calculated BMI and proceed to the next steps.

### Step 4: Determine BMI Category
- Evaluate the BMI category based on the calculated BMI.
- Categories include Severely Underweight, Underweight, Normal weight, Overweight, Moderately Obese, Severely Obese, and Morbidly Obese.

### Step 5: Display Result
- Showcase the calculated BMI and the determined category in an alert to the user.
- Limit the BMI to two decimal places for precision using `toFixed(2)`.

### Step 6: Advanced Error Handling
- Enhance the `getValidNumberInput` function to provide informative error messages.
- Prompt users to enter valid numbers greater than 0.
- Continuously loop until a valid input is received or the user cancels the input.
