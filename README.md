# 💪 Miras - Fitness Tracking & Workout Management Platform

A comprehensive **fitness tracking and workout management system** built with Laravel 12. 
Create personalized workout plans, track your progress, share achievements with friends, 
and monitor your fitness journey with detailed analytics.

## ✨ Key Features

### Workout Management
- Create and customize workout plans with multiple days
- Build exercises with sets, reps, and rest periods
- Choose from system exercises or create your own
- Duplicate plans for quick setup
- Share plans with unique tokens

### Session Tracking
- Log workout sessions with date and duration
- Track sets, reps, and weight per exercise
- Auto-detect today's routine based on your plan
- View session history and past performance
- Duplicate previous sessions easily

### Progress Analytics
- Weekly statistics (sessions, minutes, exercises)
- Workout streak tracking (current & best)
- Body weight monitoring with monthly comparison
- Exercise-specific progress tracking
- Big Three lift progress (Bench, Squat, Deadlift)
- Body measurements (chest, waist, arms, legs)
- 7-day activity visualization

### Social Features
- Add friends and track their progress
- Accept/reject friendship requests
- View friends' latest workout sessions
- Public profile sharing
- Activity feed from friends

### Admin Dashboard
- User management (create, edit, delete, admin toggle)
- Exercise library management
- User and session analytics
- Export user data reports

## 🛠️ Tech Stack

- **Backend**: Laravel 12, PHP 8.2, Eloquent ORM
- **Frontend**: Blade, Tailwind CSS, Alpine.js
- **Database**: MySQL/PostgreSQL
- **Build**: Vite, Composer
- **Testing**: PHPUnit, Faker

## 🚀 Quick Start

```bash
# Installation
composer install
npm install

# Setup
cp .env.example .env
php artisan key:generate
php artisan migrate

# Run development server
php artisan serve
npm run dev
```
---

## Author

**Mahmoud Maher Al Jbour**  
Backend Developer | Laravel & PHP Specialist  
[GitHub](https://github.com/mahmoud-aljabour) · [LinkedIn](https://linkedin.com/in/mahmoud-aljabour)
