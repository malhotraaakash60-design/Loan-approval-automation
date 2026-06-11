# 🚀 Loan Approval Automation

An automated loan approval system built using **n8n** and **Google Sheets** to streamline loan application processing. The workflow automatically evaluates applications based on predefined eligibility criteria and classifies them as **Approved** or **Rejected**.

---

## 📌 Project Overview

This project eliminates manual loan screening by automating the entire decision-making process. Applicant data is collected, validated, analyzed, and processed through an automated workflow, reducing processing time and human effort.

---

## ✨ Features

- Automated loan application processing
- Rule-based approval and rejection system
- Google Sheets integration for data management
- n8n workflow automation
- Real-time decision making
- Easy-to-modify approval criteria
- Scalable and reusable workflow design

---

## 🛠️ Technologies Used

- **n8n**
- **Google Sheets**
- **JSON Workflow Configuration**
- **Workflow Automation**

---

## 🔄 Workflow Process

1. Applicant submits loan information.
2. Data is stored in Google Sheets.
3. n8n workflow retrieves application data.
4. Eligibility criteria are evaluated:
   - Credit Score
   - Monthly Income
   - Employment Status
   - Loan Amount Requested
5. Decision is generated:
   - ✅ Loan Approved
   - ❌ Loan Rejected
6. Result is recorded and communicated.

---

## 📂 Project Structure

```text
Loan-approval-automation/
│
├── My workflow 3 (1).json
├── Google Sheet.jpeg
├── Loan Approval.jpeg
├── Loan Reject.jpeg
├── n8n workflow.jpeg
└── README.md
```

---

## 📸 Screenshots

### Complete Workflow

![Workflow](n8n%20workflow.jpeg)

### Google Sheets Integration

![Google Sheet](Google%20Sheet.jpeg)

### Loan Approval Process

![Loan Approval](Loan%20Approval.jpeg)

### Loan Rejection Process

![Loan Reject](Loan%20Reject.jpeg)

---

## ⚙️ Setup Instructions

### Prerequisites

- n8n Account / Local Installation
- Google Account
- Google Sheets Access

### Installation

Clone the repository:

```bash
git clone https://github.com/malhotraaakash60-design/Loan-approval-automation.git
```

Open n8n and import:

```text
My workflow 3 (1).json
```

Configure Google Sheets credentials and activate the workflow.

---

## 📊 Sample Approval Logic

| Credit Score | Income Status | Decision |
|-------------|--------------|----------|
| ≥ 700 | Meets Requirement | Approved |
| < 700 | Any | Rejected |
| Missing Data | Any | Rejected |

---

## 🎯 Benefits

- Faster loan processing
- Reduced manual effort
- Consistent decision-making
- Improved operational efficiency
- Easy workflow customization

---

## 🔮 Future Enhancements

- AI-powered risk assessment
- Database integration
- Email/SMS notifications
- Approval dashboard
- Multi-level verification system

---

## 👨‍💻 Author

**Aakash Malhotra**

GitHub: https://github.com/malhotraaakash60-design

---

## 📜 License

This project is licensed under the MIT License.

⭐ If you found this project useful, consider giving it a star.
