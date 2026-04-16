
# 📊 CGPA Calculator – Syllabus-Linked GPA Tool

An interactive **Web-Based CGPA Calculator** with integrated departmental syllabi. Designed for students to import their subject data, input grades, and **calculate CGPA with real-time accuracy**. Fully client-side, no backend, just pure HTML, CSS, and JavaScript — all embedded within the HTML files.

---

## 🧠 What Is This Project?

This is a complete academic tool built to:
1. Select a department
2. View its syllabus (subjects & credits)
3. Import that data into the calculator
4. Enter grades
5. **Print/export the CGPA summary as PDF**

No separate CSS or JS files — everything is modular and **self-contained** in each `.html` page.

---

## 🗂 Project Structure

```
📁 cgpacalculator/
├── index.html         # Main Calculator Page with CGPA logic
├── department.html    # Department selector
├── cs.html            # Computer Science syllabus
├── ds.html            # Artificial Intelligence syllabus
├── ec.html            # Electronics & Communication syllabus
├── eee.html           # Electrical & Electronics syllabus
├── aiml.html          # AI & ML syllabus
├── mech.html          # Mechanical syllabus
├── civil.html         # Civil Engineering syllabus
├── README.md          # You're here
```

> 📌 *Note:* No external `styles.css` or `script.js` — all code is embedded within each HTML file.

---

## 🚀 How to Use

1. ✅ **Open `index.html`**  
   This is your main CGPA calculator interface.

2. 🧭 **Click “View Syllabus”**  
   Redirects you to `department.html`.

3. 🏫 **Choose your department**  
   Loads the selected department's syllabus page (e.g., `cs.html`, `eee.html`).

4. 📥 **Click “Import to Calculator”**  
   Transfers subject names and credits to `index.html` via **Local Storage**.

5. 🧮 **Enter your grades & calculate CGPA**  
   Uses real-time formula to give accurate results.

6. 🖨️ **Click “Print Summary”**  
   Opens a printable page of your entered grades and calculated CGPA.  
   Use your browser’s **Print to PDF** to download a **PDF copy**.

---

## 🧮 CGPA Formula

```
CGPA = (Sum of (Grade Point × Credit)) ÷ Total Credits
```

---

## 🎓 Grading System (Updated & Accurate)

| Marks Range | Grade   | Grade Point |
|-------------|---------|-------------|
| 90 - 100    | S       | 10          |
| 85 - 89     | A+      | 9.0         |
| 80 - 84     | A       | 8.5         |
| 75 - 79     | B+      | 8.0         |
| 70 - 74     | B       | 7.5         |
| 65 - 69     | C+      | 7.0         |
| 60 - 64     | C       | 6.5         |
| 55 - 59     | D       | 6.0         |
| 50 - 54     | P       | 5.5         |
| Below 50    | F       | 0.0         |

📌 *Note:* Grading policies are aligned with common standards and may vary per institution.

---

## 📤 Export Feature

- ✅ **Print Summary Button**:  
   Exports your calculated CGPA & SGPA to a **printable view**, which can be **saved as PDF** via the browser.

---

## 👨‍💻 Developer Info

Built by **Samuel M Dileep**  
🎓 Student at **MA College of Engineering (2024-2028)**

- 📧 Email: `samuelmdileep@gmail.com`  
- 💻 GitHub: [github.com/samuelmdileep](https://github.com/samuelmdileep)

---

## 🌐 Live Site

[`samuelmdileep.github.io/CGPA-calculator-KTU-MA-COLLAGE-OF-ENGINEERING-/`](https://samuelmdileep.github.io/CGPA-calculator-KTU-MA-COLLAGE-OF-ENGINEERING-/)
[`https://macecgpacalculator.netlify.app/`](https://macecgpacalculator.netlify.app/)
