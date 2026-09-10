🤖 BOTBUSTER

AI-Powered Fake Social Media Account Detection

BOTBUSTER is an AI-assisted cybersecurity prototype designed to identify potentially fake, suspicious, or high-risk social media accounts using multiple account-level signals.

The system provides an explainable risk assessment rather than simply labeling an account as "fake".

---

🚀 Live Prototype

https://ai-account-shield.preview.emergentagent.com/

---

🎯 Problem Statement

Fake and automated social media accounts can be used for:

- Spam and fraudulent activities
- Fake engagement
- Impersonation
- Social engineering
- Online manipulation
- Malicious campaigns
- Misinformation amplification

Identifying suspicious accounts manually can be difficult and time-consuming.

---

💡 BOTBUSTER Solution

BOTBUSTER combines multiple account-level indicators to generate an overall risk assessment.

Analysed Signals

- Account age
- Followers
- Following count
- Followers-to-following ratio
- Engagement indicators
- Posting frequency
- Profile completeness
- Verification status
- Profile picture availability
- Follower growth patterns
- Suspicious behavioural patterns

---

✨ Key Features

🔍 Account Analyzer

Analyze account-level information and generate a risk assessment.

📊 Risk Score

Produces a normalized risk score from:

0 → 100

🚦 Risk Classification

Score| Risk Level
0–29| 🟢 Low
30–59| 🟡 Moderate
60–79| 🟠 High
80–100| 🔴 Critical

🧠 Explainable Analysis

Instead of only producing a score, BOTBUSTER highlights the signals contributing to the assessment.

📈 Visual Analytics

The prototype presents account characteristics and risk indicators using visual components.

🔐 Privacy-Focused Design

BOTBUSTER does not require a user's social-media password.

---

🏗️ System Architecture

                USER
                  │
                  ▼
          ┌────────────────┐
          │ Web Interface  │
          └───────┬────────┘
                  │
                  ▼
        ┌────────────────────┐
        │ Account Information│
        └─────────┬──────────┘
                  │
                  ▼
        ┌────────────────────┐
        │ Feature Extraction │
        └─────────┬──────────┘
                  │
        ┌─────────┼──────────┐
        ▼         ▼          ▼
     Profile   Activity   Engagement
     Signals   Signals     Signals
        │         │          │
        └─────────┼──────────┘
                  ▼
        ┌────────────────────┐
        │ Risk Scoring Engine│
        └─────────┬──────────┘
                  ▼
        ┌────────────────────┐
        │ Risk Classification│
        └─────────┬──────────┘
                  ▼
        ┌────────────────────┐
        │ Explainable Result │
        └─────────┬──────────┘
                  ▼
             DASHBOARD

---

🧠 Detection Methodology

BOTBUSTER follows a multi-signal risk assessment approach.

1. Profile Signals

Examines characteristics such as profile completeness, profile picture availability and verification status.

2. Activity Signals

Considers posting frequency and account activity patterns.

3. Engagement Signals

Examines the relationship between followers, likes, comments and other engagement indicators.

4. Network Signals

Uses follower/following relationships and account-level ratios as supporting indicators.

5. Risk Assessment

The available signals are normalized and combined into an overall risk score.

The result is classified into:

- Low
- Moderate
- High
- Critical

The score is intended as a risk indicator and not definitive proof that an account is fake.

---

🧪 Hackathon Prototype

BOTBUSTER is currently a hackathon prototype demonstrating the concept of AI-assisted suspicious-account detection.

Future versions can integrate trained machine-learning models and real-world datasets for improved detection performance.

---

🔮 Future Scope

- Real social-media API integration
- Machine-learning classification models
- Random Forest / XGBoost models
- Neural-network based detection
- Anomaly detection
- NLP-based profile/content analysis
- Graph-based account analysis
- Temporal behaviour analysis
- Bot-network detection
- Real-time monitoring
- Threat-intelligence integration
- Continuous model improvement

---

🔐 Responsible AI

BOTBUSTER provides a risk assessment rather than a definitive judgment.

A high risk score should be treated as an indicator requiring further investigation.

The system should not be used as the sole basis for punitive action against an individual.

---

🛠️ Technology Direction

Frontend

- React
- JavaScript
- Responsive UI
- Data visualization

Backend / AI

- Python
- FastAPI
- Feature engineering
- Machine-learning based risk assessment

Deployment

- Web-based prototype

---

📸 Screenshots

Screenshots of the prototype are available in the "screenshots/" directory.

---

🎥 Hackathon Demo Flow

1. Open BOTBUSTER
2. Navigate to Account Analyzer
3. Enter account information
4. Run analysis
5. Generate risk score
6. View risk classification
7. Inspect contributing signals
8. Review recommended next steps

---

👥 Project

BOTBUSTER

AI-Powered Fake Social Media Account Detection

Developed as a hackathon project prototype.
