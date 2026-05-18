# 👗 FitMatch

FitMatch is a social fashion mobile application designed to help users decide what to wear by uploading outfit options and receiving community-based feedback through voting. The app combines outfit uploads, occasion-based comparisons, Elo ranking, AI-assisted outfit analysis, and profile features to make fashion feedback more structured, interactive, and data-driven.

## ✨ Features

- 📸 Upload two outfit options for a specific occasion
- 🗳️ Vote between outfit pairs based on the selected occasion
- 📊 Elo-based ranking system that updates outfit scores after votes
- 👤 User profiles with outfit history and wardrobe-style organization
- 🏆 Trending outfits based on ranking and community engagement
- ⭐ Favorite outfits and view favorite counts
- 🗑️ Delete uploaded outfit pairs with proper ownership checks
- 🔔 Recent activity feed for uploads, votes, and favorites
- 🤖 AI-assisted outfit labeling and image validation using Google Vision AI
- 🌐 Multi-device testing using Expo Go and a shared backend

## 📱 Application Screens

### Upload Screen
- Allows users to upload two outfit images
- Includes occasion selection
- Supports outfit descriptions for added context
- Uses image validation to help ensure uploaded photos are clothing-related

### Voting Screen
- Displays two outfits for the same occasion
- Allows users to vote for the outfit that fits best
- Updates ranking through the Elo system
- Shows outfit context so voters understand the occasion

### Trending Screen
- Displays high-performing outfits
- Highlights outfits based on ranking and engagement
- Helps users discover popular looks

### Profile Screen
- Shows user information and uploaded outfits
- Displays outfit history and performance
- Supports profile image functionality

### Favorites
- Allows users to favorite outfits
- Displays favorite counts
- Helps users keep track of looks they like

### Recent Activity
- Shows recent uploads, votes, and favorites
- Helps users stay engaged with activity across the app

## ⚙️ Tech Stack

- **Frontend:** React Native, Expo
- **Backend:** Flask, Python
- **Database:** MySQL, AWS RDS
- **Image Storage:** AWS S3
- **AI Tools:** Google Vision AI
- **Ranking:** Elo algorithm
- **Hosting:** Render
- **Testing:** Expo Go, local backend testing, deployed backend testing

## 🤖 AI Integration

FitMatch uses Google Vision AI to support outfit-related image analysis. The AI integration helps label uploaded images and assists with validating that users are uploading clothing or outfit-related photos.

## 📊 Elo Ranking System

FitMatch uses an Elo-based ranking system to update outfit scores after users vote. When an outfit wins a comparison, its score increases based on the expected outcome, while the losing outfit’s score decreases. This helps create a more data-driven way to measure outfit performance over time.

## 🚧 Limitations

- The full source code is private because this project was created as part of a senior capstone project.
- Some backend features depend on the deployed Render service being live.
- Local testing requires the backend to be running and the frontend `.env` file to use the correct local IP address.
- AI image validation depends on Google Vision API configuration.

## 🔒 Security Note

API keys, database credentials, AWS credentials, and environment variables are not included in this public repository.

The full project repository remains private to protect sensitive configuration, teammate contributions, and backend credentials.

## 🎥 Demo Video

[Watch the demo video here](YOUR_GOOGLE_DRIVE_LINK)

## 👩‍💻 Author

**Rohina Saeydie**  
Computer Science Student at The George Washington University

## 📌 Repository Note

This repository is for portfolio and demo purposes only. It showcases the project concept, features, technologies, and demo video for FitMatch. The full source code is kept private.
