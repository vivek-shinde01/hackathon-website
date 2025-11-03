
# 🚀 National Level Hackathon Website

A modern, animated, and responsive website built for a **National Level Hackathon**, designed to showcase event details, enable registrations, and highlight sponsors, judges, and prizes.

---

## 🏁 Project Overview

This project aims to create a **central platform** for hackathon participants, judges, and organizers.  
The website provides all event-related information in one place — with smooth animations, an interactive UI, and secure team/individual registration.

---

## 🎯 Purpose

To design and develop a **National Level Hackathon portal** that is:
- Visually appealing and modern (UI/UX focused)
- Fast, responsive, and mobile-friendly
- Easy to maintain and scalable for future events

---

## 🧩 Key Features

| Section | Description |
|----------|--------------|
| 🏠 **Home / Landing Page** | Overview of the hackathon with animations and event highlights |
| 📅 **Event Schedule** | Complete agenda and event timeline |
| 🧑‍💻 **Registration** | Individual or team registration using Firebase |
| 👨‍⚖️ **Judges / Sponsors** | List of judges, sponsors, and partners |
| 💡 **Problem Statements** | Display of problem statements for participants |
| 🏆 **Prizes** | Information on rewards and categories |
| 📞 **Contact / FAQ** | Help section and communication details |

---

## 🧠 Tech Stack

| Layer | Technology Used |
|-------|------------------|
| **Frontend** | React.js, Tailwind CSS, Framer Motion |
| **Backend / Database** | Firebase (Firestore + Auth) |
| **Design** | Figma |
| **Version Control** | Git + GitHub |
| **Deployment** | Netlify / Vercel |

---

## 🧱 Folder Structure

```
hackathon-website/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── utils/
│   ├── context/
│   ├── App.jsx
│   └── main.jsx
├── .gitignore
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

Follow these steps to set up the project locally 👇

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-org>/hackathon-website.git
cd hackathon-website
```

### 2️⃣ Install dependencies
```bash
npm install
```

### 3️⃣ Start the development server
```bash
npm run dev
```

### 4️⃣ Build for production
```bash
npm run build
```

### 5️⃣ Deploy
Upload the `dist/` folder to Netlify or Vercel.

---

## 🌿 Git Workflow

We are using the **Feature Branch + Pull Request** workflow.

1. Create your branch  
   ```bash
   git checkout -b feature/<task-name>
   ```
   Example: `feature/home-page`

2. Add and commit your changes  
   ```bash
   git add .
   git commit -m "Added Home Page Section"
   ```

3. Push to GitHub  
   ```bash
   git push origin feature/<task-name>
   ```

4. Open a Pull Request (PR) and assign reviewers  
   - Base branch: `main`  
   - Don’t push directly to `main`  

5. After merge, update your local main  
   ```bash
   git checkout main
   git pull origin main
   ```

---

## 👥 Team Members (9 Members)

| Role | Responsibility | Members |
|------|----------------|----------|
| 👨‍💻 **Team Lead** | Project management, reviews, merges | *Vivek Shinde* |
| 🖥️ **Frontend Developers** | Build UI, components, animations | *3 Members* |
| ⚙️ **Backend Developers** | Firebase setup, data integration | *2 Members* |
| 🎨 **UI/UX Designers** | Figma design, visual system | *2 Members* |
| 📝 **Content Writer** | Website content, FAQs, problem statements | *1 Member* |
| 🔍 **QA/Testers** | Testing, responsiveness, bug reporting | *1 Member* |

---

## 🔍 QA & Testing

Before final deployment:
- ✅ Test all routes and navigation  
- ✅ Check responsiveness (mobile, tablet, desktop)  
- ✅ Verify Firebase registration and data flow  
- ✅ Run Lighthouse audit for performance and accessibility  
- ✅ Fix UI/UX inconsistencies  

---

## 🌐 Deployment

We recommend **Vercel** for smooth CI/CD:

1. Connect GitHub repo  
2. Select `main` branch  
3. Deploy → automatic updates on every merge  

---

## 🏆 Hackathon Deliverables

- ✅ Fully responsive website  
- ✅ Functional registration form with Firebase  
- ✅ Modern animated UI (Framer Motion)  
- ✅ Deployed live version  
- ✅ Demo video and presentation slides  

---

## 💬 Contribution Guidelines

- Always pull the latest code before starting work  
- Use clear and meaningful commit messages  
- Follow component naming conventions (`PascalCase`)  
- Create a pull request for every new feature or fix  
- Don’t edit files outside your assigned scope without discussion  

---

## 📞 Contact

For queries or suggestions, contact the **Team Lead**:  
📧 vivekshinde@example.com  
📱 WhatsApp Group: [Hackathon Website Team]

---

### 💡 "Build fast, collaborate smart, and deliver beautifully."  
**— National Level Hackathon Team**
