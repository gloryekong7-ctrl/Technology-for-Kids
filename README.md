# Tech for Kids 🚀

A free, fully-featured Learning Management System (LMS) built for primary and secondary school students. Designed to bring structured technology education to schools that cannot afford commercial platforms.

---

## 🌍 Background

Most schools in Nigeria and across West Africa rely on expensive commercial LMS platforms — or have no digital learning system at all. **Tech for Kids** was built as a free, open-source alternative, purpose-built for the African school context.

It was initially deployed at a private school in Nigeria serving **141 students** across Grades 3 through SSS 3, replacing a paid software subscription entirely. Students now track their learning progress, earn digital certificates, and teachers and administrators have full visibility into class performance — all at zero cost.

---

## ✨ Features

### 👩‍🎓 Student Portal
- Personalised dashboard showing progress across all courses
- Lesson-by-lesson completion tracking
- Interactive quiz system with instant scoring and feedback
- Digital certificate generation on course completion (printable)
- Full activity log with timestamps
- Simple 4-digit login system — no passwords to forget

### 🔐 Admin Panel
- Real-time overview of all 141+ students
- Course completion rates and class averages
- Per-student drill-down with progress, quiz scores, and activity log
- Certificate management — view and print certificates for any student
- Announcement system for school-wide communications
- Course management with upload date tracking
- Activity log across all students with search and filter

### 📚 Courses Included (28 lessons total)
| Course | Lessons | Topics |
|--------|---------|--------|
| 🛡️ Internet Safety | 4 | Online safety, digital citizenship, finding information |
| 💻 Using Devices | 4 | Hardware, input/output, storage, device care |
| ⚙️ Basic Coding | 6 | Algorithms, loops, variables, conditions, functions, debugging |
| 📊 Building Dashboards | 5 | Data visualisation, charts, reading data, real-world applications |
| 🎨 Creative Tools | 4 | Digital creativity, presentations, images, video and audio |
| 📋 Spreadsheets & Data | 5 | Formulas, data entry, charts, real-world projects |

---

## 🛠️ Tech Stack

- **React 18** — component-based UI
- **JSX** — templating
- **In-browser state** — no backend required, no database, no server
- **CSS-in-JS** — inline styles, zero external CSS dependencies
- **Google Fonts** — Nunito typeface

The entire application runs as a **single JSX file**. There is no build step, no npm install, no server. It runs anywhere React runs.

---

## 🚀 Getting Started

### Option 1: Run Locally
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/tech-for-kids.git
cd tech-for-kids

# Install dependencies
npm install

# Start development server
npm start
```

### Option 3: Direct HTML
The JSX can be wrapped in a standard HTML file with React loaded from CDN and opened directly in any browser. See `index.html` for the template.

---

## 📁 Project Structure

```
tech-for-kids/
├── TechForKids_GitHub.jsx    # Main application (student + admin portal)
├── TechForKidsDashboard.jsx  # Standalone admin dashboard version
├── README.md
└── LICENSE
```

---

## 📊 Impact

| Metric | Value |
|--------|-------|
| Students using the platform | 141 |
| School year groups covered | Grades 3 – SSS 3 |
| Courses available | 6 |
| Total lessons | 28 |
| Certificates issued | Based on course completion |
| Cost to school | £0 |

---

## 🔑 Demo Login

Open the app and use the **Student** tab:

| Code | Name | Class |
|------|------|-------|
| `1001` | Demo Student 1 | Grade 3 |
| `1002` | Demo Student 2 | Grade 3 |
| `1003` | Demo Student 3 | Grade 3 |

For **Admin** access:
- ID: `ADMIN001`
- Password: `admin123`

> ⚠️ This demo uses fictional student data. The production version uses real student records managed by the school.

---

## 🔒 Data & Privacy

This public repository uses **entirely fictional student data** generated for demonstration purposes. No real student names, IDs, or personal information are included. The production deployment at the school uses real data managed securely on school-controlled devices.

---

## 🤝 Contributing

Contributions are welcome. If you run a school and would like to adapt this for your context, open an issue or submit a pull request.

Areas where contributions would be most valuable:
- Additional courses and lessons
- Offline/PWA support
- Multi-language support (Yoruba, Igbo, Hausa, French)
- Backend/database version for larger deployments
- Mobile app wrapper

---

## 📄 Licence

MIT License — free to use, modify and distribute.

---

## 👤 Author

Built by **Glory Ekong**, a technology educator based in Nigeria. Created to demonstrate that world-class educational technology does not require a world-class budget.

*If you are using this platform at your school, I would love to hear from you.*

---

## 🏫 Acknowledgements

Originally deployed at a private international school in Nigeria. Thanks to the students and staff who tested and gave feedback throughout development.
