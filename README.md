# 🌱 Clean Connect

### Smart India Hackathon 2025  
**Problem Statement ID:** SIH25031  
**Title:** Crowdsource Civic Issue Reporting and Resolution System  
**Theme:** Clean and Green Technology  
**Category:** Software  
**Team Name:** Clean Connect  

---

## 📖 Overview

**Clean Connect** is a civic issue reporting and resolution system designed to empower citizens and local authorities to collaboratively create cleaner, greener cities.  
The system allows citizens to report issues like potholes, garbage overflow, or broken streetlights with photos, descriptions, and automatic location detection — while administrators can monitor, assign, and resolve these reports efficiently.

---

## 💡 Problem Statement

Local governments often struggle to track and fix civic issues promptly due to lack of visibility and efficient communication channels. Citizens face difficulty reporting such issues effectively.  
**Clean Connect** bridges this gap by providing a user-friendly mobile and web platform to streamline issue reporting and tracking.

---

## ⚙️ Technical Approach

| Component | Technology Used |
|------------|-----------------|
| **Frontend** | HTML, CSS, JavaScript, ReactJS |
| **Backend** | Python Flask |
| **Database** | AWS DynamoDB |
| **Hosting** | AWS (Backend + Database) |

---

## 🚀 Features

- 📸 **Photo Upload / Capture** – Report issues with image proof.  
- 🗺️ **Automatic Location Detection** – Uses GPS or geocoding API.  
- 📝 **Description and Voice Input** – Add text or voice description.  
- 📞 **Citizen Contact Integration** – Collects phone for follow-up.  
- 🕹️ **Dark / Light Mode** – User-selectable theme.  
- 🌐 **Multilingual Support** – English, Telugu, and Hindi.  
- 🔔 **Notifications and Updates** – Users can track issue status.  
- 🧾 **Admin Dashboard (Planned)** – For municipal staff to view and resolve reports.  
- 🏅 **Reward System** – Gamified user participation through points and badges.

---

## 🧩 System Architecture

1. **Citizen App / Web Portal** – For issue reporting (frontend).  
2. **Backend Server (Flask API)** – Handles requests and stores data in AWS DynamoDB.  
3. **Admin Panel** – Allows authorities to monitor and manage reported issues.  
4. **Database (DynamoDB)** – Stores user profiles, reports, and issue statuses.

---

## 🧪 Demo Plan

The demo simulates:
- A citizen reporting an issue (e.g., pothole).  
- The report being stored in the backend.  
- An authority resolving it and marking it as *Resolved*.  
- Citizen’s app automatically updating the issue status.

You can open the demo locally by opening **`sih.html`** in your browser.

---

## 📅 Project Roadmap

| Phase | Duration | Description |
|--------|-----------|-------------|
| **Phase 1** | Month 1 | Requirement gathering and tech stack selection |
| **Phase 2** | Months 2–3 | Prototype development (frontend + backend) |
| **Phase 3** | Month 4 | Testing with limited users and feedback |
| **Phase 4** | Month 5 | Deployment in selected wards |
| **Phase 5** | Month 6+ | Scaling, AI-based issue detection, multilingual support |

---

## 🌍 Impact and Benefits

- ✅ Faster issue reporting and resolution.  
- 🔎 Transparent tracking and citizen trust.  
- 📊 Data-driven urban planning insights.  
- 🤝 Encourages citizen participation and engagement.

---

## 👥 Team Members

| Name | Role | Email |
|------|------|--------|
| **K. Vineetha** *(Team Leader)* | Frontend Developer | satyasaivineethakarri@gmail.com |
| **M. Sulochana** | Backend Developer | moyillasulochana@gmail.com |
| **M. Kalyani** | UI/UX & Integration | kalyanmadini@gmail.com |
| **P. Nagesh** | Database & Testing | pidimnagesh@gmail.com |
| **B. Jyothi** | Documentation & Presentation | srivalli070305@gmail.com |

---

## 🔗 Reference Link

[http://54.163.37.244/](http://54.163.37.244/)

---

## 🏁 Conclusion

**Clean Connect** aims to empower citizens and authorities to work together for cleaner, smarter cities.  
It combines simplicity, transparency, and technology to drive civic engagement and ensure sustainable city development.

---

## 📸 Screenshots

(Add screenshots of your web app or prototype here)

---

## 🧠 Future Enhancements

- AI-based automatic detection of civic issues from uploaded photos.  
- Integration with municipal service APIs for auto-ticketing.  
- Real-time chat between citizens and officials.  
- Reward-based gamification for active citizens.

---

## 📜 License

This project is open-source under the **MIT License**.

