# TableTop Nights 🎲
> **BBF 302E Database Systems — Fall 2026 Term Project**  
> **Istanbul Technical University (İTÜ)**

TableTop Nights is a web-based community platform and game night organizer designed for board game enthusiasts. It enables players to catalog personal collections, discover fellow owners, schedule and join game nights at local venues, manage seat limits and waitlists atomically, and record match outcomes, scores, and ratings.

---

## 👥 Team ASLANLAR (CRN: 12492)

| # | Member | Student ID | E-mail | Responsibility & Assigned Tables |
|---|---|---|---|---|
| 1 | **Harun Yahya Tamar** *(Leader)* | 150240017 | tamar24@itu.edu.tr | Authentication, user accounts & admin (`users`, `user_profiles`) |
| 2 | **Osman Nurullah Okutan** | 150240064 | okutano24@itu.edu.tr | Game catalog & personal game collections (`games`, `categories`, `game_categories`, `collection_items`) |
| 3 | **Muhammet Böler** | 150240010 | boler24@itu.edu.tr | Venues & event management (`venues`, `events`) |
| 4 | **Ahmet Arif Akçay** | 150240014 | akcaya24@itu.edu.tr | Event games, attendance & waitlist (`event_registrations`, `event_games`) |
| 5 | **Efe Bekteş** | 150230002 | bektes23@itu.edu.tr | Play records, reviews & statistics (`play_sessions`, `play_results`, `game_reviews`) |

---

## 🛠️ Technology Stack

- **Primary Database:** PostgreSQL 16
- **Database Driver:** `psycopg2` (*Raw SQL queries only — ORM is strictly prohibited*)
- **Web Application:** Python 3 & Flask
- **Frontend:** Server-side rendered Jinja2 templates, Bootstrap 5, Vanilla JavaScript
- **Data Generation:** Python Faker (tr_TR locale) & Team-curated catalog datasets

---

## 📁 Project Structure & Deliverables

- `milestone1.pdf` — Approved Milestone 1 Project Proposal
- `BBF302E_Milestone2_ASLANLAR.docx` — Milestone 2 ER Diagram and Relational Schema Design
- `BBF302E_Milestone2_ASLANLAR.pdf` — Milestone 2 Document (PDF Export)
- `README.md` — Project Documentation & Contribution Guide

---

## 📌 Milestones Roadmap

- [x] **Milestone 1:** Project Proposal & Group Formation
- [x] **Milestone 2:** ER Diagram & Relational Data Model Design *(Deadline: Nov 22, 2026)*
- [ ] **Milestone 3:** Database Queries & Web App Development *(Deadline: Dec 11, 2026)*
- [ ] **Milestone 4:** Demo, Presentation & Documentation *(Deadline: Dec 22, 2026)*
