# ArogyaMitra – AI Wellness Assistant

ArogyaMitra is an AI-powered wellness assistant designed to help users maintain a healthy lifestyle through personalized **workout plans, nutrition guidance, and AI-based health coaching**. The system uses modern web technologies and AI services to generate recommendations tailored to the user’s fitness goals, activity level, and dietary preferences.

This project was developed as part of the **SmartBridge Agentic AI Program in collaboration with IBM**.

---

# 🚀 Features

* 🤖 **AI Health Coach (AROMI)** – Conversational assistant for wellness guidance
* 🏋️ **Workout Plan Generator** – Personalized weekly workout routines
* 🥗 **Nutrition Planner** – AI-generated meal plans based on calorie targets
* 🔐 **Authentication System** – Secure login and user profile management
* 📊 **User Health Profile** – Stores activity level, injuries, and preferences
* 🧠 **Agentic AI Architecture** – AI services orchestrated for decision making

---

# 🏗 Project Architecture

The project is divided into two main components:

```
ArogyaMitra
│
├── backend        → FastAPI + AI services
│
├── frontend       → Web UI
│
└── README.md
```

### Backend

Handles:

* API endpoints
* AI integrations
* workout/nutrition planning
* database management

### Frontend

Handles:

* User interface
* API communication
* displaying workout and nutrition plans
* AI chat interaction

---

# ⚙️ Backend Setup (Local Deployment)

### 1️⃣ Clone the repository

```bash
git clone <repository-url>
cd arogyamitra
```

---

### 2️⃣ Navigate to backend folder

```bash
cd backend
```

---

### 3️⃣ Create virtual environment

```bash
python -m venv venv
```

Activate environment:

**Windows**

```bash
venv\Scripts\activate
```

**Mac / Linux**

```bash
source venv/bin/activate
```

---

### 4️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

### 5️⃣ Configure environment variables

Create a `.env` file inside the backend directory.

Example:

```env
GROQ_API_KEY=your_groq_api_key
DATABASE_URL=sqlite:///./arogyamitra.db
SECRET_KEY=your_secret_key
```

---

### 6️⃣ Run backend server

```bash
uvicorn app.main:app --reload
```

Server will start at:

```
http://127.0.0.1:8000
```

API documentation:

```
http://127.0.0.1:8000/docs
```

---

# 💻 Frontend Setup (Local Deployment)

### 1️⃣ Navigate to frontend folder

```bash
cd frontend
```

---

### 2️⃣ Install dependencies

If the frontend uses **Node.js**:

```bash
npm install
```

---

### 3️⃣ Start frontend server

```bash
npm run dev
```

or

```bash
npm start
```

Frontend will typically run at:

```
http://localhost:3000
```

---

# 🔗 Connecting Frontend and Backend

Ensure the frontend API configuration points to:

```
http://127.0.0.1:8000
```

Example:

```javascript
const API_BASE_URL = "http://127.0.0.1:8000";
```

---

# 🧠 AI Components Used

* **Groq LLM API**
* Agentic AI architecture
* Prompt-driven task generation
* Structured JSON outputs

---

# 📚 Technologies Used

### Backend

* Python
* FastAPI
* SQLAlchemy
* Pydantic
* Groq AI API

### Frontend

* HTML / CSS / JavaScript
* React
* REST API communication

### Tools

* Git
* GitHub
* VS Code
* Postman / Swagger

---

# 👨‍💻 Contributors

Developed by students as part of the:

**SmartBridge Agentic AI Program in collaboration with IBM**

* Utsav Kumar – Team Lead
* Sonal Gupta
* Sanchita Jha
* Satyam Vats

---

# 📜 License

This project is created for **educational purposes under the SmartBridge + IBM Agentic AI program**.
