# QuizVerse — AI-Powered Quiz Generation Platform

## Overview
QuizVerse is a full-stack web application that generates topic-based quizzes using Google Gemini’s API.  
Users can log in, choose difficulty levels, generate quizzes instantly, attempt them, and view their past quiz history.

## Features
- AI-generated MCQs using Google Gemini API  
- User authentication with JWT  
- Difficulty-wise quiz generation (Easy, Medium, Hard)  
- Automated scoring and quiz result tracking  
- Quiz history storage and retrieval  
- Responsive and modern UI  

## Tech Stack
**Frontend:** React.js, Vite, Tailwind CSS  
**Backend:** Node.js, Express.js, MongoDB, JWT  
**AI Integration:** Google Gemini API  

## Project Structure
- Frontend built with React (Vite) and Tailwind CSS  
- Backend built using Express.js with REST APIs  
- MongoDB for storing users, quiz attempts, and quiz data  

## How It Works
Users enter a topic and difficulty → Backend calls Gemini → AI generates a quiz →  
User attempts it → Score is calculated → History is stored and displayed.

## Future Enhancements
- Leaderboards  
- Timer-based quizzes  
- Categories and recommended quizzes  
- PDF export  

