# VISH HUB · FYBA Academic Portal

A modern, responsive academic companion and study material management application tailored for First Year Bachelor of Arts (FYBA) students and faculty.

## Features

### 1. Study Material Library
- **Comprehensive Subject Coverage**: Psychology, Philosophy, Economics, English, History, Politics, Geography, French, SEC (Skill Enhancement Courses), OE (Open Electives), and Common Courses (AEC, VEC, IKS).
- **Sub-discipline Categories**: Fine-grained filtering for specialized tracks within SEC, OE, Common, and Other electives.
- **Material Formats**: Textbooks, Syllabus guidelines, Study Notes, Question Banks, Answer Keys, and Video Lectures.
- **Instant Search & Filters**: Search across titles, units, channels, descriptions, and file names with multi-criteria chips.
- **Embedded Video Player**: Watch YouTube lectures seamlessly with lesson details without leaving the workspace.

### 2. Academic Focus & Study Timer
- Customizable study sessions (15 min, 25 min Pomodoro, 45 min, 60 min) with real-time circular SVG progress indicator.
- Daily session targets with progress bar and streak tracker.
- Session completion celebration and local persistence.

### 3. Practice & Assessment Quizzes
- Academic multiple-choice quizzes across core subjects.
- Instant feedback with conceptual insights and rationales for correct answers.
- Student scoreboard tracking completion dates, scores, and accuracy percentages.

### 4. Personal Study Collection (Saved)
- One-tap bookmarking for textbooks, revision notes, and exam answer keys.

### 5. Owner Content Management (Admin Workspace)
- Real-time library metrics (total published links, sections covered, material types).
- Full CRUD operations: Add, Edit, and Delete materials with HTTPS link validation and YouTube domain enforcement.
- Instant sync with the student library.

### 6. Student Profile & Guest Mode
- Student identification (Name, Academic Course, Email).
- Switch between Guest access and registered student sessions.

## Tech Stack
- **Framework**: React 19 + Vite 8
- **Styling**: Tailwind CSS v4 with Material 3 dynamic styling & Georgian academic typography
- **Icons**: Lucide Icons
- **Storage**: LocalStorage with schema matching original VISH HUB keys for backward compatibility
