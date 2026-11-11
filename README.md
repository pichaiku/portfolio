<div align="center">

# 📂 Portfolio — Pichai Jodpimai, Ph.D.

### Business & Digital Transformation

**Enterprise Architecture · Data Governance · Applied AI & ML · Software Engineering**

[![Email](https://img.shields.io/badge/Email-pichaiku%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:pichaiku@gmail.com)
![Location](https://img.shields.io/badge/Based%20in-Bangkok%2C%20Thailand-0A66C2)
![EA/DGF](https://img.shields.io/badge/EA/DGF-3-green)
![Projects](https://img.shields.io/badge/Projects-7-orange)
![Research](https://img.shields.io/badge/publications-6-8A2BE2)
![Subjects](https://img.shields.io/badge/Subjects%20taught-7-success)

</div>

---

## 👋 About

This portfolio collects selected work from my career in digital transformation, research and teaching:

1. **[Enterprise Architecture & Data Governance](#ea-dgf)**: consulting work products for organizations
2. **[AI-Powered Software Projects](#projects)**: end-to-end mobile and web applications with AI/ML built in
3. **[Research Publications](#research)**: applied AI and machine learning
4. **[Subjects Taught](#teaching)**: lecture materials from my courses at university

---

<a name="ea-dgf"></a>

## 🏗️ Enterprise Architecture & Data Governance

| Project | Document | Edition | Organization | Role |
|---|---|---|---|---|
| **Data Governance Framework** | [DGF](https://waa.inter.nstda.or.th/stks/pub/2019/20191105-data-governance-framework-book.pdf) | Published, 88 pp. | DGA, 2019, [2021](https://www.dga.or.th/wp-content/uploads/2021/03/ราชกิจจานุเบกษา_ประกาศคกกพัฒนารัฐบาลดิจิทัล-ธรรมาภิบาลข้อมูลภาครัฐ.pdf) | DGF Consultant |
| **Enterprise Architecture (organization-wide)** | [EGA-EA-V1-Public](https://www.dga.or.th/wp-content/uploads/2015/08/file_4bd4ed97187349d235ecd5178e0e41c8.pdf) | Published, 76 pp. | EGA, 2015 | EA Consultant |
| | EGA-EA-V1-Private | Internal use only *(not published)* | EGA, 2015 | EA Consultant |
| **First Transformation Initiative: Inventory Management** | [EGA-EA-V2-Public-Inventory](https://www.dga.or.th/wp-content/uploads/2016/06/file_3650bf3f500bc967bb0fdab663be0ff4.pdf) | Published, 99 pp. | EGA, 2016 | EA Consultant |
| | EGA-EA-V2-Private-Inventory | Internal use only *(not published)* | EGA, 2016 | EA Consultant |


- **Data Governance Framework (DGF):** a guideline that government agencies, state enterprises and public organizations can adapt to their own context. It is also applicable to the private sector.
- **Enterprise Architecture (EA):** an organization-wide blueprint for the Electronic Government Agency (EGA), built on a framework combining Zachman, TOGAF and FEA. It covers As-Is analysis across Business, Application, Data, Infrastructure and Security, To-Be design, gap analysis and a transformation roadmap.
- **First Transformation Initiative:** the first initiative delivered from the EA roadmap, covering process redesign and technology transformation of inventory management.


---

<a name="projects"></a>

## 🤖 AI-Powered Software Projects

End-to-end software that takes AI and machine learning models from training to working mobile and web apps, each with a model, an API and client apps. Click a project name to open its repository.

| Project | Description | AI / ML Integration | Platforms | Tech Stack |
|---|---|---|---|---|
| 💬&nbsp;**[ChatMate](https://github.com/pichaiku/chatmate)** | AI chat assistant that sends and receives messages over WebSocket, renders responses as Markdown and stores chat history. | **Generative AI (LLM)**<br/>Google Gemini via the Gen AI SDK | Mobile, Web | Flutter, Next.js, FastAPI, MySQL |
| 🌟&nbsp;**[CelebMatch&nbsp;AI](https://github.com/pichaiku/celeb)** | Celebrity lookalike finder: scan live with the camera or upload a photo to see the closest celebrity match with a confidence breakdown. Photos never leave the device. | **Computer vision**<br/>CNN image classification with BlazeFace face detection, run on-device / in-browser | Mobile, Web | Flutter, TensorFlow Lite, ONNX Runtime Web, TensorFlow.js |
| 🩻&nbsp;**[DeepXRay](https://github.com/pichaiku/deep_xray)** | Chest X-ray analysis: capture or select an X-ray image and get the three most likely findings with confidence scores and descriptions. | **Computer vision**<br/>Chest X-ray classification with PyTorch and TorchXRayVision | Mobile | Flutter, Flask, Docker Compose |
| 🧑‍💼&nbsp;**[FaceEntryX](https://github.com/pichaiku/faceentry)** | Face recognition attendance system: one app registers employees, the other scans faces every 3 seconds, greets recognized employees by voice in Thai and logs attendance. | **Face recognition**<br/>128-dimension face encodings and matching with face_recognition (dlib) | Mobile | Flutter, Flask, MySQL |
| 🫁&nbsp;**[LungEcho](https://github.com/pichaiku/lung_echo)** | Preliminary COPD risk screening from breath and cough sounds: record a short clip and get a risk level from COPD0 (low) to COPD4 (very severe) with per-level probabilities. Includes a PDPA/GDPR consent flow, and recordings are never stored. | **Audio classification**<br/>CNN on mel spectrograms (TensorFlow/Keras, librosa) | Mobile | Flutter, FastAPI, TensorFlow |
| 🏠&nbsp;**[House&nbsp;Price&nbsp;Prediction](https://github.com/pichaiku/house_price)** | Estimates house prices (THB per sq. m.) from the property's age, distance to an MRT station and the number of nearby convenience stores, served through a validated REST API. | **Regression**<br/>Linear Regression model trained with scikit-learn | Mobile, Web | Flutter, Next.js, Flask, Pydantic |
| 🛍️&nbsp;**[Shopdee](https://github.com/pichaiku/shopdee)** | Full-stack online clothing store with cart, credit-card (Omise) and bank-transfer payments, and an admin dashboard. Runs on Docker Compose behind nginx with Prometheus/Grafana monitoring, e-mail/LINE alerts and automated API, end-to-end, performance and usability tests. | **Recommendation system**<br/>KNN personal picks from purchase history (scikit-learn), topped up with best sellers | Mobile, Web | Next.js, Flutter, Express, Flask, MySQL, Docker, Grafana |

Together, the projects cover generative AI, computer vision, face recognition, audio classification, regression, and recommendation systems.

---

<a name="research"></a>

## 🔬 Research Publications: Applied AI & Machine Learning

| # | Title | Venue | Year | Application · Technique |
|:-:|---|---|:-:|---|
| 1 | [Appendicitis Disease Diagnosis using Machine Learning Techniques](https://nccit.net/wp-content/uploads/2023/09/Proceeding-of-NCCIT2021.pdf) | NCCIT 2021, KMUTNB | 2021 | Healthcare · Machine Learning, Classification |
| 2 | [Predicting Recidivism to Drug Distribution using Machine Learning Techniques](https://doi.org/10.1109/ICTKE47035.2019.8966834) | ICT&KE 2019, IEEE | 2019 | Safety & Justice · Feature selection, Machine Learning, Classification |
| 3 | [Re-estimating Software Effort using Prior Phase Efforts and Data Mining Techniques](https://doi.org/10.1007/s11334-018-0311-z) | Innovations in Systems and Software Engineering, 14, Springer | 2018 | Project effort · Outlier detection, Feature selection, Data Transformation, Machine Learning, Estimation |
| 4 | [Ensemble Effort Estimation using Selection and Genetic Algorithms](https://doi.org/10.1504/IJCAT.2018.094061) | Int. J. of Computer Applications in Technology, 58(1), Inderscience | 2018 | Project effort · Machine Learning, Genetic algorithm, Ensemble learning, Estimation |
| 5 | [Estimating Software Effort with Minimum Features using Neural Functional Approximation](https://doi.org/10.1109/ICCSA.2010.63) | ICCSA 2010, IEEE | 2010 | Project effort · Feature selection, Neural network, Estimation |
| 6 | [Analysis of Effort Estimation based on Software Project Models](https://doi.org/10.1109/ISCIT.2009.5341149) | ISCIT 2009, IEEE | 2009 | Project effort · Analysis, Estimation  |

All six papers apply AI and machine learning to real-world problems. Papers 3–6 come from my Ph.D. research at Chulalongkorn University on software effort estimation. Highlight: in paper 1, SVM with symptom factors reached **95% accuracy** in diagnosing appendicitis.

---

<a name="teaching"></a>

## 🎓 Subjects Taught

Rajamangala University of Technology Tawan-ok (RMUTTO), 2018–2026. Click a number to open that lecture (PDF).

| Subject | Topics | Lectures |
|---|---|---|
| 🤖 **Artificial Intelligence**<br/>[`subjects/AI`](https://github.com/pichaiku/subjects/tree/main/AI) | Python, machine learning, deep learning, house-price prediction, recommendation systems (ML model → API → web app) | [01](https://github.com/pichaiku/subjects/tree/main/AI/AI-01.pdf) · [02](https://github.com/pichaiku/subjects/tree/main/AI/AI-02.pdf) · [03](https://github.com/pichaiku/subjects/tree/main/AI/AI-03.pdf) · [04](https://github.com/pichaiku/subjects/tree/main/AI/AI-04.pdf) · [05](https://github.com/pichaiku/subjects/tree/main/AI/AI-05.pdf) · [06](https://github.com/pichaiku/subjects/tree/main/AI/AI-06.pdf) |
| 📊 **Data Science**<br/>[`subjects/DS`](https://github.com/pichaiku/subjects/tree/main/DS) | Python, data collection & EDA, missing values, data transformation, outlier detection, feature engineering, classification, regression, clustering, association rules | [01](https://github.com/pichaiku/subjects/tree/main/DS/DS-01.pdf) · [02](https://github.com/pichaiku/subjects/tree/main/DS/DS-02.pdf) · [03](https://github.com/pichaiku/subjects/tree/main/DS/DS-03.pdf) · [04](https://github.com/pichaiku/subjects/tree/main/DS/DS-04.pdf) · [05](https://github.com/pichaiku/subjects/tree/main/DS/DS-05.pdf) · [06](https://github.com/pichaiku/subjects/tree/main/DS/DS-06.pdf) · [07](https://github.com/pichaiku/subjects/tree/main/DS/DS-07.pdf) · [08](https://github.com/pichaiku/subjects/tree/main/DS/DS-08.pdf) · [09](https://github.com/pichaiku/subjects/tree/main/DS/DS-09.pdf) · [10](https://github.com/pichaiku/subjects/tree/main/DS/DS-10.pdf) · [11](https://github.com/pichaiku/subjects/tree/main/DS/DS-11.pdf) |
| 📈 **Business Intelligence**<br/>[`subjects/BI`](https://github.com/pichaiku/subjects/tree/main/BI) | Business understanding & requirements, data collection & storage, data cleansing & integration, reports and dashboards | [01](https://github.com/pichaiku/subjects/tree/main/BI/BI-01.pdf) · [02](https://github.com/pichaiku/subjects/tree/main/BI/BI-02.pdf) · [03](https://github.com/pichaiku/subjects/tree/main/BI/BI-03.pdf) · [04](https://github.com/pichaiku/subjects/tree/main/BI/BI-04.pdf) · [05](https://github.com/pichaiku/subjects/tree/main/BI/BI-05.pdf) |
| 🛠️ **Software Engineering**<br/>[`subjects/SE`](https://github.com/pichaiku/subjects/tree/main/SE) | Software processes, system modeling, requirements engineering, architectural & detailed design, UI design, QA & testing, project management | [01](https://github.com/pichaiku/subjects/tree/main/SE/SE-01.pdf) · [02](https://github.com/pichaiku/subjects/tree/main/SE/SE-02.pdf) · [03](https://github.com/pichaiku/subjects/tree/main/SE/SE-03.pdf) · [04](https://github.com/pichaiku/subjects/tree/main/SE/SE-04.pdf) · [05](https://github.com/pichaiku/subjects/tree/main/SE/SE-05.pdf) · [06](https://github.com/pichaiku/subjects/tree/main/SE/SE-06.pdf) · [07](https://github.com/pichaiku/subjects/tree/main/SE/SE-07.pdf) · [08](https://github.com/pichaiku/subjects/tree/main/SE/SE-08.pdf) · [09](https://github.com/pichaiku/subjects/tree/main/SE/SE-09.pdf) |
| 📱 **Mobile Application Development**<br/>[`subjects/Mobile`](https://github.com/pichaiku/subjects/tree/main/Mobile) | Mobile app concepts, Dart, Flutter front-end (Material Design, widgets), back-end APIs (CRUD, register/login) | [01](https://github.com/pichaiku/subjects/tree/main/Mobile/Mobile-01.pdf) · [02](https://github.com/pichaiku/subjects/tree/main/Mobile/Mobile-02.pdf) · [03](https://github.com/pichaiku/subjects/tree/main/Mobile/Mobile-03.pdf) · [04](https://github.com/pichaiku/subjects/tree/main/Mobile/Mobile-04.pdf) |
| ⚖️ **Computer Law & Ethics**<br/>[`subjects/Law`](https://github.com/pichaiku/subjects/tree/main/Law) | PDPA, Computer Crime Act, Cybersecurity Act, Electronic Transactions Act, computer security, secure web development (JavaScript, TypeScript, front-end, back-end) | [01](https://github.com/pichaiku/subjects/tree/main/Law/Law-01.pdf) · [02](https://github.com/pichaiku/subjects/tree/main/Law/Law-02.pdf) · [03](https://github.com/pichaiku/subjects/tree/main/Law/Law-03.pdf) · [04](https://github.com/pichaiku/subjects/tree/main/Law/Law-04.pdf) · [05](https://github.com/pichaiku/subjects/tree/main/Law/Law-05.pdf) · [06](https://github.com/pichaiku/subjects/tree/main/Law/Law-06.pdf) · [07](https://github.com/pichaiku/subjects/tree/main/Law/Law-07.pdf) · [08](https://github.com/pichaiku/subjects/tree/main/Law/Law-08.pdf) · [09](https://github.com/pichaiku/subjects/tree/main/Law/Law-09.pdf) · [10](https://github.com/pichaiku/subjects/tree/main/Law/Law-10.pdf) · [11](https://github.com/pichaiku/subjects/tree/main/Law/Law-11.pdf) |
| 🔬 **Research Methodology**<br/>[`subjects/RS`](https://github.com/pichaiku/subjects/tree/main/RS) | Principles of research, data collection & analysis, research proposal writing, research writing and publication | [01](https://github.com/pichaiku/subjects/tree/main/RS/RS-01.pdf) · [02](https://github.com/pichaiku/subjects/tree/main/RS/RS-02.pdf) · [03](https://github.com/pichaiku/subjects/tree/main/RS/RS-03.pdf) · [04](https://github.com/pichaiku/subjects/tree/main/RS/RS-04.pdf) · [05](https://github.com/pichaiku/subjects/tree/main/RS/RS-05.pdf) |

The subjects cover the full path from programming and software engineering to data, AI and real-world deployment, including the legal and ethical side of technology.

---

<div align="center">

📬 **Contact:** [pichaiku@gmail.com](mailto:pichaiku@gmail.com) · [Google Scholar](https://scholar.google.com/citations?hl=th&user=0PylMxYAAAAJ)

</div>
