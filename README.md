# Smart India Hackathon Workshop
# Date:24-09-2025
## Register Number:25011903
## Name:Kanishka G
## Problem Title
SIH 25010: Smart Crop Advisory System for Small and Marginal Farmers
## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

• A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory.
• Soil health recommendations and fertilizer guidance.
• Weather-based alerts and predictive insights.
• Pest/disease detection via image uploads.
• Market price tracking.
• Voice support for low-literate users.
• Feedback and usage data collection for continuous improvement.

Relevant Stakeholders / Beneficiaries

• Small and marginal farmers
• Agricultural extension officers
• Government agriculture departments
• NGOs and cooperatives
• Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution

Crop Disease & Pest Detection
Farmers capture/upload leaf images using their smartphones.
An AI model (CNN, optimized for TensorFlow Lite) analyzes the image to detect crop diseases/pests.
Provides output with:
Disease identified
Confidence level
Severity level (mild, moderate, severe)
Suggested organic/chemical remedies and preventive steps

Fertilizer & Soil Nutrition Advisory
Inputs: crop type, stage, soil N-P-K/pH (optional), farm size.
Rule-based engine recommends:
Fertilizer type and dose
Application timing
Weather-sensitive adjustments (avoid fertilizer before heavy rainfall).

Smart Irrigation Advisory
Uses local weather forecasts + optional soil moisture sensors.
Predicts daily/weekly water needs (crop evapotranspiration model).
Alerts farmers when irrigation is required and how much water to apply.

## Technical Approach
Accessibility Features
Multilingual UI with voice support for semi-literate farmers.
Offline-first with SMS fallback in low-connectivity areas.
Simple icon-based interface for usability.

Technology Stack
Mobile App: Android (Kotlin) / React Native
Backend: Python Flask/Django REST APIs
Machine Learning: TensorFlow Lite / PyTorch Mobile for on-device inference
Database: PostgreSQL + Redis

Data Sources:

PlantVillage dataset for crop disease images
IMD/Weather APIs for weather forecasts
Govt. Mandi Price APIs for crop market rates
<img width="796" height="749" alt="Screenshot 2025-09-24 101711" src="https://github.com/user-attachments/assets/661df421-5c56-4822-9af4-bd7a31d74de1" />


## Feasibility and Viability
Target Users: Small & marginal farmers.
Accessibility: Mobile app or SMS-based advisory can reach farmers with basic phones.
Ease of Use: UI/UX must be simple, language-localized, and visually guided.
Training: Farmers may need short-term training sessions or demo videos.

 Market Viability

Target Market: Millions of small and marginal farmers in India and other developing countries.
Adoption Drivers:
Increasing smartphone penetration.
Government initiatives for digital agriculture (e.g., PM-FME, eNAM).
Rising awareness about modern farming techniques.

## Impact and Benefits
Economic Impact
Increased Crop Yield: Personalized crop and input recommendations lead to better productivity.
Reduced Input Costs: Optimized use of fertilizers, pesticides, and water reduces unnecessary expenses.
Better Market Decisions: Real-time price alerts help farmers sell crops at optimal rates, increasing income.

Technological and Environmental Benefits
Precision Agriculture: Data-driven recommendations optimize farming operations.
Reduced Environmental Impact: Less chemical runoff, efficient water usage, and soil preservation.
Resource Optimization: Sensors and AI models help make optimal use of limited land, water, and fertilizer.

## Research and References
https://ijisrt.com/assets/upload/files/IJISRT25MAY1858.pdf
