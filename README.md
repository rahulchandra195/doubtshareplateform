
Overview



DoubtShare is a real-time doubt-solving website meant to assist students with their academic problems in an engaging manner. By facilitating communication between tutors and students, the platform guarantees effective settlement of doubts.

Features of the Product
Types of Users Students:

Qualities: Language and class grade. Steps taken: Make requests for doubt. Instructors:

Qualities: Question language, class rank, and subject knowledge. Respond to inquiries from students about doubts.

Indicates the language, class grade, and doubt subject. System locates online tutors who meet the requirements. Instantaneous Notification:

Instant notifications are sent to qualified tutors.

monitors the available tutors in real time.

updates the "Tutor Availability" table with each tutor's most recent ping time every three seconds. CRON Work:

counts the tutors who are now available in real time every second.

Technologies used
the project is build in :
 MongoDB: Database
Express.js: Backend Framework
React.js: Frontend Library
Node.js: Runtime Environment

Navigate to the project directory:

cd frontend
cd backend
Install dependencies:
npm install

Set up the MongoDB connection and other environment variables.

Run the application:

For frontend : npm start
For backend : npm run server

User Routes
1.Register

>Endpoint: /register
>Method: POST
>Description: Allows users to register on the platform.

2.Login
>Endpoint: /login
>Method: POST
>Description: Allows users to log in and receive an authentication token.
>
3.Logout
>Endpoint: /logout
>Method: GET

 Doubt Routes
 
1.Get Doubt History
Endpoint: /doubt/history
Method: GET
Description: Retrieves the doubt history of the currently logged-in student.
2.Add Doubt
Endpoint: /doubt/addDoubt
Method: POST
Description: Allows students to add a doubt.
Tutor Routes
Get Tutor Profile
Endpoint: /tutor/gettutor
Method: GET
Description: Retrieves the profile of the currently logged-in tutor.
Add Tutor Data
Endpoint: /tutor/addData
Method: POST
Description: Allows tutors to add their profile information.
Update Tutor Data
Endpoint: /tutor/updateData
Method: PATCH
Description: Allows tutors to update their profile information.

Update Tutor Ping
Endpoint: /tutor/update-ping
Method: POST
Description: Updates the last ping time for a tutor.




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
