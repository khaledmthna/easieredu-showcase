# EasierEdu – Interactive English Learning Platform

<p align="center">
  <strong>Learn English. Practice with AI. Build Real-World Confidence.</strong>
</p>

<p align="center">
  <a href="https://easieredu.com/"><img src="https://img.shields.io/badge/Website-easieredu.com-blue?style=flat-square&logo=googlechrome" alt="Website" /></a>
  <a href="https://www.youtube.com/@EasierEduc"><img src="https://img.shields.io/badge/YouTube-EasierEdu-red?style=flat-square&logo=youtube" alt="YouTube" /></a>
  <a href="https://www.linkedin.com/in/khaled-mthna-280801359/"><img src="https://img.shields.io/badge/Founder-LinkedIn-0077B5?style=flat-square&logo=linkedin" alt="LinkedIn" /></a>
  <a href="https://github.com/khaledmthna"><img src="https://img.shields.io/badge/GitHub-khaledmthna-181717?style=flat-square&logo=github" alt="GitHub" /></a>
</p>

---

## 📌 About EasierEdu

**EasierEdu** is a production-grade, interactive English-learning platform engineered to guide learners from foundational basics to fluent communication. It bridges structured curriculum design with real-time, multimodal AI-assisted conversation practice.

* **Live Platform:** [https://easieredu.com/](https://easieredu.com/)
* **Trial Experience:** Frictionless Guest Mode available for immediate lesson and roleplay practice.

---

## 🚀 Key Features

* **Structured Learning Curriculum:**
  * 700+ CEFR-aligned structured lessons across beginner to advanced proficiency tracks.
  * Step-by-step modular progression focusing on functional grammar and lexical acquisition.
* **Multilingual Accessibility:**
  * Native translation scaffolding supporting learners across 45 native languages.
  * Real-time word hints and cross-lingual conceptual explanations.
* **Audio-Assisted Learning & Phonetics:**
  * High-fidelity speech synthesis for natural pronunciation modeling.
  * Integrated listening comprehension tasks and vocal active recall.
* **Dynamic Assessment Engine:**
  * Modular JSON schema architecture handling multi-type evaluation: Fill-in-the-blank (`___`), relational token matching, syntax ordering (`ArrangeSentence`), and multiple-choice challenges.
  * 4-stage active-recall challenge engine with dynamic re-sampling.
* **Multimodal AI Conversational Coach:**
  * Adaptive AI roleplay across 23 real-world scenarios (workplace, travel, academic, social).
  * Real-time error correction, context-aware suggestions, and speech evaluation.

---

## 🛠 Technology Stack

| Area | Technologies & Services |
| :--- | :--- |
| **Backend & Microservices** | ASP.NET Core, C# (.NET 8/9) |
| **API Gateway & Routing** | YARP (Yet Another Reverse Proxy), REST APIs |
| **Database & Persistence** | PostgreSQL, Entity Framework Core |
| **Frontend Web** | ASP.NET Core MVC, Responsive Modern UI |
| **Cross-Platform Mobile** | .NET MAUI |
| **Cloud Infrastructure** | Google Cloud (Cloud Run, Compute Engine, Cloud Storage) |
| **AI & Speech Layer** | Google Cloud Vertex AI (Gemini Models), Cloud Speech-to-Text, Cloud Text-to-Speech |
| **Identity & Security** | ASP.NET Core Identity, JWT, Firebase Auth |

---

## 🏗 System Architecture

The ecosystem operates on decoupled, independently scalable components:
* **Identity Service:** Multi-tenant credential verification, JWT lifecycle, and user profile management.
* **Curriculum & Lessons Engine:** Delivers dynamic JSON-backed syllabus, multilingual metadata, and scoring algorithms.
* **Conversation Hub:** Real-time conversational pipeline handling audio transcription, prompt orchestration, and synthetic voice feedback.
* **API Gateway (YARP):** Secure single point of entry orchestrating microservice communication and load distribution.

---

## 🗺 Roadmap

- [x] Live web production deployment with frictionless guest onboarding.
- [x] Deployment of 700+ interactive lessons with dynamic evaluation schemas.
- [x] Real-time conversational AI speaking coach across 23 topics.
- [ ] Cross-platform mobile release via .NET MAUI.
- [ ] Multidirectional language matrix (expanding pedagogy beyond English to all supported languages).
- [ ] Advanced phoneme-level speech evaluation via custom neural pipelines.

---

## 👤 Founder & Leadership

**Khaled Mthna**  
*Founder & Lead Software Engineer*  

Responsible for end-to-end product architecture, microservices engineering, and cloud deployment for EasierEdu.

* **LinkedIn:** [linkedin.com/in/khaled-mthna-280801359](https://www.linkedin.com/in/khaled-mthna-280801359/)
* **GitHub:** [github.com/khaledmthna](https://github.com/khaledmthna)
* **Email:** [admin@easieredu.com](mailto:admin@easieredu.com)

---

<p align="center">
  <sub>EasierEdu © 2026. Empowering global communication through intelligent learning.</sub>
</p>
