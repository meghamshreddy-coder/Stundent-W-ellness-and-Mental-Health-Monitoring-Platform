1. Introduction

The Student Wellness Monitor is a digital mental health platform designed to help students track their emotional well-being, identify behavioral patterns, and receive personalized recommendations. The app encourages self-awareness through daily mood check-ins, sentiment analysis, and data-driven visualizations while ensuring a responsive and user-friendly experience.

2. Objectives

Enable students to log daily moods quickly and easily.

Apply sentiment analysis to interpret journal entries or mood descriptions.

Provide personalized wellness recommendations based on tracked emotions.

Present visual trends (graphs, charts, reports) to show mood progress over time.

Deliver a responsive application accessible across mobile, tablet, and desktop.

Ensure data privacy and security for sensitive mental health information.

3. Scope

The platform will:

Support user registration & authentication.

Allow mood tracking via emojis, sliders, or text input.

Perform sentiment analysis using NLP (Natural Language Processing).

Provide customized suggestions (e.g., meditation, journaling, peer support, time management tips).

Show trend visualizations (line graphs, weekly/monthly reports).

Include reminder notifications for daily check-ins.

Offer a dashboard for self-reflection and progress tracking.

Out of scope:

Clinical diagnosis or replacing professional mental health services.

Emergency crisis intervention.

4. System Requirements
4.1 Functional Requirements

User Management

Registration (email/SSO) and secure login.

Profile creation with optional preferences (study load, lifestyle, etc.).

Mood Check-ins

Daily prompts with quick response (emoji scale, rating, text input).

Option to write journal entries.

Sentiment Analysis

NLP-based text analysis to detect mood trends (positive, neutral, negative).

Keyword extraction for stressors (e.g., "exams", "sleep").

Recommendations Engine

Personalized wellness activities (e.g., "Try a 10-min meditation", "Take a short walk").

Adaptive suggestions based on history.

Visualization Dashboard

Graphs: Mood over time, stress vs relaxation trends.

Weekly & monthly summaries.

Notifications & Reminders

Daily mood check-in reminders.

Gentle nudges for wellness activities.

Tracking & Reporting

Exportable reports (PDF/CSV).

Long-term tracking of wellness progress.

4.2 Non-Functional Requirements

Performance: Real-time sentiment processing.

Usability: Mobile-first responsive UI.

Security: Encrypted data storage, secure authentication.

Privacy: Compliance with GDPR/HIPAA-like standards.

Scalability: Cloud-hosted backend to support large student populations.

5. System Design
5.1 Architecture

Frontend: React Native (for cross-platform mobile) or React.js (for web).

Backend: Node.js/Express or Django REST API.

Database: PostgreSQL / MongoDB (encrypted storage).

NLP Engine: Python (NLTK, spaCy, Hugging Face).

Visualization: Chart.js / D3.js.

Hosting: AWS / Firebase.

5.2 Data Flow Diagram

User logs mood ➝ App collects data ➝ Backend stores data.

Text input ➝ NLP sentiment analyzer ➝ Mood category assigned.

Historical data ➝ Analytics engine ➝ Graph generation.

Recommendation engine ➝ Personalized suggestions displayed.

6. User Interface (UI/UX)

Login & Registration Page

Daily Mood Check-in Page (emoji scale, sliders, journal text box).

Dashboard with charts & summaries.

Recommendation Page with actionable insights.

Settings Page (notifications, privacy controls).

7. Testing Plan

Unit Testing: Check individual modules (login, sentiment analysis, visualization).

Integration Testing: Ensure smooth flow from input ➝ sentiment ➝ recommendation ➝ visualization.

Usability Testing: Gather student feedback on ease of use.

Security Testing: Validate encryption and authentication.

8. Deployment

Mobile App Stores (Android/iOS) for student access.

Web App (Responsive) for cross-device compatibility.

Cloud Hosting (AWS/Firebase) with auto-scaling.

9. Future Enhancements

AI-powered chatbot for peer-like conversation support.

Integration with wearables (Fitbit, smartwatch) for sleep/activity tracking.

Community features (peer support groups, anonymous discussions).

Faculty dashboard (with student consent) for wellness monitoring.

10. Conclusion

The Student Wellness Monitor provides an effective, non-intrusive platform for supporting student mental health. With daily check-ins, sentiment analysis, recommendations, and visualization, the app empowers students to reflect on their emotional well-being, make healthier lifestyle choices, and identify patterns that may require attention.
