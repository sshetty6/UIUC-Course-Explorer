# CtrlAltDb - UIUC Course Hub

## Project Overview
CtrlAltDb is a sophisticated web application designed to help UIUC students streamline their course selection by aggregating key data points such as GPA statistics, professor reviews, and crowdsourced feedback. The platform also features AI-driven tools like GPT-generated summaries and a **Gemini-based recommendation system** to provide personalized course suggestions, ensuring students make informed academic decisions.

## Key Features
- **Comprehensive Course Data:** Centralized access to all UIUC course information, including GPA data, professor reviews, and student feedback.
- **AI-Powered Summaries:** Summarize course details and reviews using GPT, helping students quickly understand what to expect from each course.
- **Gemini-Powered Recommendation System:** A cutting-edge AI-driven recommendation engine powered by **Gemini AI** that tailors course suggestions based on user behavior, preferences, and past performance.
- **Search & Filter Options:** Refine course searches by difficulty level, GPA, professor ratings, and specific topics covered.
- **User Reviews:** Log in with NetID to securely contribute reviews and course insights, adding a crowdsourced element to the data.
- **CRUD Operations:** Users can create, update, and manage their reviews directly on the platform.
- **Advanced Sorting:** Sort courses by various criteria (professor, GPA, semester) to assist in decision-making.

## Tech Stack
- **Frontend:** React.js with Mantine UI for modern, responsive interfaces.
- **Backend:** Node.js with Express to handle server-side logic and API integrations.
- **Database:** MongoDB or MySQL for persistent data storage, user reviews, and course metadata.
- **AI Integration:** 
  - **GPT-3 (via OpenAI API)** for generating natural language course summaries.
  - **Gemini AI** for the recommendation system, leveraging both collaborative and content-based filtering to suggest courses based on individual preferences and behavior.
- **Authentication:** Secure NetID login with OAuth2, ensuring only authorized students can contribute reviews.

## Gemini-Powered Recommendation Engine
Our recommendation engine is built on **Gemini AI**, designed to provide highly personalized course recommendations by analyzing:
- **Collaborative Filtering:** Leveraging user behaviors (course enrollments, ratings, etc.) to find patterns and suggest courses taken by similar users.
- **Content-Based Filtering:** Evaluating course attributes such as difficulty, professor reputation, and course materials to align recommendations with user preferences.
  
### How the Gemini Recommendation System Works:
1. **Data Collection:** Gemini analyzes the courses students view, rate, and enroll in, building a profile of each user’s academic preferences and history.
2. **Behavioral Analysis:** Gemini uses deep learning models to predict which courses the user will find most beneficial or interesting based on this profile.
3. **Personalized Recommendations:** Recommendations are dynamically displayed on the user’s dashboard, improving over time as the system gathers more data from interactions.

## Data Sources
- **Course Explorer API:** The primary data source for course metadata, including course names, descriptions, professors, and departments.
- **Wade Fagen's GPA Dataset:** A comprehensive dataset containing historical GPA information from 2010-present.
- **Crowdsourced User Data:** Reviews and ratings contributed by users, which feed into the GPT summaries and the Gemini recommendation engine.

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/CtrlAltDb.git
2. Install dependencies
3. Set up environment variables

## Future Enhancements
Cross-University Expansion: Extend the platform to support courses and data from other universities.
Enhanced AI Features: Use Gemini's advanced models to predict course success rates based on professor teaching styles and student backgrounds.
Analytics for Engagement: Track user behavior to continuously refine recommendation accuracy and user experience.
