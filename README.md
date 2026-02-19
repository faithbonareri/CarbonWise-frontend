CarbonWise Frontend

CarbonWise – AI-Based Carbon Footprint Monitoring & Prediction System

This repository contains the frontend implementation of CarbonWise, a web-based platform designed to monitor, analyze, and predict carbon emissions using Artificial Intelligence.

The system provides users with real-time carbon footprint insights, predictive analytics, and environmental risk indicators through an interactive dashboard.

Project Overview

CarbonWise aims to help individuals and organizations understand their environmental impact and make informed decisions to reduce carbon emissions.

The frontend provides:

1.User authentication and role-based access

2.AI-powered emission prediction visualization

3.GPS-based emission estimation

4.Vehicle carbon emission calculator

5.Industrial smoke detection interface

6.Emission reports and analytics dashboard

Tech Stack

.React (Vite)

.Tailwind CSS

.React Router DOM

.Axios

.Recharts

.Google Maps JavaScript API

Features
Authentication

.User login and registration

.JWT-based authentication

.Role-based routing (Admin / User)

Dashboard

.Carbon emission scorecard

.Risk level indicator (Low / Medium / High)

.AI-based emission prediction (LSTM visualization)

.Monthly emission bar chart

.Alerts panel

.Summary statistics

Location Tracking

.GPS location access

.Interactive Google Map

.Route distance calculation

.CO₂ emission estimation

.Heatmap visualization

Vehicle Emission Calculator

Vehicle type selection (Petrol, Diesel, Hybrid, Electric)

.Distance input

.Real-time emission calculation

.Reduction recommendations

Industrial Monitoring

.Image upload for smoke detection

.CNN-based classification results

.Risk status display

Reports

.Emission history table

.PDF report download

Admin Panel

.User management

.Emission logs

.Search and filtering

Project Structure
src/
│
├── components/        # Reusable UI components
├── pages/             # Application pages
├── services/          # API calls
├── context/           # Global state (Auth)
├── hooks/             # Custom hooks
├── utils/             # Helper functions
├── config/            # Environment configuration
├── App.jsx
└── main.jsx

Getting Started
1. Clone the Repository
git clone https://github.com/YOUR-USERNAME/carbonwise-frontend.git
cd carbonwise-frontend

2. Install Dependencies
npm install

3. Run the Development Server
npm run dev


The app will run at:

http://localhost:5173

Environment Variables

Create a .env file in the root directory:

VITE_API_URL=http://localhost:5000
VITE_GOOGLE_MAPS_KEY=your_google_maps_api_key


Make sure .env is not pushed to GitHub.

Collaboration Workflow

Create a new branch for each feature:

git checkout -b feature/dashboard


Commit changes:

git add .
git commit -m "Add dashboard UI"
git push origin feature/dashboard


Create a Pull Request on GitHub.

Feature branches:

.feature/auth

.feature/dashboard

.feature/maps

.feature/vehicle

.feature/industrial

.feature/admin

Backend Integration (Expected)

The frontend communicates with backend APIs for:

.Authentication

.Emission data

.AI predictions (LSTM)

.Image classification (CNN)

.Report generation

Future Improvements

.Real-time emission tracking

.Mobile responsive optimization

.Notifications system

.Advanced analytics dashboard

.Deployment (Vercel / Netlify)


License

This project is for academic and research purposes.
