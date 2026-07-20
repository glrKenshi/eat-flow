# Eat Flow

Eat Flow is a modern web application for managing meals, tracking nutrition, and organizing food data in a simple and intuitive way.

## What it is for

Eat Flow is designed for people who want better control over their daily eating habits. It helps users log meals, track nutrients, and keep their food information organized, whether for personal health goals or a more structured meal-planning workflow.

## What it does

- Allows users to sign up and log in securely
- Lets users create and manage meals for specific dates
- Supports adding foods with nutritional information such as calories, protein, fat, carbohydrates, fiber, and sugar
- Enables users to associate foods with serving units and quantities
- Provides a dashboard to review meals and nutrition data
- Includes an admin area for managing food categories and food entries
- Supports role-based access for regular users and administrators

## Tech Stack

- Next.js
- React
- TypeScript
- Prisma with SQLite
- NextAuth
- Tailwind CSS and shadcn/ui

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```
2. Create a .env file and set your database URL:
   ```env
   DATABASE_URL="file:./dev.db"
   ```
3. Run database migrations:
   ```bash
   npx prisma migrate dev
   ```
4. Seed the database with initial data (optional):
   ```bash
   npm run seed
   ```
5. Start the development server:
   ```bash
   npm run dev
   ```

Open http://localhost:3005 to view the app in your browser.

## Project Goal

The main goal of Eat Flow is to make nutrition tracking and meal planning easier, more organized, and more accessible for everyday use.
