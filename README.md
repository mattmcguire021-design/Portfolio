# Matthew Paul McGuire — Systems & Eco-Infrastructure Portfolio
> **Live Site:** [mattmcguire021.github.io/portfolio](https://mattmcguire021.github.io/portfolio/)  
> **Contact:** mattmcguire021@gmail.com | +1 (470) 874 - 0609 Ext. 0010

This repository houses the live, interactive portfolio of Matthew Paul McGuire. It is built as a direct, zero-friction path for recruiters, hiring managers, and engineering teams to review real-world "Evidence of Excellence" spanning civil infrastructure, renewable energy systems, hydrological modeling, and narrative systems design.

---

## 📂 Portfolio Structure & Assets

The landing page (`index.html`) is structured to present multi-media project evidence across four key pillars:

### 1. 📷 Photos & Site Mapping
*   **Purpose:** Showcases spatial planning, site layouts, and CAD models.
*   **Asset Location:** Place your Fusion 3D renders, site maps, and physical land photos in an `/images` folder within this repository.
*   **Key Project Highlighted:** I-20 West Eco-Infrastructure Hub layout (Buchanan, GA).

### 2. 🎙️ Audio & Field Records
*   **Purpose:** Houses audio logs from physical field-testing to prove empirical execution.
*   **Asset Location:** Upload your recorded stream float test audio logs to an `/audio` folder within this repository.
*   **Key Project Highlighted:** Tallapoosa Basin stream flow velocity recordings.

### 3. 📄 Literature & Briefings
*   **Purpose:** Direct access to project master plans, engineering equations, and creative screenwriting documentation.
*   **Asset Location:** Save your project PDFs or markdown briefs to a `/docs` folder within this repository.
*   **Key Projects Highlighted:** Hydrological & Micro-Grid briefings; *The WRabid* creative pitch bible.

### 4. ⏳ Project Timeline
*   **Purpose:** A chronological roadmap tracing active developments from physical land stewardship (TSI) to infrastructure planning.

---

## 🛠️ How to Add Your Assets to GitHub

To make your photos, audio, and documents live on your portfolio site, you can upload them directly through your GitHub browser interface or command line:

### Adding Images
1. Create a folder named `images` in this repository.
2. Upload your site photos or CAD screenshots (e.g., `eco-hub-render.png`).
3. In `index.html`, update the placeholder image path to:
   ```html
   <img src="images/eco-hub-render.png" alt="I-20 Eco-Hub Site Layout" />
