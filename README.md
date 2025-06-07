# Scholarship Finder App

A full-stack web application that helps users discover and apply for scholarships. Built with React (frontend) and Node.js/Express with MongoDB (backend).

## Getting Started

Follow these instructions to set up the project on your local machine.

### 1. Clone the Repository

```bash
git clone <your-repo-url>
cd scholarship-finder
```

### 2. Setup the Frontend

```bash
cd frontend
npm install
npm start
```

### 3. Setup the Backend

```bash
cd ../backend
npm install
node server.js
```

### 4. Create `.env` Files

#### `frontend/.env`

```
REACT_APP_API_URL=http://localhost:3001
```

#### `backend/.env`

```
PORT=3001
DB_URI=mongodb://localhost:27017/scholarship-finder
JWT_SECRET=your_jwt_secret_key
JWT_EXPIRES_IN=1d
```

### 5. Scrape Scholarships

To populate the database with scholarships:

```bash
cd backend/scrapers
node index.js
```

### 6. Register and Use the App

* Visit the React app in your browser (typically at `http://localhost:3000`).
* Register a new account.
* Browse available scholarships and recommended scholarships (using matching scores).

---

## Tech Stack

* **Frontend**: React, Axios, React Router
* **Backend**: Node.js, Express.js, MongoDB, Mongoose, JWT
* **Scraping**: Cheerio, Axios

## License

[MIT](LICENSE)

---

For any questions or contributions, feel free to open an issue or submit a pull request!



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
