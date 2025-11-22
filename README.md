# Fractal Multiplier & GCD Duality

This project demonstrates the duality between the Euclidean GCD algorithm and a fractal multiplication kernel based on Fibonacci numbers.

## Overview

The script `fractal_multiplier.py` simulates an analog computing approach where:
-   **Multiplication** is performed by summing the areas of squares in a Fibonacci tiling.
-   **GCD Computation** is performed by reversing this process (subtraction).

It includes:
-   A mathematical model of the fractal multiplier.
-   An analog hardware simulator (RRAM-based).
-   Visualizations of the duality.

## Usage

1.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

2.  Run the simulation and visualization:
    ```bash
    python fractal_multiplier.py
    ```

## Output

-   Console output with simulation results (multiplication accuracy, GCD steps).
-   `gcd_multiplication_duality.png`: A visualization of the algorithm.

## 🎓 Mentorship & Collaboration

This project is developed as part of independent research using AI tools and analysis.

-   **Lead Researcher:** Benson Su
-   **Mentor:** Ms. J Yu
-   **Contact:** Jeyu@mednet.ucla.edu

## ⚖️ License & Citation

-   **Code:** MIT License (free for research use)
-   **Citation:** Please cite our repo if using this work.
