---
title: SkillTrack
slug: skilltrack
date: '2026-03-26'
updated: '2026-03-26'
draft: false
archived: false
service: UX/UI Design
year: 2024
industry: Education
description: Gamified skill tracking for lifelong learners.
main_image: 'https://cdn.prod.website-files.com/692486acb16e64066a373b89/692e059829579af30deeaa17_SkillTrack_UX-UI-design_by_Georges-baradehi.jpg'
gallery:
  - 'https://cdn.prod.website-files.com/692486acb16e64066a373b89/692df2ad42d48a508bb5e37d_Illustrations%20Sample.png'
  - 'https://cdn.prod.website-files.com/692486acb16e64066a373b89/692dd458294883b1ba2b8ad2_Color%20Palette%20(2).png'
  - 'https://cdn.prod.website-files.com/692486acb16e64066a373b89/692dddbbdc4501e77e621e8a_Interactive%20Components%20(2).png'
  - 'https://cdn.prod.website-files.com/692486acb16e64066a373b89/692e0355f45e3b0200664c56_SkillTrack_Right-to-left-arabic-screen_UX-UI-design_by_Georges-baradehi.png'
  - 'https://cdn.prod.website-files.com/692486acb16e64066a373b89/692e069324b3277ebe782ecf_SkillTrack-screens_UX-UI-design_by_Georges-baradehi.jpg'
website: '#prototype'
testimonial:
  name: Maher Berro
  position: Senior UX/ UI Lecturer at A.U.B
  picture: 'https://cdn.prod.website-files.com/692486acb16e64066a373b89/692b4a47623c7a7a23aa1aa9_Maher-Berro-UX-UI-AUB-Faculty-Profile.jpg'
  quote: '"Great research and plan You could have further elevated the interactions and wireframes."'
next_project: smart-enseignes
home_order: 2
project_order: 1
---

## Objective

Introduction

The Challenge: Why do we quit what we start? We live in the golden age of self-education, yet completing a course or mastering a new hobby remains incredibly difficult. The enthusiasm is there, but the structure is missing.

The Solution: SkillTrack is a mobile learning companion designed to fix the consistency gap. By combining habit-tracking mechanics with gamification, it turns the chaotic process of self-study into a rewarding, structured journey.

Research & Discovery

Understanding the Learner’s Struggle: I kicked off the project with a simple question: What stops people from learning? Through a mix of surveys and 1:1 interviews, I dug into user habits.

The data revealed a clear pattern: motivation isn’t the problem consistency is. Users felt overwhelmed by unorganized resources and lacked the immediate feedback loops that make learning addictive.

Struggle to find consistent time
61%

Use YouTube or online platforms
73%

Want structured but flexible learning
82%

Prefer short sessions
58%

Need motivation and gamification
47%

Defining the Users: To keep the design focused, I synthesized my research into two core personas:

- The Career Climber: Needs efficiency and measurable progress to upskill for work.

- The Curious Learner: Needs a fun, low-pressure way to explore creative hobbies.

Despite their different goals, both needed the same thing: accountability.

Information Architecture

Building a Structure that Makes Sense: I organized the app to minimize cognitive load. The architecture centers around the Home Dashboard a single source of truth where users can see their daily tasks and progress at a glance.

Surrounding this are the Learning Hub (where resources live) and the Profile (where achievements are celebrated).

Onboarding & Learning Setup

User enters skills, time availability, and pace. AI generates personalized schedule.

Home (Dashboard)

Central hub for tracking progress, upcoming lessons, and AI recommendations.

Profile (Top Corner)

Achievements, Badges, Settings, and Schedule management.

Flip Cards

AI-generated flashcards for reinforcement. Swipe to mark "Mastered" or "Review Again".

AI Chatbot

Virtual tutor for Q&A, explanations, and voice interaction without disrupting flow.

Learning Path

Structured step-by-step lessons, quizzes, difficulty adjustments, and resources.

User Flows

Mapping the Happy Path: Before opening my design tools, I mapped out the critical journeys. My goal was to remove friction between "opening the app" and "learning." The flows below visualize the onboarding process and the core "Daily Check-in" loop.

Flow 1: Onboarding and Schedule Creation

User Opens the App

Welcome screen displays a brief introduction. User clicks "Get Started".

Select or Enter Skill

App suggests skills or allows manual entry. User selects their target topic.

Input Free Time

User defines availability per day (e.g., Mon 10-11 PM, Wed 8-9 AM).

Choose Learning Pace

Short
15-30m

Normal
30-60m

Deep
1hr+

AI Generates Schedule

Processing inputs to create a custom plan. Displays Start Date, Duration, and a preview.

Confirm & Start

User clicks "Continue", completing onboarding and entering the Dashboard.

Flow 2: Learning and Quiz Progression

User Opens the Home (Dashboard)

Dashboard displays current and upcoming lessons with a progress visual.

User Starts a Lesson

Scrolls through sections.

Completes Lesson & Starts Quiz

Lesson ends, "Take Quiz" button appears. Includes Multiple-choice & Fill-in-the-blank.

Decision Point: Did the User Pass?

System evaluates score threshold (70%).

↓

Score ≥ 70% (Passed)

• Receives corrections

• Next lesson unlocks

• Success message appears

↓

Score < 70% (Failed)

• Explanations for mistakes

• Creates review lesson

• Must retake short quiz

↓

User Returns to Learning Path

Progress updated. Next lesson unlocked (if passed). User can proceed or review.

Flow 3: Getting Help from the AI Chatbot

User Accesses the Chatbot

Accessible via the bottom navigation bar (except during quizzes).

The user taps the AI Chatbot icon to open the assistant.

User Inputs a Question or Request

• Types a custom question

• Uses voice input to speak the question

Chatbot Generates a Response

AI provides a text-based explanation and links to relevant lessons or TED talks.
It may also suggest a quick quiz or flashcard review.

User Engages with Additional Features

Voice Mode: Switch to talk/listen mode.

Knowledge Check: Bot asks follow-up questions to ensure understanding and identify weak areas.

User Returns to Learning

User closes the chatbot to continue their lesson. The system records the interaction to modify future lesson recommendations.

Visual Strategy & Localization

Designing for Global Users (LTR & RTL): SkillTrack is designed to be accessible in both Left-to-Right (English) and Right-to-Left (Arabic/Hebrew) languages. However, I avoided blindly mirroring every single element.

The Strategy: Adaptive Content, Fixed Navigation: While I mirrored the visual flow of text, progress bars, and directional icons to match the natural reading order of RTL users, I made a strategic decision to keep the Bottom Navigation consistent in both versions.‍

Why? To preserve muscle memory. The thumb learns where key actions live. By anchoring the core navigation in the same spot, I ensure that the physical interaction remains familiar, even if the language settings change.

Prototyping & Interaction Design

📱

Tap to View Prototype

Since this screen is small, the interactive prototype is best viewed in a full browser window.

Open Prototype ↗

## Results

Reflections

What I Learned: SkillTrack taught me that gamification is a delicate balance. It’s not just about slapping badges on a screen; it’s about creating meaningful feedback loops that make the user feel accomplished.

Next Steps: If I were to continue developing this product, I would introduce Social Accountability features. Allowing users to share milestones with friends could be the final piece of the puzzle to solve the motivation problem.
