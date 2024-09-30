# EventTrackingApplication

## Overview
EventTrackingApplication is a powerful, easy-to-use tool that allows users to manage and track their events efficiently. The app allows users to create, edit, and manage events, as well as receive notifications via SMS to ensure they never miss an important date.

This project is designed as part of a CS360 project, showcasing Android development skills and event management functionality using SMS reminders and phone state management.

---

## Features
- **Event Creation and Editing**: Add and modify events with relevant details.
- **SMS Notifications**: Automatically send SMS notifications to remind users about upcoming events.
- **Event List Management**: View, edit, and delete events from a comprehensive list.
- **Minimal Permissions**: The app only requests permissions for sending SMS and reading phone state.

---

## Permissions
The following permissions are required for EventTrackingApplication to function correctly:
- **Send SMS** (`SEND_SMS`): To send event reminders via SMS.
- **Read Phone State** (`READ_PHONE_STATE`): To manage and handle phone states for SMS notifications.

---

## Requirements
- **Android Version**: The app supports Android 7.0 (Nougat) and higher.
- **Development Environment**: Android Studio with Gradle for build automation.
  
---

## Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The EventTrackingApplication was developed to help users manage and track their events seamlessly. The app is designed to address the user need for timely reminders about important events, with SMS notifications ensuring that users stay informed, even without internet access. Users can create, edit, and delete events, making it an all-in-one event management tool. The core goal was to provide a simple, easy-to-use interface with reliable notification features.

## What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The following screens and features were necessary to support user needs:

Main Screen (Event List): Displays all created events in a list format, allowing users to easily see upcoming events.
Add Event Screen: Enables users to create new events, adding details such as date, time, and description.
Edit Event Screen: Allows users to modify existing events.
SMS Notifications: Sends reminders via SMS based on the set event time.

## How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

The process of coding the app was centered around modularity and reusability. Key techniques included:

Separation of Concerns: Keeping the UI code separate from business logic (e.g., using separate activities for UI, and helper classes for database management).
Use of Adapters: Implementing EventAdapter to bind event data to the UI components like RecyclerView.
Database Management: Utilizing SQLite to store and retrieve event data efficiently.
These strategies ensured that the codebase was clean and maintainable, making future updates and feature additions easier. In the future, these techniques could be applied to other projects, especially those involving data handling and UI interactions.

## How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I simply used the app on my phone to ensure that the apps functionality was working as expected. 

## Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

The application I created was fairly simple and did not present too many challenges. The biggest challenge was figuring out how to implement each function. It took a lot of research to implement each function, especially when it came to the implementation of the database. This was a concept that was fairly new to me. 

## In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

Implementing a full stack application that has a dynamic database, showcases my ability to develop the simple aspects of a CRUD app which most business APIs rely upon. 
