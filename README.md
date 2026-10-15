# Student Help Desk
Student Help Desk is a fully featured desktop application developed using JavaFX technology, acting as a single point of support for students of a university. It allows students to request and follow up on support tickets, view a knowledge base of frequently asked questions, and chat with customer support professionals in real-time. It allows customer support professionals to manage support requests and customer support activities as well.
## Key Features
### For students
- Secure login: Role based login/authentication
- Ticket Management: create, view, and track tickets with different priority levels
- KnowledgeBase: can search for FAQ's in the system for self help
- Live Chat: real time communication with AI chatbot
- Dahsboard: personalized view of tickets and their status

### For agents
- Agent Dashboard: Overview of tickets assigned to them and key metrics
- Ticket processing: Update or escalate ticket status

### For admins
- Admin Dashboard: Thorough system overview with analytics
- Content Management: Maintain and update knowledge base and FAQ system
- System monitoring: track overall activity and performances.

# Technology Framework
- Frontend: JavaFX with FXML for UI structure
- Styling: CSS for visual presentation
- Data Persistence: Plain text file storage (users.txt, tickets.txt, faqs.txt)
- Design Pattern: Modular MVC architecture
# System requirements
## Minimum Requirements
- Java: JDK 17 or later
- JavaFX SDK: Compatible with your JDK version
- IDE: IntelliJ IDEA, NetBeans, or Eclipse with JavaFX support
- Memory: Minimum 2GB RAM
- Storage: 100MB free disk space
## Recommended Setup
- Java: JDK 21
- JavaFX: JavaFX 21 SDK
- IDE: IntelliJ IDEA 2023+
- Memory: 4GB RAM or more
# installation
Step 1: Download the Project

![img.png](img.png)

Step 2: Import into IDE (IntelliJ IDEA)
- Open IntelliJ IDEA
- Select File → Open
- Navigate to the extracted project folder
- Click OK to open as a project
- Set Project SDK to Java 17+

Step 3: Configure JavaFX
- Download JavaFX SDK from Gluon's Official Site
- Add JavaFX Library:
  File → Project Structure → Libraries
  Click + → Java
  Navigate to javafx-sdk-XX/lib
  Click OK to add
- Configure Run/Debug Configuration:
  Click "Edit Configurations" (top-right)
  Add VM Options:

![img_1.png](img_1.png)

Adjust the path to your JavaFX SDK location

Step 4: Build and run
- Locate Main Class: src/controllers/Main.java
- Run the Application:
  Right-click Main.java → Run 'Main.main()'
  Or click the green run button in your IDE

# User guide
## Student User guide
1. Login
   Launch the application
   Enter login credentials mentioned in the users.txt file in the project folder (Automatically fills the login form)
   Click Login

You'll be redirected to your Student Dashboard

2. Dashboard:
- Ticket Overview: Counts of Open/Resolved tickets
- Quick Actions:
  Create New Ticket
  View My Tickets
  Chat Support (chatbot)
  Browse FAQs
  Provide Feedback

## Agent User guide
1. Agent login:
   Enter agent credentials from users.txt file in the project folder
   Access Agent Dashboard
2. Agent Dashboard Features
   Manage Assigned Tickets: Tickets assigned to you
   Process Tickets
   View insights

## Agent User guide
1. Admin Login
   Enter admin credentials from users.txt file
   Access Admin Dashboard
2. Dashboard features
   System Statistics
   Activity log
   View User feedback
   Update FAQ's

# License & Attribution
This project is developed for educational purposes as part of a software engineering course. All rights reserved by the development team.