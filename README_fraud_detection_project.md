# AI-Powered Fraud Detection & Compliance Monitoring System

A portfolio-ready prototype demonstrating how synthetic transaction data and machine learning can be used to support fraud detection and compliance monitoring.

## Project Summary

This project simulates a fraud detection workflow using synthetic credit card transaction data. A machine learning model is trained to classify transactions as fraudulent or legitimate based on transaction amount, location, and time. Model predictions are then integrated into a simple compliance workflow that flags suspicious activity and generates review-friendly summaries.

## Files Included

- `synthetic_credit_card_transactions.csv` - synthetic dataset used for training and analysis
- `AI_Fraud_Detection_Compliance_Project_Ruby_Visual.pdf` - polished project report with visuals
- `fraud_label_distribution.png` - chart showing fraud vs. non-fraud counts
- `average_amount_by_label.png` - chart comparing average transaction amounts by label

## Dataset Fields

- `Transaction_ID`
- `Amount`
- `Location`
- `Time`
- `Fraudulent`

## Technical Approach

### 1. Synthetic Data Generation
Synthetic transaction data was created to mimic real-world financial activity while avoiding the privacy risks of real customer records.

### 2. Model Training
A Random Forest Classifier was used as the baseline fraud detection model.

**Features used:**
- Amount
- Location
- Hour (derived from transaction time)

**Why Random Forest?**
- Works well with structured data
- Captures non-linear relationships
- Practical balance of performance and explainability

### 3. Compliance Workflow
The prototype workflow:
1. Evaluates each transaction using the trained model
2. Flags suspicious transactions
3. Produces summaries to support analyst review
4. Keeps human oversight in the decision process

### 4. Testing and Optimization
The system is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Governance and Compliance Considerations

This prototype was designed with responsible AI concepts in mind:
- Synthetic data to reduce privacy risk
- Explainable flagged-transaction summaries
- Human-in-the-loop review
- Awareness of auditability and compliance needs

## Future Improvements

- Add customer behavior history and transaction velocity
- Expand the dataset with more realistic fraud scenarios
- Add anomaly detection models
- Generate risk scores instead of binary predictions
- Build a dashboard for real-time compliance monitoring

## Portfolio / Resume Description

Developed a machine learning-based fraud detection prototype using synthetic financial transaction data and integrated it into a compliance workflow for monitoring, flagging, and review of suspicious activity. Incorporated explainability, privacy-aware development, and human oversight principles to align the system with responsible AI and compliance objectives.

## Author

Ruby  
Generated on March 30, 2026
