# Instagram Clone made with React

[hostedSite](https://instagram-clone-3b95e.web.app/)

### To make it run locally:

1. Add a firebase.js file in src folder
2. Import firebase from npm
3. Add code similar to this:

```javascript
import firebase from "firebase";

const firebaseApp = firebase.initializeApp({
  apiKey: "your api key",
  authDomain: "your auth domain",
  databaseURL: "your database URL",
  projectId: "your project ID",
  storageBucket: "your storage bucket",
  messagingSenderId: "your messaging SenderId",
  appId: "your app Id",
  measurementId: "your measurement ID",
});

const db = firebaseApp.firestore();
const auth = firebase.auth();
const storage = firebase.storage();

export { db, auth, storage };
```

4. Configure your firebase database
5. run `npm start` in terminal
