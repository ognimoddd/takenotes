# TakeNotes: An Immersive Note-Taking App for Students

## About
This feature-rich note-taking application called TakeNotes was developed as the centrepiece of my dissertation project. It aims to address the unique challenges students face in managing the vast amounts of information they encounter during their studies. The project's innovative approach and execution led to its recognition as a Project Finalist for the Final Year Project Dissertation, underscoring its significance and potential impact on educational technology.

Born from a deep understanding of student needs and leveraging cutting-edge technologies, this app represents the culmination of extensive research, design, and development efforts. It stands as a testament to the potential of mobile applications to enhance the learning experience and improve academic outcomes.

Built with React Native and Expo, this app offers robust features to enhance the note-taking experience, including user authentication, CRUD operations, advanced search functionality, and extensive customisation options. It also incorporates cutting-edge AI-powered features such as handwriting recognition, image labelling, and note summarisation, pushing the boundaries of what's possible in a mobile note-taking application.

## Dissertation Focus
The development of this app formed the core of my dissertation, which explored:
- The impact of digital tools on student information management
- The integration of AI technologies in educational applications
- User experience design for academic productivity tools
- The challenges and opportunities in mobile app development for education

Through this project, I demonstrated technical proficiency in mobile app development and a deep understanding of user-centred design and the practical application of emerging technologies in an educational context.

## Key Features
- User Authentication: Secure login and registration system
- CRUD Operations: Create, read, update, and delete notes
- Search: Quickly find notes based on content or tags
- Customisation: Personalise note appearance with various fonts, sizes, and colours
- AI-Powered Features:
  - Text Recognition: Convert images of text into editable notes
  - Image Analysis: Automatically detect and label objects in images
  - Text Summarisation: Generate concise summaries of lengthy notes
- Sharing Options: Easy sharing of notes with peers
- Bookmarking: Mark important notes for quick access
- Templates: Pre-defined note templates for different purposes
- Text-to-Speech: Listen to your notes for auditory learning
- Dynamic Backgrounds: Change app background based on note content or user preference

## Demo Videos
1. User Authentication:

https://github.com/HenryOnilude/note-taking-app/assets/111580327/cd88a706-94ee-4e58-ab4c-37b736eed642

2. Save, Pin, Bookmark & Search Notes

https://github.com/HenryOnilude/note-taking-app/assets/111580327/3fc7c145-6218-489f-adda-444b2e32c115
   
3.  Template & Customisation Options:

https://github.com/HenryOnilude/note-taking-app/assets/111580327/6427d7b6-798c-4e40-8e2b-06ac26239480

4.  Text to speech:

https://github.com/HenryOnilude/note-taking-app/assets/111580327/181b8523-fc7c-4281-a725-fb9600263fd8

5. Text recognition and summary:

https://github.com/HenryOnilude/note-taking-app/assets/111580327/0a76367a-4c24-4480-8b31-2d6c435722b9

6. Analyse Image:

https://github.com/HenryOnilude/note-taking-app/assets/111580327/2526f955-014e-40f0-80ce-a5f326e52ffa

7. Print & Sharing Options:

https://github.com/HenryOnilude/note-taking-app/assets/111580327/1bb81422-c70e-48c5-887b-1fb5bb32223e

## Usage Instructions
1. Register an account or log in if you already have one.
2. Create a new note by tapping the '+' button.
3. Use the rich text editor to write your notes.
4. Customise your note's appearance using the style options.
5. Use AI features:
   - Tap the camera icon to use image labelling.
   - Use the handwriting or text recognition feature to convert written text.
6. Save your note and find it later in the main list.
7. Use the search function to find specific notes quickly.
8. Share notes with others using the share button.

## Technologies Used
- React Native: Frontend framework for mobile app development
- Expo: Development platform for React Native
- AsyncStorage: Local data storage solution
- Google Cloud Vision API: Powers AI features like image labelling and handwriting recognition
- React Navigation: For app navigation
- Expo AV: For audio playback in text-to-speech feature
- Axios: For making HTTP requests
- React Native Picker Select: For dropdown menus
- Linear Gradient: For stylish UI elements
- iOS Simulator: Used for testing and development, specifically iOS 17.2 on iPhone 15 simulator

## Steps to Run the Client Locally
1. Ensure you have Node.js and npm installed on your machine.
2. Install Expo CLI globally: `npm install -g expo-cli`
3. Clone the repository: `git clone [your-repo-url].`
4. Navigate to the project directory: `cd [project-name]`
5. Install dependencies: `npm install`
6. Start the project: `npm start`

## What I Learned from This Project

1. Developing a React Native application using Expo:
   - Created a multi-screen mobile app with navigation using React Navigation
   - Implemented a stack navigator for the main app flow and a drawer navigator for additional navigation options

2. Implementing basic user authentication:
   - Developed login and registration screens (Login.js, Register.js)
   - Used AsyncStorage for storing and retrieving user credentials
   - Implemented form validation for user inputs

3. Integrating third-party APIs for AI features:
   - Utilised Google Cloud Vision API for image labelling (ImageDetection.js)
   - Implemented handwriting recognition using Google Cloud Vision API (HandwritingRecognition.js)
   - Note: While not directly visible in the provided code, you mentioned note summarisation, which typically uses Cloud Natural Language API

4. Creating a custom navigation drawer:
   - Designed and implemented a custom drawer component (CustomDrawer.js)
   - Included functionality for displaying bookmarked notes and a logout option

5. Working with multimedia in React Native:
   - Implemented video backgrounds in login and registration screens using Expo's Video component
   - Handled image picking and display within notes

6. Managing local data storage in a mobile app:
   - Used AsyncStorage for CRUD operations on notes (Notes.js)
   - Implemented bookmarking functionality for notes

7. Designing a customisable user interface:
   - Created options for users to customise note appearance, including font family, font size, text colour, and background colour (Notes.js)
   - Implemented a template system for different types of notes

8. Handling form inputs and validation in React Native:
   - Implemented input validation for registration and login forms
   - Created dynamic form inputs for note creation and editing

9. Implementing text-to-speech functionality:
   - Added feature to read out note content using Expo's Speech API (Notes.js)

10. Working with image picking and processing:
    - Integrated image selection for note attachments
    - Implemented image analysis for automatic labelling using Google Cloud Vision API

11. Implementing basic animations in React Native:
    - Used LinearGradient for creating animated background effects
    - Applied subtle animations to enhance user interface elements

12. Implementing sharing and exporting features:
     - Added functionality to print notes directly from the app
    - Implemented note export as PDF and Word document options using Expo's Print API
