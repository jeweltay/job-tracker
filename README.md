# Job Application Analytics Dashboard

## Video Demo: https://youtu.be/omKjLPmh3fY

## Live Demo: https://job-tracker-u7gb.onrender.com/

## Description
Job Tracker is a full-stack web application that transforms job search chaos into data-driven clarity. Built as my CS50 final project, it helps job seekers track applications and uncover patterns through advanced analytics and custom visualizations.

## Features
- **Complete CRUD Operations**: Add, view, edit, and delete job applications
- **Smart Scoring System**: Rate jobs by career fit (20%), interest (30%), growth potential (30%), and salary fit (20%)
- **Interactive Dashboard**: Real-time analytics with key metrics and trends
- **Custom Chart Builder**: Create personalized visualizations to answer specific job search questions
- **Advanced Filtering**: Search and filter by company, status, score ranges, and dates
- **Data Export**: Download application data as CSV for external analysis
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## Technology Stack
- **Backend**: Python, Flask, SQLAlchemy
- **Frontend**: HTML5, CSS3, JavaScript, Chart.js
- **Database**: PostgreSQL (Production), SQLite (Development)
- **Deployment**: Render.com
- **Visualization**: Chart.js for interactive charts

## Project Structure
- `app.py` - Main Flask application with all routes and business logic
- `templates/` - HTML templates using Jinja2 for dynamic content
- `requirements.txt` - Python dependencies
- `runtime.txt` - Python version specification

## Key Insights Provided
- Identify which application stages have the highest success rates
- Track alignment between interest levels and actual applications
- Analyze industry fit and performance patterns
- Discover career pivot sweet spots through data visualization

## Installation
```bash
git clone https://github.com/jeweltay/job-tracker
cd job-tracker
pip install -r requirements.txt
python app.py

## Design Choices
The application focuses on user-centric design with guided analytics that prevent meaningless chart combinations. The custom chart builder specifically addresses the three most critical questions job seekers face about their application pipeline, interest alignment, and industry fit.

## Future Enhancements
Saved filter combinations and chart presets

Advanced predictive analytics

Integration with job boards and LinkedIn

Collaborative features for career coaches

## Note
This project was developed as the final assignment for Harvard CS50 and represents the culmination of skills learned throughout the course.
