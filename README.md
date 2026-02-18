# Scientific Retro Calculator

A web-based scientific calculator featuring a nostalgic 80s retro aesthetic. This calculator handles basic arithmetic, advanced scientific functions, and solves systems of linear equations.
Unlike the ones on youtube, this one can actually solve linear equations in both 2 and 3 variables.

## LIVE DEMO: https://gauri-gupta0.github.io/scientific-calculator/

## Features

- **Retro Aesthetic**: Designed with a classic 80s look, complete with 'VT323' and 'Press Start 2P' fonts, scanline effects, and a tactile button feel.
- **standard Arithmetic**: discrete operations like Addition, Subtraction, Multiplication, Division, and Modulo.
- **Scientific Functions**:
  - Trigonometric: `sin`, `cos`
  - Logarithmic: `log` (base 10), `ln` (natural log)
  - Exponential: `e^x`, Power (`x^?`), Square Root (`sqrt`)
  - Inverse (`x^-1`)
- **Linear Equation Solver**:
  - Solves systems of linear equations for **2 variables** (2x2) and **3 variables** (3x3).

## 🚀 How to Use

1. **Basic & Scientific Calculations**: 
   - Simply click the buttons to enter numbers and operations.
   - Press `=` to see the result.

2. **Solving Equations**:
   - Click the **`3var`** button to enter Equation Mode.
   - You will be prompted to select the number of unknowns.
   - Click **`2`** for a 2-variable system or **`3`** for a 3-variable system.
   - The display will prompt you to enter coefficients (e.g., `a11`, `a12`, `b1`...).
   - Enter each number and press **`=`** to submit it.
   - Once all coefficients are entered, the calculator will display the values for x, y (and z).

## Technologies Used

- **HTML5**: Structure and layout.
- **CSS3**: Styling with gradients, shadows, and web fonts for the retro effect.
- **JavaScript**: Core logic for calculations, equation processing, and DOM manipulation.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gauri-gupta0/scientific-calculator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd scientific-calculator
   ```
3. Open `calculator.html` in your preferred web browser.
