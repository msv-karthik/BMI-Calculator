# BMI Calculator

This is a simple **BMI Calculator** built with HTML, CSS, and JavaScript. The application allows users to input their **height** (in centimeters) and **weight** (in kilograms) to calculate their **Body Mass Index (BMI)**. It then categorizes the result as **Underweight**, **Normal weight**, or **Overweight** based on BMI values.

---

## Features

- Input for **height** and **weight**.
- Real-time calculation of **BMI** based on user input.
- Output displaying BMI and weight category (Underweight, Normal, Overweight).
- Basic form validation to ensure height and weight are valid numbers.
- User-friendly design with clear error messages.

---

## Installation

To run the BMI Calculator locally on your machine, follow these steps:

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/your-username/bmi-calculator.git
    ```

2. Navigate to the project directory:
    ```bash
    cd bmi-calculator
    ```

3. Open the `index.html` file in your preferred browser.
    
    You can simply double-click the `index.html` file, or if you prefer to use a local server, you can run it with a live server extension (e.g., in Visual Studio Code) or through a simple Python HTTP server:
    ```bash
    python -m http.server
    ```

4. The app will be accessible at `http://localhost:8000` or just by opening the `index.html` file directly.

---

## Usage

1. Enter your height in **centimeters** (e.g., `170`).
2. Enter your weight in **kilograms** (e.g., `70`).
3. Click the **Calculate** button to calculate your BMI.
4. The BMI will be calculated and displayed along with the corresponding weight category:
    - **Underweight**: BMI < 18.6
    - **Normal**: 18.6 <= BMI < 24.9
    - **Overweight**: BMI >= 24.9
5. If any of the inputs are invalid (non-numeric or zero/negative values), an error message will appear asking you to provide valid inputs.

---

## Technologies Used

- **HTML** for structure
- **CSS** for styling
- **JavaScript** for interactivity and logic

---

## File Structure
```
bmi-calculator/
├── index.html      # Main HTML file
├── style.css       # Styles for the calculator
├── index.js        # JavaScript for BMI logic and form validation
└── README.md       # Project documentation
```
