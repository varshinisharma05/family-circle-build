Family Circle - A Private Mental Wellness Support System

Project Overview

"Family Circle" is a secure, private, and easy-to-use web application designed to foster open communication and collaborative support for mental well-being within families. In a world where mental health apps often focus on individual users and raise privacy concerns, Family Circle offers a unique "local-first" approach. It acts as a shared digital space where family members can monitor and support each other without relying on external servers or cloud databases, ensuring complete data privacy and instant accessibility within the browser.

Features

• Privacy-First, Local-First Architecture: All application data is stored exclusively in the user's browser's localStorage, eliminating the need for backend servers or cloud databases.

• Room-Based Access: Instead of traditional user accounts, access is managed through password-protected "rooms." Families create a unique room name and password, which they can share privately.

• Intuitive Entry & Access Flow: Clear paths for creating new family rooms or joining existing ones.

• Dynamic Main Application Interface: A two-column layout with a fixed navigation sidebar and a main content area.

• Age-Appropriate "Kid's View": A toggle switch that simplifies the navigation and content for younger users, hiding complex sections and rephrasing text to be more encouraging.

• Dashboard: Provides an overview of family wellness, including simulated collective wellness scores, active member count, and support message count. Features a mood trend chart visualizing aggregated moods over the last 7 days.

• My Mood: Allows individual family members to track their mood using visual emoji buttons and add private notes. Displays a personal mood history.

• Family Wall: A real-time chat interface for family communication, with messages styled differently based on the author.

• Family Circle (Room Management): Displays room name and password for easy sharing, with a "Copy Info" button. Lists all current family members in the room.

• Insights, Strategies, & Resources: Placeholder pages with high-quality, professional-sounding content demonstrating potential future features for mental wellness insights, coping strategies, and external resources.

• Responsive Design: Built with Tailwind CSS to ensure a clean, modern, and calming UI/UX that adapts flawlessly to mobile, tablet, and desktop screens.

• Inline SVG Icons: Utilizes high-quality inline SVG icons for all interactive elements.

Technologies Used

• Frontend Framework: React (Functional Components and Hooks - useState, useEffect, useContext)

• Styling: Tailwind CSS

• Charting Library: Recharts

• UI Components: shadcn/ui (Button, Input, Card, Textarea, Switch)

• Icons: Lucide icons (via inline SVG)

• Build Tool: Vite

Installation and Setup (Local Development)

To run this project locally, follow these steps:

1. Clone the repository (or create a new React project):
If you have the zip file, unzip it. If you're starting fresh, create a new React project using Vite:

2. Install Dependencies:
Navigate to your project directory and install the required npm packages:

3. Replace App.jsx:
Ensure the src/App.jsx file in your project contains the provided application code.

4. Update index.html:
Verify that the <title> tag in your index.html is set to Family Circle - Mental Wellness Support.

5. Configure tailwind.config.js:
Make sure your tailwind.config.js is configured to process your source files:

6.Add Tailwind Directives to CSS:
Add the Tailwind directives to your main CSS file (e.g., src/index.css or src/App.css):

7. Run the Development Server:

Usage

Upon launching the application:

1. Create a New Room: Click "Create Room," enter your name, a new family room name, and a password. This will set up your private family space.

2. Join an Existing Room: Click "Join Room," enter your name, the existing family room name, and its password. You will be added to the family circle.

3. Navigate: Use the sidebar to switch between Dashboard, My Mood, Family Wall, Family Circle, Insights, Strategies, and Resources.

4. Kid's View: Toggle the "Kid's View" switch at the bottom of the sidebar to simplify the interface for younger family members.

5. Track Moods: On the "My Mood" page, select an emoji and optionally add notes about your feelings.

6. Communicate: Use the "Family Wall" to send messages to other family members in your room.

7. Invite Others: On the "Family Circle" page, copy the room name and password to share with new family members.
<img width="1522" height="801" alt="image" src="https://github.com/user-attachments/assets/095f67db-72ef-4c18-9a05-c9c52008e528" />
<img width="1533" height="812" alt="image" src="https://github.com/user-attachments/assets/c84fb845-2d64-48cb-848a-27930ddc563d" />
<img width="1574" height="792" alt="image" src="https://github.com/user-attachments/assets/64c7cc45-a359-4aa8-a8cd-0652800bbb5e" />
<img width="1912" height="834" alt="image" src="https://github.com/user-attachments/assets/bd156bab-f924-4da5-a2e6-8625d2d1ebd3" />

