# Introduction to R

Welcome to the repository where I share my master's work, showcasing one of the first projects where I was introduced to **R programming**. This project combines statistical concepts and programming to provide hands-on experience with **simple linear regression** (SLR) and **bootstrapping** techniques. It serves as a foundational exercise for anyone new to R or looking to strengthen their understanding of these concepts.

---

## **Project Title**
### R Project: SLR and Bootstrap

---

## **Objective**

This project focuses on implementing two unique functions in R:
1. **Simple Linear Regression (SLR)**:
   - Custom function `myslr()` to estimate coefficients (betas) for a simple linear regression model.
2. **Bootstrap Function**:
   - Custom function `myboot()` to generate bootstrap estimates from a given sample.

---

## **Dataset**

The project utilizes the **`mtcars` dataset**, which is a well-known dataset extracted from the 1974 Motor Trend US magazine. This dataset includes observations on fuel consumption and 10 aspects of automobile design and performance for 32 cars.

### **Key Variables Used in the Project**:
- **`mpg`**: Miles per gallon (fuel efficiency)
- **`wt`**: Weight of the car (used as the predictor for the regression model)

Other variables in the dataset include:
- `cyl`: Number of cylinders
- `disp`: Displacement (cu.in.)
- `hp`: Horsepower
- `drat`: Rear axle ratio
- `qsec`: 1/4 mile time, and more.

---

## **What the Project Covers**

1. **Simple Linear Regression (SLR)**:
   - The function `myslr()` is used to fit a regression model for predicting `mpg` based on `wt`.
   - Estimated regression coefficients (`beta0` and `beta1`) are calculated.
   - Model interpretation is provided, showcasing the relationship between a car's weight and its fuel efficiency.

2. **Bootstrapping**:
   - The function `myboot()` generates bootstrap estimates for the regression coefficients to assess variability and reliability.
   - Bootstrap samples are created, and results are summarized to provide insights into the robustness of the model.

---

## **Applications**

- Fitting and interpreting a **linear regression model** using real-world data.
- Learning how to apply **bootstrapping techniques** to evaluate the precision of statistical estimates.
- Demonstrating how to build custom statistical functions in R for educational and professional purposes.

---

## **Why Share This Project?**

This project represents an important step in my journey of learning R programming and applying statistical concepts to real-world data. It is an excellent starting point for anyone new to:
- **R programming**
- **Statistical modeling**
- **Bootstrapping techniques**

By sharing this project, I hope to provide a resource that others can use to learn and practice. The repository includes code, explanations, and results to guide you through these concepts step-by-step.

---

## **How to Use This Repository**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/masters-work.git
   cd masters-work
