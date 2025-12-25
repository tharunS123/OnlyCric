# Vibecode App

---

Build a complete mobile app called "OnlyCric – Multi-Angle Cricket Moments".

Goal:
Allow cricket fans to upload their stadium tickets, share photos/videos from matches, and let users view match moments from multiple fan perspectives.

Core Features:

1. User Authentication:

- Login / Signup (email + Google)
- Profile with username, bio, favorite team

2. Ticket Upload System:

- Upload stadium ticket image
- Extract match, venue, date, seat section using OCR
- Verify and assign user to match room

3. Media Upload:

- Upload photos & short videos
- Auto tag by time + match
- Group content into “Moments” (like: wicket, six, crowd cheer)

4. Multi-Angle Viewing:

- Select a match
- Select a moment
- Switch between different fan camera angles
- Sort by closest seat POV

5. Social Layer:

- Like, comment, share
- Follow users
- Badges for stadium attendance
- Leaderboard for top contributors

Backend Requirements:

- Store users, matches, videos, tickets
- Efficient media storage
- Content moderation

UI Requirements:

- Clean, modern, dark theme
- Match feed homepage
- Upload button prominent
- Moment viewer like Instagram reels + multi-camera selector

Tech Expectations:

- Suggested stack: Flutter / React Native
- Backend: Firebase / Node / FastAPI
- Simple MVP structure but scalable

Make the project structured, documented, and beginner friendly.

User Journey:
1️⃣ Onboarding → Splash screen → Signup/Login → Choose favorite teams → Permission walkthrough.
2️⃣ Home Feed → Trending Matches → “I Was There” section → Upload Ticket CTA.
3️⃣ Ticket Upload Flow → Upload stadium ticket → OCR reads stadium name, match, seat section → Validate ticket → Link user to seat zone.
4️⃣ Media Upload Flow → Upload photo/video → Extract metadata + timestamp → AI tags (wicket, six, crowd cheer, celebration, reaction) → Assign to Match Moments.
5️⃣ Match Moment Page → Show timeline of match highlights → Each moment has multiple fan POV tiles grouped by stadium section → User can switch viewing angle like rotating perspectives.
6️⃣ Social Layer → User profiles → Followers/Following → Stadium achievement badges → Contribution history → Likes & comments → Leaderboards.
7️⃣ Moderation/Admin Side → Queue for content approval → Duplicate detection → Sensitive content filtering → Storage management indicators.

Core Screens to Design:
Onboarding & Login
Home Feed
Match Page
Ticket Upload & Validation
Media Upload & Processing
Multi-Angle Replay Viewer
User Profile Page
Leaderboard Page
Notifications
Admin Moderation Panel

Design Goals:
Clean modern sports app style
Energetic cricket vibe with bold typography
Simple intuitive UX
Clear CTA buttons and structured flows

Tone & Style:
Professional startup-grade
Fun, social, and community-driven
Minimal clutter, prioritize content
