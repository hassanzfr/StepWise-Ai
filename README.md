# StepWise 🧠
# ![Logo](./Frontend/src/logo.png)

**Note:** This project was done in collaboration with [Jalees Bajwa](https://github.com/jaleesbajwa55) at WinHacks Hackathon, [Repository](https://github.com/jaleesbajwa55/StepWise) was used for coding from same workingspace. This is a refined repository for archiving the project and presenting it.

### Built With 🔧  

![React](https://img.shields.io/badge/React-%2361DAFB.svg?style=for-the-badge&logo=react&logoColor=black)  ![Flask](https://img.shields.io/badge/Flask-%23000000.svg?style=for-the-badge&logo=flask&logoColor=white) ![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white)  ![ICalendar (ICS)](https://img.shields.io/badge/ICalendar-FF4500.svg?style=for-the-badge)  ![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)  

An intelligent scheduling web application that integrates Google Calendar and utilizes the Gemini API to break down projects efficiently.

## 🎥 Demo Video
[![Watch the video](https://img.youtube.com/vi/YOUR_VIDEO_ID/maxresdefault.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)

## 🌟 Features
- Google Calendar integration
- AI-powered project breakdown using Gemini API
- React-based frontend
- Python backend
- User authentication and dashboard

## 🛠️ Setup Instructions

### Prerequisites
- Node.js & npm
- Python 3.x
- Google Cloud API credentials

### Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/touring-company.git
cd touring-company

# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
pip install -r requirements.txt
```

### Environment Variables
Create a `.env` file in both `frontend` and `backend` directories with the required API keys.

### Running the Application
```bash
# Start the backend
cd backend
python app.py

# Start the frontend
cd ../frontend
npm start
```

## 📡 API Endpoints
| Endpoint       | Method | Description                        |
|--------------|--------|--------------------------------|
| `/schedule`   | POST   | AI-based project breakdown |
| `/events`     | GET    | Fetch calendar events       |

## 🚀 Deployment
To deploy the application, use Docker or cloud services like Vercel, AWS, or Firebase.

### Using Docker
```bash
docker-compose up --build
```

### Deploying Frontend (Vercel)
```bash
vercel --prod
```

### Deploying Backend (Heroku)
```bash
git push heroku main
```

---

### 📩 Contact
For inquiries, reach out to `hz.hassanzafar@gmail.com`.
