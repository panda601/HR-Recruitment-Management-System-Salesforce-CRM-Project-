# HR Recruitment Management System (Salesforce CRM Project)

The **HR Recruitment Management System** is an end-to-end hiring and candidate tracking solution built on Salesforce.  
It streamlines job posting, candidate management, screening, interview scheduling, and offer processing—designed to help HR teams automate manual work and gain full visibility into the hiring funnel.

---

## 📌 Project Overview

This project replicates a real-world recruitment workflow inside Salesforce using:

- Custom Objects  
- Record-Triggered Flows  
- Approval Processes  
- Email Alerts  
- Dashboards & Reports  
- Lightning App Customization  

---

## 🧱 Key Features

### ✔ Job Posting Management  
- Create & manage job positions  
- Required skills, experience, department, salary range  
- Status tracking: Open → In Progress → Closed  

### ✔ Candidate Management  
- Candidate information, skills, experience  
- Resume upload  
- Auto-screening  
- Stage tracking  

### ✔ Automated Screening Flow  
- Filters candidates based on experience & skills  
- Updates status & notifies recruiters  

### ✔ Interview Management  
- Auto-create interview records  
- Scheduling & reminders  
- Feedback capture  

### ✔ Offer Management  
- Offer creation  
- Salary validation  
- Approval workflow  
- Final hiring decision  

### ✔ Dashboards  
- Recruitment funnel  
- Candidates by source  
- Interviews outcome  
- Offers insights  

---

## 🛠 Salesforce Components Used

### Custom Objects
- Job_Position__c  
- Candidate__c  
- Interview__c  
- Offer__c  

### Automation
- Flows  
- Approval Processes  
- Email Alerts  

---

## 🗂 Data Model (ER)

Job Position (1) — (Many) Candidates  
Candidate (1) — (Many) Interviews  
Candidate (1) — (1) Offer  

---

## ⚙️ System Architecture

Job Created → Candidates Apply → Auto Screening → Interview Scheduling → Feedback → Offer Approval → Hiring Decision  

---

## 📁 Folder Structure

```
HR-Recruitment-Management-System
│
├── README.md
├── /Flows
├── /Screenshots
├── /ER-Diagram
└── sample-data.csv
```

---

## 📝 Resume Summary

Designed and implemented a complete recruitment workflow inside Salesforce including job posting, candidate screening, interview scheduling, and offer automation. Built dashboards, flows, and approval processes to streamline hiring operations.

---

## 👨‍💻 Author  
**Rahul Kumar Roy**

