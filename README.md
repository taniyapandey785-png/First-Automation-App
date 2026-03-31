# Automated Feedback Email System (n8n Workflow)

## 📌 Project Description
This project is an **automation workflow built using n8n** that automatically sends a **thank-you email** whenever a new response is added to a Google Sheets document connected to a feedback form.

The workflow continuously monitors a Google Sheet for new responses and sends a personalized email to the participant using Gmail.

This automation helps save time and ensures every participant receives an instant acknowledgment.

---

# ⚙️ How the Workflow Works

The workflow follows a simple automation process:

1. A user submits a response through a **Google Form**.
2. The response is automatically stored in **Google Sheets**.
3. The **Google Sheets Trigger** in n8n detects the new row added.
4. The workflow is triggered automatically.
5. The **Gmail node sends a personalized thank-you email** to the participant.

---

# 🧩 Workflow Nodes

### 1️⃣ Google Sheets Trigger
- Monitors a Google Sheets document.
- Detects whenever a **new row is added**.
- Triggers the workflow automatically.

### 2️⃣ Gmail Node
- Sends an automated email.
- Uses the email address submitted in the form.
- Sends a thank-you message to the participant.

---

# ✉️ Example Email

### Subject
```
{Name}, Thank you for participating
```

### Message
```
Thanks for your feedback.

Thank you for your time.

Would you like to get notifications on this number: {Phone Number}
```

---

# 🛠 Technologies Used

- **n8n** – Workflow automation platform  
- **Google Sheets API** – To detect new responses  
- **Gmail API** – To send automated emails  
- **Google Forms** – To collect feedback responses  

---

# 🚀 Setup Instructions (Step-by-Step)

### Step 1
Create a **Google Form** to collect responses.

### Step 2
Link the form to a **Google Sheets document**.

### Step 3
Open **n8n**.

### Step 4
Import the workflow JSON file into n8n.

### Step 5
Connect your credentials:
- Google Sheets OAuth
- Gmail OAuth

### Step 6
Configure the **Google Sheets Trigger node** with your sheet.

### Step 7
Configure the **Gmail node** to send emails.

### Step 8
Activate the workflow.

Now whenever a new response is submitted, the system automatically sends a thank-you email.

---

# 📂 Repository Contents

```
workflow.json   → n8n automation workflow
README.md       → Project documentation
```

---

# 💡 Use Cases

- Feedback collection automation
- Event registration confirmation
- Survey participation acknowledgment
- Customer engagement automation

---

# 📚 Learning Outcome

Through this project I learned:

- Workflow automation using **n8n**
- Integrating **Google Sheets with automation**
- Sending automated emails using **Gmail API**
- Building real-world automation systems

---

# 👩‍💻 Author

Taniya Kumari
