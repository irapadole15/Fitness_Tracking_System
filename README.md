#  Fitness Tracking System

A full-stack Fitness Tracking Web Application built with **Spring Boot** (Java) for the backend and **React.js** for the frontend. This system allows users to manage their diet plans, track workout routines, and browse through personalized exercise recommendations — all from one platform.

---

##  Features

-  Personalized Diet Plan Management
-  Activity Planning and Logging
-  Exercise Listing and Search
-  User-friendly Dashboard
-  Secure RESTful APIs with Spring Boot
-  Responsive UI built with React, HTML, CSS, and JavaScript

---

##  Tech Stack

###  Frontend
- React.js
- HTML5 & CSS3
- JavaScript

### Backend
- Java
- Spring Boot (REST API)
- Spring MVC, Spring Data JPA

###  Database
- MySQL

---

##  Project Structure

```

fitness-tracking-system/
│
├── backend/
│   ├── src/main/java/com/fitness/
│   │   ├── controller/
│   │   ├── model/
│   │   ├── repository/
│   │   ├── service/
│   │   └── FitnessTrackingApplication.java
│   └── resources/
│       └── application.properties
│
├── frontend/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── App.js
│       └── index.js
│
├── README.md
└── .env

````

---

## Getting Started

### Prerequisites
- Java 17+
- Node.js & npm
- MySQL Server
- Maven

### Clone the Repository

```bash
git clone https://github.com/your-username/fitness-tracking-system.git
cd fitness-tracking-system
````

---

### Backend Setup

```bash
cd backend
mvn clean install
```

Edit `application.properties` and update your MySQL credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/fitness_db
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
```

Run the Spring Boot application:

```bash
mvn spring-boot:run
```

---

### Frontend Setup

```bash
cd frontend
npm install
npm start
```

---

##  API Endpoints

| Endpoint          | Method | Description              |
| ----------------- | ------ | ------------------------ |
| `/api/users`      | GET    | Get all users            |
| `/api/diet-plans` | POST   | Create a diet plan       |
| `/api/exercises`  | GET    | List available exercises |
| `/api/activities` | POST   | Log workout activity     |

---

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

---

##  Demo Users (Optional)

You can preload some sample data into your MySQL database to test functionality.

---

##  Future Enhancements

* [ ] Integration with wearable fitness devices (Fitbit, etc.)
* [ ] Admin dashboard for analytics
* [ ] Notifications & email reminders
* [ ] Mobile-friendly PWA support

---

##  Contact

 [irapadole2004@gmail.com](mailto:irapadole2004@gmail.com)
 [LinkedIn](https://www.linkedin.com/in/ira-padole-3487062b4) • [Portfolio](https://irapadole.com)

```
