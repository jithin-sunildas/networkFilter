# Network Filter
A high perfomant model which can efficiently and precisely predict whether a connection is normal or some sort of network attack. Trained with over 80,000 rows and tested with over 25,000 rows.

```mermaid
graph TD
    A[Start: Project Kick-off] --> B[Phase 1: Problem Statement & Goal Definition]
    B --> C[Phase 2: Data Acquisition & Initial Inspection]

    subgraph Data Preparation
        C --> D[Phase 3: Data Cleaning - Missing Values]
        D --> E[Phase 4: Data Cleaning - Categorical Feature Encoding]
        E --> F[Phase 5: Data Cleaning - Numerical Feature Scaling & Outlier Handling]
        F --> G["Phase 6: Exploratory Data Analysis (EDA)"]
        G --> H[Phase 7: Feature Selection]
    end

    subgraph Model Development & Evaluation
        H --> I[Phase 8: Build ML Models]
        I --> I1[Logistic Regression Model]
        I --> I2[Decision Tree Classifier]
        I --> I3[Random Forest Classifier]

        I1 --> J[Phase 9: Model Evaluation]
        I2 --> J
        I3 --> J

        J --> K[Phase 10: Hyperparameter Tuning]
        K --> L[Phase 11: Model Saving]
    end

    L --> M[Phase 12: Test with Unseen Data]
    M --> N["Phase 13: Interpretation of Results (Conclusion)"]
    N --> O["Phase 14: Future Work & Deployment Readiness"]
    O --> P[End: Project Complete / Deploy Model]

```
