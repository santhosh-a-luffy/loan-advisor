# Loan Advisor AI (Streamlit)

An interactive, chat-style loan eligibility assistant. It asks for missing inputs, computes EMI/DTI, renders an eligibility decision, and gives suggestions to improve approval chances.

## ✨ Features
- Chat UI with memory (Streamlit `st.chat_message`, `st.chat_input`)
- Field-by-field questioning (income, loan amount, tenure, interest rate, existing EMIs, missed payments, credit score)
- EMI & DTI calculations
- Heuristic risk scoring → Decision + reasons + suggestions
- Quick commands: `reset`, `set tenure to 48`, `modify amount to 300000`, etc.

## 🧱 Project Structure
