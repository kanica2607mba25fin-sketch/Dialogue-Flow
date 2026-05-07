# 💰 FINANCIAL ASSISTANT – Personal Finance AI Chatbot

An AI-powered personal finance assistant built using Google Dialogflow NLP.

This chatbot helps users with:

- 🏦 Loan Eligibility Checking
- 📊 EMI Calculation
- 💹 Investment Advice

The project demonstrates the practical implementation of Artificial Intelligence and Natural Language Processing (NLP) in the FinTech domain.

---

# 📌 Project Overview

Many people struggle with:

- Understanding loan eligibility
- Calculating EMI manually
- Choosing the right investment option
- Accessing financial guidance anytime

Traditional financial consultation is often slow, complex, and unavailable 24×7.

To solve this problem, **Lovegeet** was developed as an intelligent finance chatbot that provides quick and personalized financial assistance using NLP technology.

---

# 🤖 Technologies Used

- Google Dialogflow
- Natural Language Processing (NLP)
- Machine Learning
- Intent Classification
- Entity Extraction
- Slot Filling
- FinTech Logic

---

# 🧠 AI & NLP Concepts Used

## ✅ Intent Classification

Identifies what the user wants.

### Examples:
- EMI Calculation
- Loan Eligibility
- Investment Advice

---

## ✅ Entity Extraction

Extracts important values like:
- Income
- Loan Amount
- Interest Rate
- Risk Level

---

## ✅ Slot Filling

If information is missing, the chatbot asks follow-up questions automatically.

---

## ✅ Custom Entity

Custom entity created:

```text
risk_level
```

Values:
- LOW
- MEDIUM
- HIGH

---

# 📂 Project Modules

# 🏦 1. Loan Eligibility Module

## Intent
```text
Loan_Eligibility_Advanced
```

## Features

- Checks loan eligibility using salary
- Uses 30–40% income EMI rule
- Suggests safer loan options
- Mentions credit score requirements

## Parameters Extracted

| Parameter | Type | Purpose |
|---|---|---|
| income | @sys.number | Monthly Salary |
| Loan_amount | @sys.number | Requested Loan Amount |

## Example Query

```text
I earn 60000, can I get 20 lakh home loan?
```

---

# 📊 2. EMI Calculation Module

## Intent

```text
EMI_Calculation
```

## Features

- Calculates monthly EMI
- Uses standard banking EMI formula
- Accepts loan amount, interest rate, and tenure

## Parameters Extracted

| Parameter | Type | Purpose |
|---|---|---|
| LOAN_AMOUNT | @sys.number | Principal Amount |
| interest | @sys.number | Interest Rate |
| tenure | @sys.number | Loan Duration |

---

# 🧮 EMI Formula

```text
EMI = P × r × (1 + r)^n / ((1 + r)^n – 1)
```

Where:

- P = Principal Loan Amount
- r = Monthly Interest Rate
- n = Loan Tenure in Months

## Example

```text
₹10,00,000 at 8% for 5 years
EMI ≈ ₹20,276/month
```

---

# 💹 3. Investment Advice Module

## Intents

- Investment_Advice_Advanced
- Low Risk Investment
- Mutual Fund vs FD

---

# 🟢 LOW RISK

- Fixed Deposits (FD)
- Government Bonds
- Debt Mutual Funds

### Expected Returns
```text
6–7% p.a.
```

---

# 🟡 MEDIUM RISK

- Balanced Mutual Funds
- Index Funds
- SIP Investments

### Expected Returns
```text
10–12% p.a.
```

---

# 🔴 HIGH RISK

- Equity Mutual Funds
- Direct Stock Market
- Aggressive Growth Funds

### Expected Returns
```text
12–18% p.a.
```

---

# ⚙️ Dialogflow Architecture

```text
User Input
     ↓
Dialogflow NLP Engine
     ↓
Intent Matching
     ↓
Entity Extraction
     ↓
Slot Filling
     ↓
Response Generation
     ↓
User Receives Output
```

---

# 📁 Intents Configured

The chatbot includes the following intents:

- Default Welcome Intent
- Default Fallback Intent
- Loan_Eligibility_Advanced
- EMI_Calculation
- Investment_Advice_Advanced
- Investment Planning
- Low Risk Investment
- Mutual Fund vs FD
- Loan_Request_With_Amount

---

# 📸 Screenshots to Add

Add the following screenshots in your GitHub repository:

- Agent Name & Intent List
- Loan Eligibility Training Phrases
- Parameters & Entities Configuration
- Loan Eligibility Output
- EMI Calculation Output
- Investment Advice Output

## Example

```md
![Loan Intent](images/loan_intent.png)
```

---

# 🚀 Future Improvements

## 🔗 Webhook Integration

Connect with real banking APIs for:
- Live interest rates
- Credit score checks
- Real-time financial data

---

## 🌍 Multi-Language Support

Support for:
- Hindi
- Punjabi
- Tamil
- Other regional languages

---

## 📲 Platform Deployment

Deploy on:
- WhatsApp
- Telegram
- Facebook Messenger
- Mobile Apps

---

## 🧠 AI Personalization

Provide smarter recommendations based on:
- User history
- Financial goals
- Previous interactions

---

# 📦 Repository Structure

```text
📁 Dialogue_Flow/
│
├── intents/
├── entities/
├── README.md
├── Dialogue_Flow.zip
└── screenshots/
```

---

# 🛠️ How to Run the Project

## Step 1

Open Google Dialogflow Console.

---

## Step 2

Create a new Dialogflow agent.

---

## Step 3

Go to:

```text
Settings → Export and Import
```

---

## Step 4

Import:

```text
Dialogue_Flow.zip
```

---

## Step 5

Test the chatbot inside Dialogflow console.

---

# 🎯 Key Features

✅ Loan Eligibility Assessment  
✅ EMI Calculation  
✅ Risk-Based Investment Advice  
✅ NLP-Based Conversation  
✅ 24×7 Financial Assistance  
✅ User-Friendly Interaction  

---

# 📈 Project Impact

This chatbot can help:
- Students
- Working professionals
- First-time investors
- Financially underserved users

It simplifies financial decision-making using conversational AI.

---

# 🎓 Learning Outcomes

This project demonstrates:
- Practical NLP implementation
- AI-powered conversation systems
- Dialogflow intent handling
- Entity extraction techniques
- FinTech chatbot development

---

# 🙌 Conclusion

*FINANCIAL ASSISTANT* is an AI-powered finance chatbot built using Google Dialogflow that provides:

- Instant loan eligibility checking
- Accurate EMI estimation
- Personalized investment advice

The project showcases how AI and NLP can improve financial accessibility and user experience in the FinTech industry.

---

# 👩‍💻 Author

**Kanica**

---

# ⭐ Thank You

If you liked this project, feel free to ⭐ the repository.
