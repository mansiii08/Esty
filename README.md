# team-project-team-eight
team-project-team-eight created by GitHub Classroom

# Airport-Management-system

### Team Members
1. Amika Mehta (015957695)
2. Dhruva Gajera (016040934)
3. Milan Dudhatra (015998645)
4. Virag Bhanderi (015277340)

### Summary of Contributions

- Amika Mehta
  - Designed frontend functionality for User Login/signup.
  - Created separate NavBar component to be used in all pages.
  - Implemented the frontend functionality for viewing flight details.
  - Communicated with team members throughout the project and maintain sprint task sheet.

- Dhruva Gajera
  - Designed the backend APIs for user login/signup.
  - Implemented the backend functionality for viewing flight details.
  - Designed the backend APIs automatic gate assignment.
  - Integrated frontend pages and tested API calls.

- Milan Dudhatra
  - Designed the backend APIs for Airline emoployee.
  - Implemented the backend functionality for baggage claim.
  - Implemented the frontend functionality for viewing flight details.
  - Provided regular feedback between sprints.

- Virag Bhanderi
  - Designed user login and signup page.
  - Designed the frontend for admin side to add flight and automatic gate assignment.
  - Designed pages for view flights, gate assignment and baggage claim.
  - Implemented routing on the frontend side.
  

### Architecture Diagram
https://github.com/gopinathsjsu/team-project-team-eight/blob/main/Documentation/ArchitectureDiagram.png

### Class Diagram
https://github.com/gopinathsjsu/team-project-team-eight/blob/main/Documentation/Class%20Diagram.png

### Wire Frame
https://github.com/gopinathsjsu/team-project-team-eight/blob/main/Documentation/WireFrame.png

### Link to team's GitHub Repo 
https://github.com/gopinathsjsu/team-project-team-eight

### Link to team's Google Sprint Task Sheet
https://github.com/gopinathsjsu/team-project-team-eight/blob/main/Documentation/Task-sheet.xlsx

### Tools and Languages Used
Frontend : React JS
Backend : Node JS, Express JS
Database : MySQL
Cloud : AWS EC2

# Extreme Programming (XP) Core Values

1. Communication

Our team's capacity for communication was one of its greatest strengths. The best kind of communication, in our view, is face-to-face communication.
As a consequence, we all sit one on one in same room for the crucial sessions, removing any barriers to communication.
Additionally, on Mondays and Tuesdays of every week, our team held scrum meetings.During the call, we spoke about our progress and dealt with issues with dependency and other obstacles. In order to oversee the project and keep track of our user stories,we used Project Dashboard - Jira .This allowed us to track the progress of several tasks during the sprint. We decided to take on duties based on our individual strengths and to support one another by collaborating frequently via Google Meet meetings. During the meetings, any issues or problems were routinely aired.

2. Simplicity

The most crucial components of the scope of the project were identified using a critical eye, and we only finished the necessary tasks.
We actively worked to remove duplications when we introduced additional APIs and corresponding UI components, which helped us keep our code easy to maintain.We ensured that all class names, method names, and local variables were unambiguous and indicated the objective.

3. Feedback

We believe in feedback. We have given valuable feedback to the team to create a better product. After every development item is 
completed, the team gave feedback on the delivered item for changes/suggestions. We also tested features made by other team members and 
provided comments to each other during the testing process. It aided us in locating the bugs.

4. Respect

Everyone was considerate of the time, efforts and views of the other team members. 
During the process of selecting technological stacks, team members acknowledged each other's viewpoints and ideas. 
Everyone politely agreed on the technologies chosen by a majority vote, and committed to study and develop the necessary abilities 
to put them into practice. When a group member experienced an unexpected challenge, all of us were empathetic and polite, and everyone 
volunteered to make and solve the situation.



# Feature Set 

1. Three personas—Airlines Employee, Airport Employee, and General Users—are used for role-based identification to access the system.

2. All Users
Get the arrival and departure times of flights (for the next one, two, and four hours), updated gate information, and the arrival file's luggage carousel number.

3. Airline Worker:
Add, modify, and remove flights from their airline that are pertinent to that airport.
For arriving and departing flights, a random gate assignment is used to avoid scheduling conflicts.

4. Airport personnel:
For maintenance, you can enable or disable one or more gates and view information about each one, such as its state.
Give arriving flights a luggage carousel number; the system should prevent conflicting assignments.
