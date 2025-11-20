🚀 Project Title: “Online Feedback Collector with Admin   Dashboard”  

# OnlineFeedBackCollection 

Online Feedback Collection  Form , full-stack web application that collects feedback from users.  
The Online Feedback Collector System is a web-based application designed to collect, store, and analyze user feedback in a structured and efficient manner. Traditional feedback collection methods using paper forms or manual entry are time-consuming, prone to errors, and difficult to analyze.
This system provides a digital solution that enables users to submit their feedback easily, while administrators can view and analyze responses in real time.
The project is developed using Flask (Python) for backend processing, SQLite for database management, HTML/CSS/Bootstrap for user interface, and Chart.js for graphical analytics.  


2. Purpose of the System
   
The main purpose of this system is to:
•	Collect user feedback online in a simple and user-friendly way.
•	Maintain all feedback information in a digital database.
•	Provide an admin dashboard for viewing, analyzing, and managing feedback.
•	Generate visual analytics such as rating charts for quick understanding.
•	Replace manual feedback processes with a faster and more accurate system. 


4. Problem Definition
   
Many institutions and organizations still rely on manual surveys, which have several drawbacks:
•	Time-consuming data collection
•	Difficulty in organizing and analyzing responses
•	Higher chances of human error
•	Limited insights due to lack of visual representation
This project solves these challenges by offering an automated, accurate, and user-friendly online feedback system. 

6. Scope of the Project
   
This project can be used in:
•	Colleges and universities (student feedback)
•	Training institutes
•	Product or service review systems
•	Customer satisfaction surveys
•	Event feedback collection 

7. The system includes:
   
✔ Feedback form 

✔ Admin login/dashboard

✔ Analytics (bar chart of ratings)

✔ API endpoint for feedback export

✔ Database storage 

9. System Overview
The system contains two main modules:

A. User Module 

•	Users enter details such as name, email, rating, and comments
•	Feedback is stored securely in the database
•	Users receive confirmation of submission

B. Admin Module
•	Access to dashboard
•	View list of all feedback
•	View total number of feedback entries
•	View average rating
•	Analyze rating distribution using charts
•	Export feedback through API  


Working of this module:   



<img width="768" height="117" alt="image" src="https://github.com/user-attachments/assets/a55f3c80-5be3-4bf4-8a06-dccc5e1473ad" /> 









<img width="788" height="516" alt="image" src="https://github.com/user-attachments/assets/37ea63a9-02a6-4527-b141-aef61d23762b" />





  
 

 <img width="788" height="516" alt="image" src="https://github.com/user-attachments/assets/d1ffc910-affd-4f95-b162-ca41ecf47acd" />  










 <img width="788" height="516" alt="image" src="https://github.com/user-attachments/assets/5589bf76-9525-4f03-8bcf-335f5b094ff5" /> 









 6. Technologies Used
Frontend

•	HTML 

•	CSS

•	Bootstrap

•	JavaScript

•	Chart.js (for charts) 

Backend 

•	Python 

•	Flask Framework 

Database

•	SQLite (lightweight file-based database)

7. System Architecture
   
User → Feedback Form → Flask Backend → SQLite Database 

Admin → Dashboard → Flask Backend → SQLite Database → Charts (Chart.js) 


The architecture follows the MVC (Model-View-Controller) pattern: 


•	Model: Feedback data stored in SQLite 

•	View: HTML templates for user and admin pages 

•	Controller: Flask routes handling logic  


OnlineFeedbackCollector/

│
├── app.py # Flask backend code

├── requirements.txt # Required Python packages

├── database.db # SQLite database (empty, students will add data)
│
├── static/

│ ├── css/

│ │ └── style.css # Basic styling

│ └── js/

│ └── script.js # JS for form validation (optional)
│
├── templates/

│ ├── index.html # Home page with feedback form

│ ├── admin.html # Admin dashboard page

│ └── layout.html # Base HTML template for reuse
│
└── README.md # Project instructions and setup guide 

8. Advantages of the System
   
•	Easy to use and highly interactive
•	Accurate data collection and storage
•	Real-time analytics and dashboard view
•	Portable and lightweight 
•	Paperless system
•	Improves decision-making through insights 


9. Applications
•	Educational feedback systems
•	Product review websites
•	Customer service evaluation
•	Training and workshop feedback
•	Event feedback collection forms


Design by Ruheena Tasneem 

Contributors: Please all intern welcome to improve to level of best.  

You Tube :   https://www.youtube.com/watch?v=CCgRcJHknyo 

GitHub  :  https://github.com/ruheenatasneem/OnlineFeedBackCollection


10. Conclusion
    
The Online Feedback Collector System provides a modern solution for gathering and analysing feedback. With its simple interface, real-time analysis, and efficient database handling, it serves as a powerful tool for organizations to understand user opinions and improve their performance.









 

 

  
 
 
 



 
