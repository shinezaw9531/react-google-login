>>>>   frontend:
        npx create-react-project react-google-login
        npm install react-google-login
        edit App.js
        create h1 for app name
        define loginData state hook
        check loginData and render content
        if loginData is null render GoogleLogin component
        if loginData isn't null render you are logged in message
        implement handleLogout
        implement handleFailure
        implement handleLogin

>>>>>   google cloud platform
        login to google
        go to https://console.cloud.google.com
        create a project
        go to api credential
        accept consent screen
        create oauth client id
        create .env file and save it as REACT_APP_GOOGLE_CLIENT_ID

>>>>    backend:
        edit package.json add proxy": "http://127.0.0.1:5000/",
        create server.js file
        npm install express dotenv google-auth-library
        config dotenv
        create OAuth2Client client
        create express server
        use express.json()
        define app.post('/api/google-login',...)
        define app.listen

>>>>    heroku publish
        create Procfile
        create
