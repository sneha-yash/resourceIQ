# 🚀 ResourceIQ Hackathon Prototype Plan (1 Week)

## 🎯 Goal
Build a working prototype of **ResourceIQ** that demonstrates:
- ✅ AI-driven skill matching
- ✅ Predictive staffing analytics
- ✅ Basic UI for RMG to view candidate matches and skill gaps

---

## 🗓️ Day-by-Day Breakdown

### 🛠️ Day 1: Setup & Planning
- Finalize tech stack:
  - **Frontend**: React.js + TypeScript, Redux Toolkit
  - **Backend**: Express.js (Node.js)
  - **ML**: LangChain + Sentence-BERT
  - **Databases**: PostgreSQL (structured), Pinecone (vector), MongoDB (unstructured)
- Define MVP scope:
  - Skill extraction from resumes/project briefs
  - Candidate matching with scoring
  - Skill gap analysis with mock training suggestions
- Prepare mock data:
  - Sample resumes (JSON or PDF)
  - Project briefs with skill requirements
  - Skill taxonomy (tech, domain, soft skills)

---

### 🧠 Day 2: Backend & ML Foundations
- Implement NLP pipeline using Sentence-BERT for skill extraction
- Set up Pinecone vector DB for storing skill embeddings
- Build basic matching algorithm using cosine similarity
- Create APIs:
  - `POST /matchCandidates`
  - `POST /extractSkills`
  - `GET /getSkillGaps`

---

### 🎨 Day 3: Frontend UI
- Create React UI with:
  - 📄 Project Brief Input
  - 👤 Candidate Profile Viewer
  - 📊 Match Results Dashboard
- Use D3.js or Chart.js for visualizing:
  - Skill match scores
  - Skill gap radar charts

---

### 🔗 Day 4: Integration
- Connect frontend to backend via REST APIs
- Enable real-time updates using WebSocket (optional)
- Add basic authentication and session management with Redis

---

### 📚 Day 5: Skill Gap Analysis & Learning Path
- Implement logic to identify missing skills per candidate
- Suggest mock training paths (static recommendations)
- Display ROI and progress tracking using charts

---

### 🧪 Day 6: Testing & Polish
- Test end-to-end flow:
  - Input project brief → Get matched candidates → View skill gaps
- Polish UI/UX
- Add basic logging and analytics (ELK stack optional)

---

### 🎥 Day 7: Demo Prep
- Prepare demo script and walkthrough
- Highlight key outcomes:
  - ⏱️ Time-to-staff reduction
  - 🎯 Match accuracy
  - 🚀 Career mobility insights
- Optional: Record demo video

---

## 🧩 Key Features to Showcase

| Feature                     | Description                                                  |
|----------------------------|--------------------------------------------------------------|
| 🔍 NLP Skill Extraction     | Extract skills from resumes and project briefs               |
| 🧠 AI Matching              | Match candidates using semantic similarity and scoring       |
| 📊 Skill Gap Analysis       | Identify missing skills and suggest training paths           |
| 📈 Predictive Analytics     | Forecast staffing needs from project pipeline                |

---

## 📁 Optional Add-ons
- GitHub folder structure
- OpenAPI spec for backend APIs
- Sample resume/project brief JSON templates

---

> Built with ❤️ for the Hackathon by Team ResourceIQ
