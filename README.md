# PneumoScan AI - Pneumonia Detection System

This is a complete end-to-end AI-powered medical web application for Pneumonia Detection using Deep Learning.

## Project Architecture
- **Frontend**: Next.js (React) + Tailwind CSS + Framer Motion
- **Backend**: FastAPI (Python)
- **AI Model**: PyTorch DenseNet121
- **Features**: Patient report generation (PDF), Grad-CAM Heatmaps, Dark Mode, and a responsive Hospital UI.

## Setup Instructions

### 1. Backend Setup
1. Open a terminal and navigate to the `backend` directory:
   ```bash
   cd backend
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   # Windows
   .\venv\Scripts\activate
   # Mac/Linux
   source venv/bin/activate
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the FastAPI server:
   ```bash
   uvicorn main:app --reload
   ```
   The backend will start at `http://localhost:8000`.

### 2. Frontend Setup
1. Open a new terminal and navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```
2. Install the Node.js dependencies:
   ```bash
   npm install
   ```
3. Run the Next.js development server:
   ```bash
   npm run dev
   ```
   The frontend will start at `http://localhost:3000`.

## Features Included
- **Drag and Drop Image Upload** for Chest X-rays.
- **AI Inference** with severity calculation and medical precautions.
- **Grad-CAM Heatmap** overlay indicating the focal points of the AI's decision.
- **PDF Report Generation** with patient ID and predictions.
- **Dark/Light Mode** toggle in the Navbar.
- **Voice Assistant Placeholder** UI.
