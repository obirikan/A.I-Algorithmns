# Simple Linear Regression – Explained for AI Interviews

This guide explains **Simple Linear Regression**, a core idea in AI and statistics. It models the relationship between `x` (input) and `y` (output) using a straight line.

---

##  Goal: Predict `y` from `x`

We fit a line:

    y = m * x + c

Where:
- `m` = slope of the line
- `c` = y-intercept (value of y when x = 0)

---

##  Step 1: Compute Means

Let:

    x̄ = mean of x values = (x1 + x2 + ... + xn) / n  
    ȳ = mean of y values = (y1 + y2 + ... + yn) / n

---

##  Step 2: Compute Slope (m)

    m = Σ[(xi - x̄) * (yi - ȳ)] / Σ[(xi - x̄)^2]

Intuition:
- Numerator = how x and y vary **together** (covariance)
- Denominator = how x varies **alone** (variance)

---

##  Step 3: Compute Intercept (c)

    c = ȳ - m * x̄

This shifts the line to best match the average values.

---

##  Final Equation

    y = m * x + c

Use this to predict y for any x.

---
##  Summary

- This is the foundation of **supervised learning**.
- Linear regression minimizes error by finding the best `m` and `c`.
- Used in predictions, trend analysis, and AI pipelines.

---
