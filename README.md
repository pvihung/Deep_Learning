# Deep Learning

## Overview: 
This project explores how deep learning architectures adapt across diverse predictive domains — regression, classification, and feature-rich analysis.

Three separate datasets and tasks were implemented to demonstrate how neural networks generalize and perform under different data distributions, objectives, and feature complexities.

The study emphasizes model design, preprocessing discipline, and cross-domain insights.

## Project Structure

| Part                        | Domain    | Task Type                  | Objective                                                                              |
| --------------------------- | --------- | -------------------------- | -------------------------------------------------------------------------------------- |
| **Part 1 – Exam Scores**    | Education | Regression                 | Predict students’ final exam scores based on academic & lifestyle factors.             |
| **Part 2 – Sleep Quality**  | Health    | Multi-class Classification | Classify individuals by sleep disorder type (None, Sleep Apnea, Insomnia).             |
| **Part 3 – Healthy Eating** | Nutrition | Binary Classification      | Predict whether a meal is healthy based on its nutritional and categorical attributes. |

## Dataset Summaries
### Part 1 – Exam Scores (Regression)

Predict final exam scores using academic and behavioral indicators.
| Feature              | Description                            |
| -------------------- | -------------------------------------- |
| `hours_studied`      | Study duration before exam             |
| `sleep_hours`        | Average daily sleep duration           |
| `attendance_percent` | Class attendance rate                  |
| `previous_scores`    | Historical performance                 |
| `exam_score`         | **Target:** Predicted continuous score |

### Part 2 – Sleep Quality (Classification)

Classify presence of sleep disorders using lifestyle and biometric data. 
| Feature                                                                                           | Description                               |
| ------------------------------------------------------------------------------------------------- | ----------------------------------------- |
| `Sleep Duration`, `Quality of Sleep`, `Stress Level`, `BMI Category`, `Heart Rate`, `Daily Steps` | Predictors                                |
| `Sleep Disorder`                                                                                  | **Target:** None / Sleep Apnea / Insomnia |

### Part 3 – Healthy Eating (Binary Classification)

Determine if a meal is healthy from nutritional composition.

| Feature Type    | Examples                                                          |
| --------------- | ----------------------------------------------------------------- |
| **Categorical** | `cuisine`, `meal_type`, `diet_type`, `cooking_method`             |
| **Numerical**   | `calories`, `protein_g`, `carbs_g`, `fat_g`, `fiber_g`, `sugar_g` |
| **Target**      | `is_healthy` (0 = No, 1 = Yes)                                    |

## Technologies Used

- Language: Python

- Frameworks: TensorFlow / Keras / PyTorch

- Visualization: Matplotlib, Seaborn

- Data Handling: Pandas, NumPy, Scikit-learn

- Environment: Google Colab

## Repository Structure

Assignment_3/
│
├── Student_Exam/
│   ├── ML_Student_Exam.ipynb
│   ├── Student_Exam_DL.pdf
│   └── student_exam_scores.csv
│
├── Sleep_Health_LifeStyle/
│   ├── ML_Sleep_Health_LifeStyle.ipynb
│   ├── Sleep_Health_LifeStyle_DL.pdf
│   └── sleep_health_and_lifestyle.csv
│
├── Healthy_Eating/
│   ├── ML_Healthy_Eating.ipynb
│   ├── Healthy_Eating_DL.pdf
│   └── healthy_eating_dataset.csv
│
└── README.md



