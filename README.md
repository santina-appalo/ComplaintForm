
# 📋 Sathyabama Disciplinary Complaint System

A simple web-based complaint form developed to monitor and manage disciplinary violations at **Sathyabama Institute of Science and Technology (Deemed to be University)**.

## 🧾 Description

This is a frontend-only project (HTML, CSS, JavaScript) that allows faculty and administrators to log complaints regarding student disciplinary actions like:
- Not carrying ID card
- Dress code violations
- Late coming
- Bunking classes
- Others (custom input)

Users can auto-fill student details by entering the register number (mocked function for now), select the nature of the complaint, and submit the form.

---

## 🛠️ Technologies Used

- **HTML5**  
- **CSS3** (Custom styling and Bootstrap 4)
- **JavaScript** (DOM manipulation, form handling)

---

## 📂 Project Structure

```
📁 Project Folder
├── 📄 pg2.html          # Main complaint form UI
├── 📄 pg2.css           # Styling for the form and layout
├── 📄 pg2.js            # JavaScript for fetching student details (placeholder)
├── 📁 Media
│   └── satlogo.jpg      # Sathyabama logo used in header
```

> Note: File paths in the HTML are local (e.g., `C:\Users\...`). These should be relative (`./Media/satlogo.jpg`) when hosting or deploying.

---

## 🔧 Features

- 🧾 Complaint categories via checkboxes  
- 🧠 Auto-fill student name and class based on register number  
- 🖊 Custom complaint textbox (shows up when “Other” is checked)  
- 📱 Responsive design for mobile and desktop  
- 🎨 Clean UI using Bootstrap 4 and custom CSS  

---

## 🚀 How to Use

1. Open `pg2.html` in a browser.
2. Enter a valid register number and click **Fetch Details**.
3. Fill in the complaint details.
4. Click **Submit** (currently non-functional – no backend).

> **Note:** The system currently uses a placeholder `fetchStudentDetailsFromServer()` function. Integrate with your backend to fetch student data dynamically.

---

## 🛡️ Purpose

This tool is designed to support internal staff in quickly logging and reporting disciplinary issues, ensuring swift documentation and action as per **Sathyabama’s code of conduct**.

---

## 📷 Screenshot

![Complaint Form Screenshot](satlogo.jpg)

---

## ⚠️ Future Improvements

- Connect to real-time student database/backend
- Export complaints to PDF or database
- Admin dashboard for complaint review
- Email/SMS notifications

---

## 🏫 Institution

**Sathyabama Institute of Science and Technology**  
(Deemed to be University)  
Category - 1 University by UGC  
Motto: *Justice | Peace | Revolution*
