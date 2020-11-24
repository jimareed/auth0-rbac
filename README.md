# auth0-rbac
Simple RBAC example using Auth0 (under development)


Config setup
1. create auth0 account
2. create app
3. set Allowed Callback URLs and Allowed Logout URLs and Allowed Web Origins to http://localhost:3000

Initial setup
```
npm install
```

Run
```
export REACT_APP_DOMAIN=-- insert here --
export REACT_APP_CLIENTID=-- insert here -- 
export REACT_APP_AUDIENCE=-- insert here -- 
npm start
```

Follow the instructions to install and run the backend at: https://github.com/jimareed/auth0-react-backend

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

