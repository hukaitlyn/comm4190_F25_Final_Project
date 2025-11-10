# Final Project Idea Selection and Use Case Scenarios

## Idea Pitch (100-150 words)

RunMate is an AI-powered running companion that transforms every workout into a motivating conversation. Designed for anyone who struggles with consistency or confidence, RunMate offers personalized running plans, pacing advice, and encouragement before, during, and after each run. By chatting naturally with users about their goals, schedule, or even the weather, it acts as a supportive coach and teammate rolled into one. Whether it’s creating a beginner 5K plan, suggesting recovery stretches, or celebrating milestones, RunMate makes training safer, smarter, and more social. helping runners stay consistent while having fun. The app adapts to each runner's fitness level and preferences, providing guidance that feels personal rather than robotic. From first-time joggers to experienced marathoners, RunMate helps athletes stay consistent, avoid injury, and enjoy the journey!

## Description of Target Users

- College students or young professionals balancing fitness with busy schedules
- Beginner and intermediate runners seeking structure and motivation
- Users recovering from injury or aiming to build stamina safely
- Casual joggers who enjoy conversation, accountability, and feedback
- Runners in general

## What the Application Will Do 

RunMate will:
- Conduct a chat-based onboarding to learn the user’s fitness level, past running experience, and goals (e.g., “run 3x a week,” “train for a 10K”).
- Generate custom running plans with progressive goals, rest days, and adaptive scheduling based on user feedback.
- Provide real-time conversational support before and after runs (e.g., pep talks, pacing reminders, cooldown prompts).
- Offer progress tracking and motivational insights, summarizing trends in pace, frequency, and energy levels.

### What data (from users, web, other sources, etc) will be needed

From users:
- Name or nickname
- Fitness level (beginner/intermediate/advanced)
- Running goals (e.g., “run 5K without stopping,” “train for a half marathon”)
- Preferred schedule (days per week, run duration)
- Health considerations (optional: prior injuries, limits)
- Daily reflections (energy, mood, soreness level, weather)
From other sources:
- Public training guidelines and reference data (e.g., pacing charts, recovery standards)
- Optional wearable or app data (distance, heart rate, pace)

### What is the role of LLMs

The LLM powers all conversational reasoning and adaptive motivation:
- Engages users naturally, recognizing emotions and intent (“I almost skipped today” → offers gentle encouragement).
- Adapts running plans dynamically (“You missed your long run yesterday; let’s adjust your week”).
- Explains training principles in accessible language (“Why recovery days matter”).
- Reflects back progress summaries (“You’ve improved your pace by 10% since last month!”).
- Handles creative, empathetic dialogue to sustain motivation while remaining safe and evidence-based.

## How it is Different

How your product will differ from both existing non-LLM powered systems in the domain and from just using a general purpose LLM for the task (e.g. Gemini, Claude or ChatGPT)

Compared to non-LLM running apps (e.g., Nike Run Club, Strava):
- Most apps rely on static plans and push notifications, not real conversation.
- RunMate listens, encourages, and adjusts like a real coach who understands your mood, schedule, and progress.
- Adds an emotional layer of motivation, addressing burnout and self-doubt, not just performance metrics.
Compared to general-purpose LLMs (e.g., ChatGPT, Gemini):
- RunMate maintains persistent training data and progress across sessions.
- Includes specific domain rules for safe pacing, progressive overload, and rest recovery.
- Offers structured, goal-based chat flows (pre-run pep talk, post-run reflection, mid-week motivation).
- Filters unrealistic or unsafe suggestions (e.g., no “run 10 miles tomorrow” after an injury).

## Usage Scenarios

Each group member should create TWO USAGE SCENARIOS for the product. A usage scenario consists of:

Short description - e.g. 'Capturing my network of friends and family through chat interaction'

Narrative of scenario - e.g. 'The user will engage in a chat conversation with MyNetGPT and be prompted to talk about recent social interactions, activities and situations they have done with their friends and family. The LLM will build up a list of names from these chats and ask follow up questions about them. In the background the app is constructing an ego network where nodes are the names of the friends (with attributes for features like how long you've known them, how strong the relationship is, what the individual likes/dislikes, how often you see them etc) and edges between the nodes based on imputing relationships like "A knows B", "A socializes with C" etc. from the chat history'

Step by step break down of the interaction - you can do this with bullet points and/or a Mermaid Sequence Diagram
Data description - what data is:
Needed for the app/LLM to engage and complete this scenario (be specific about the type of data, how it will be provided to the LLM etc)
Created as a result of the interaction, e.g. as a result of the 'tell me about your social interactions' scenario, a data structure (i.e. a network data structure) will be built and updated 

Evaluation - how will you test whether the application has successfully completed the scenario and what possible complications, errors should you consider (e.g. what happens if the input from the user is unexpected or adversarial etc)
