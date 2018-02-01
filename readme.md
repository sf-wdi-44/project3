# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project #3: Building a Full Stack MERN Application

## Overview

While your Project 1 taught you how to write a fullstack application in JavaScript using Express, Mongoose, and Node, this project will have you building another full stack application, but this time with a React front-end.

Your team will build an app with two major components:

1. An API of your own design, built using Node, Express, and Mongoose, that serves JSON.
2. Front-end React code that updates the UI and makes requests to the API.

**This is meant to push you both technically and collaboratively.**  You will, almost certainly, be joining a development team during your career.  Working collaboratively is a learned skill, just like programming. It's important to learn how to work together.

---

## Planning & Deliverables

###### What will we be turning in?

### Project Planning Deliverables

**You must review the following with your instructional team BEFORE you start to code.**

* **Scope/MVP:** What are you planning to build? What do you reasonably think you can implement in the time period?
* **User Stories:** Who is your user? What features will your app have? Set up your project and user stories in <a href="https://trello.com" target="_blank">Trello</a> or in some other organized format.
* **Wireframes:** Sketch out what your core pages will look like and how they will work. Consider making a *paper prototype* to demonstrate and/or test key user interactions.
* **Data Models (ERD):** Draw out the models and any associations for your project in an entity relationship diagram (ERD).
* **Milestones:** Outline the milestones/sprints for your group. Identify where in those sprints you've met your MVP.

### Completed Project Deliverables

* Link to Heroku hosted front-end and back-end, with all core technical requirements completed.
* Link to two source code repos on GitHub.
* A `README.md` file on ONE of your repos with the following:
  * Description: Short paragraph (2-3 sentences) "elevator pitch" describing what your project does
  * Wireframes and user stories
  * Links to Heroku hosted project
  * Link to frontend/backend GitHub repo (each should link to the other)
  * Technologies (languages, external libraries, APIs)
  * Wish List / Future Development
  * Contributors (with links to their GitHub profiles)

---

### Requirements

> ### *Do not use Redux for this project*

#### Back-End Requirements
This app must contain a Node, Express, and Mongoose backend API with at least 2 models. No associations are required, but they're certainly encouraged. User authentication is **optional, and makes sense as a stretch goal**.

##### Specifics:
  * **Express:** Use Express for your server.
  * **MongoDB and Mongoose:** Use MongoDB for your database in development and production.
  * **Data Models** Include at least two data models, with associations if appropriate.
  * **Data Validation:** Your application should validate incoming data before entering it into the database.
  * **Heroku:** Deploy your app to Heroku. Ensure no app secrets are exposed. *Do not commit secret keys to GitHub!*

#### Front-End Requirements
  - This app must use a React front end that leverages the backend API in the above requirement.
  - Must use React Router to handle multiple views.
  - Must communicate with the back-end API RESTfully to Create, Read, Update, and Destroy resources, using fetch or axios.

##### Specifics:
  * **React:** Use React to create an elegant frontend for your application.
  * **Modular Components:** Your frontend code should be organized into logical components, using containers and models appropriately to store and fetch data.
  * **API Interaction:** Your frontend should provide a way of performing full CRUD on the API.
  * **Error Handling:** Forms in your application should validate data, handle incorrect inputs, and provide user feedback on the client side.
  * **Responsive Design:** Make sure your app looks great on a phone or tablet.
  * **Heroku:** Deploy your app to Heroku. Ensure no app secrets are exposed. *Do not commit secret keys to GitHub!*

#### Deployment
  - Your API must be deployed to one Heroku instance, and your frontend must be deployed to another Heroku instance.

    > We strongly recommend deploying your back-end and front-end separately. This will make it far easier to debug your deployed applications and manage your deployments. If you feel strongly about deploying your code in a different way, you need to convince Michelle this is a good idea.

---

### App Organization

You should split your application into **two** repositories, one for your React front-end and another for your Node-Express-Mongoose API.

---

### Contribution Guidelines

  - Each project should include a `readme.md` that defines the roles of each group member. Specifically, it should include the responsibilities of each member and their contributions.
  - Each member of your group is expected to present for an equal amount of time during [project presentations](presentations.md), which last at least 10 minutes per group.
  - During 10-minute daily standups, teams members must share progress with each other. Standup discussion topics may include goal-setting, time management, goal progress, and individual group contributions. This is **not** time to address technical issues. The instructors will check in with groups every day of project week.

---

### Process

* **Keep user stories small** and well-defined. Remember: user stories focus on what a user *needs*, not what development tasks need accomplishing.
* **Write pseudocode** before you write actual code. Thinking through the logic first helps.
* **Don't hesitate** to write throwaway code to solve short-term problems, then refactor to a better solution if you have time.
* **Read the docs** for whatever technologies / frameworks / API's you plan to use. (See ["RTFM"](https://en.wikipedia.org/wiki/RTFM))
* **Continuously Deploy** your code.

---

### Code

* **Keep your code DRY** and build your APIs RESTful.
* **Be consistent** with your code style. You're working in teams, but you're only making one app per team. Make sure it looks like a unified effort.
* **Commit early; commit often.** Don't be afraid to break something because you can always go back in time to a previous version (so long as you're committing often).
* **Deploy early; deploy often.** Deploy your work as early as possible, even if you don't really have anything completed. Heroku issues **always** pop up. Don't be caught short just before the submission deadline!
* **Name things appropriately.  Comment as necessary.** Do your naming conventions make sense? Would another developer be able to look at your app and understand what everything is? (See ["self-documenting"](https://en.wikipedia.org/wiki/Self-documenting)).  Even if it's obvious, comments can help to explain the intent -- the what and why.  This allows the next developer to understand the purpose and decide what can be adjusted to achieve the same goal.
* **Ensure it is well-formatted.** Are you indenting consistently? Can we find the start and end of every div, curly brace, etc?  Organizing the hierarchy is key to understanding.

Teams of developers usually adhere to an agreed-upon set of code-style rules. This reduces issues with reading our colleagues' code. We strongly recommend using [StandardJS linting](https://github.com/standard/standard#install). Instructions for Atom package installation [here](https://github.com/standard/standard#atom).

---


### Deadlines

Your **project planning work** must be approved by an instructor by **Friday, February 9, at 11:00am**. This will ensure you're able to set up the basics of your app before you leave for the weekend.

You will present this project on **Thursday, February 8, at 3:00 pm**. (Other classes will be invited to see your presentations!) For your presentation, please follow these guidelines:

* Your presentation should include the **motivation** for building this project and a **demo** of the core functionality.
* **Maximum 20 minutes.**
* **Minimum 5 slides.** Slides should include:
  * Wireframes
  * User stories
  * ERDs
  * Walk through the development of one feature from ideation to execution. At minimum, this should include wireframes, code samples, and the final result.
* **ALL group members must speak during the presentation.** Each group member should answer the following:
  * What parts of the project did you work on?
  * What was the most challenging aspect? Was there anything that was surprisingly easy to implement?
  * What did you learn?


---

### Bonuses

You should only attempt these bonuses if and only if you've satisfied project requirements.

#### User Authorization

Consider whether or not you want to introduce a barrier to entry for your application. Does it fit in with the idea of your application? User authorization is really tricky.

  > "Do I *really* need to log in just so I can post a link to a GIF?"

Use Passport for your authentication. The Passport lab is a good guide to setting up that functionality.

#### Image Uploading

Uploading images is **hard**. This is a great stretch goal for your application and should **not** be part of your core functionality/MVP.

#### Maps

If your application uses physical locations, consider adding a map ***as a bonus feature*** to your application. [Check out this Google Maps component library](https://tomchentw.github.io/react-google-maps/).
