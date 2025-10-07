# 🏙️ CivicFix — Crowdsourced Civic Issue Reporting and Resolution System  
_A Smart India Hackathon 2025 Project_  

### 🧠 Problem Statement
**Problem ID:** 25031  
**Theme:** Clean & Green Technology  
**Problem Title:** Crowdsourced Civic Issue Reporting and Resolution System  
**Team Name:** IssueBusters  

---

## 📋 Project Summary

**CivicFix** is a crowdsourced platform that allows citizens to **report civic issues** such as potholes, garbage, or water leaks using a simple and intuitive interface.  
The system integrates **AI/ML models** to automatically classify issues, detect severity, and route them to the relevant departments.  
Each report generates a **unique ticket ID** with **real-time status tracking**, ensuring transparency and accountability.  

It was developed as part of **Smart India Hackathon 2024**, and our solution was **selected in internal evaluation** for its innovation and feasibility.

---

## 🌟 Key Features

- 🧾 **Simplified Reporting** — Citizens can easily report issues with images, GPS, and short descriptions.  
- 🤖 **AI-Powered Classification** — Automatically categorizes issues and assigns them to the right department.  
- 📍 **Location Tagging** — Uses Google Maps API for geolocation and hotspot mapping.  
- 🔄 **Duplicate Detection** — Merges repeated reports of the same issue to prevent redundancy.  
- 📊 **Authority Dashboard** — Displays reported issues by location and category for quick action.  
- 🕓 **Real-Time Tracking** — Users can monitor their complaint’s progress through unique ticket IDs.  
- 🔔 **Notifications** — Citizens get updates through Firebase Cloud Messaging.  
- 🧮 **Analytics & Reports** — Heatmaps, charts, and performance tracking for authorities.

---

## ⚙️ Technical Approach

| Phase | Description |
|--------|-------------|
| **1️⃣ Data Collection & Preprocessing** | Collected civic issue images (potholes, garbage, leaks, etc.), annotated them, and built labeled datasets. |
| **2️⃣ AI Model Development** | Used TensorFlow for image classification and severity detection. |
| **3️⃣ Web/App Integration** | Built responsive web & mobile interfaces using ReactJS and Node.js. |
| **4️⃣ Smart Routing** | Auto-forwarded categorized complaints to relevant authorities. |
| **5️⃣ Feedback Loop** | Used status updates and crowd validation to improve data accuracy. |

---

## 🧰 Tech Stack

| Category | Technologies Used |
|-----------|-------------------|
| **Frontend** | React.js, HTML, CSS, JavaScript |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **Cloud** | AWS |
| **AI/ML** | TensorFlow |
| **Maps & Location** | Google Maps API |
| **Notifications** | Firebase Cloud Messaging |

---

## 🧩 Feasibility & Challenges

**Feasibility:**  
Lightweight AI deployment ensures easy scalability for cities of various sizes.  

**Challenges & Solutions:**  
- 🚫 **Fake Reports:** Filtered using crowd validation (upvotes/flags) and anomaly detection.  
- 🔒 **Data Privacy:** Used image blurring and encrypted data storage.  
- 🗣️ **Citizen Adoption:** Enabled multi-channel access (App, Web, WhatsApp, IVR).  
- ⏱️ **Delayed Responses:** Introduced escalation system and public dashboards for transparency.  
- 📈 **Model Accuracy:** Continuous learning using feedback and active retraining.

---

## 🌍 Impact & Benefits

| Stakeholder | Benefit |
|--------------|----------|
| **Citizens** | Easy issue reporting, real-time updates, and community empowerment. |
| **Authorities** | Reduced manual sorting, AI-classified inputs, and actionable dashboards. |
| **Society** | Cleaner infrastructure, transparent governance, and improved civic engagement. |

---

## 🧑‍💻 Team — *IssueBusters*

| Name | Role |
|------|------|
| **Shivani Chaudhary** | Backend Developement(admin pannel) |
| **Daksh Verma** |AI Integration |
| **Nishtha Dobhaal** | Backend Developement(user pannel) |
| **Samriddhi Mishra** | frontend Developement |
| **Rishab Rana** | frontend Developement |
| **Kamaldeep Soni** | frontend Developement |

---

## 🖼️ Screenshots

| Citizen Interface | Authority Dashboard |
|-------------------|---------------------|
| ![Citizen UI](https://github.com/user-attachments/assets/655613c4-d956-436d-aa01-52d6a6aed770)|
| ![Admin Dashboard](https://github.com/user-attachments/assets/ee9dd306-0f3e-4a04-8a87-e272451d2d36)|
| ![Dashboard](https://github.com/user-attachments/assets/5198c1ad-c7b4-41ec-bf57-3a8b6a0db6c4)

---

## 🧠 Research References

- [ResearchGate Paper](https://bit.ly/4mQtWwP)  
- [RaastaFix (Gurgaon)](https://bit.ly/42k8kk2)

---

## ⚠️ Disclaimer

This project was developed under **Smart India Hackathon 2025** for educational and research purposes only.  
All data, models, and assets used belong to their respective owners.  
No commercial usage intended.

---

## ✨ Author & Contact

**Shivani Chaudhary** — [LinkedIn](https://www.linkedin.com/in/shivani-chaudhary-b78317296) | [GitHub](https://github.com/officialshivanichaudhary)  


📧 Email: [shivanichaudhary664157@mail.com](mailto:shivanichaudhary664157@mail.com)

---

⭐ *If you found this project inspiring, give it a star and share feedback!*
