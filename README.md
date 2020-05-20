


# Tutor Marketplace

Heroku deployment: https://tutor-marketplace-sei.herokuapp.com/


Tutor Marketplace is an app that connects students with teachers to facilitate online learning.  It is free to join and create your profile, so you pay nothing until you find the lesson that you're looking for. Users can log in as students or as teachers, and their profile and functions will vary depending on which.  Teachers can add lessons and availability, while students can select teachers and lessons. All lessons are currently one-on-one. 

## Technologies used
Python, Django, PostgreSQL, Bootstrap, HTML, Heroku

## User Stories

User enters the site and reaches the homepage, where they can choose a language. Alternatively, they can choose to view a list of all teachers.
If they choose language, they will only see teachers who can teach that language. If they choose all teachers, they will see all registered teachers. 
Then student can register and sign in, and choose a teacher. Each teacher will have a calendar with available lessons and class times to choose from.
A student when signed in can see the current teachers they are signed up for, and past teachers. 
Teachers can register and create a profile. Once signed in, they can see current students and past students.

### Future development

* Search capability
* Choose a topic with teacher (conversational practice, reading & writing, etc)
* Ratings - students rate teachers (and vice versa?)
* Payment via Stripe
* Add teaching subjects other than languages

## Data Model
* One to many relationship between Teacher, Lessons, and Language. 
* Many to many relationship between Students and Lessons
![Data Model](./main_app/static/images/ERD.png)

## Wireframes

![Wireframe](./main_app/static/images/wire2.png)
![Wireframe](./main_app/static/images/wire3.png)
![Wireframe](./main_app/static/images/wire4.png)
![Wireframe](./main_app/static/images/wire5.png)
![Wireframe](./main_app/static/images/wire6.png)
![Wireframe](./main_app/static/images/wire7.png)
![Wireframe](./main_app/static/images/wire8.png)
![Wireframe](./main_app/static/images/wire9.png)
![Wireframe](./main_app/static/images/wire10.png)
![Wireframe](./main_app/static/images/wire11.png)
![Wireframe](./main_app/static/images/wire12.png)

## Milestones

EOD Wed, 5/13: All deliverables to present to Kenny for project approval

EOD Thu, 5/14: One data model (Student/User) complete with urls, views and templates

EOD Fri, 5/15: Three related data models (Student/User, Teacher, Subject) complete with urls, views, and templates

Weekend: CSV files with established shared dbs for testing, add Availability functionality to Teacher, begin CSS using Bootstrap 

EOD Mon, 5/18: Fully functioning app with four related data models (Student/User, Teacher, Subject, and Lessons) complete with urls, views, and templates 

Throughout Tue, 5/19: Working out bugs, improving style/layout, looking into stretch goals
