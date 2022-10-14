# Student-Attendance-Management-System
## A flask based API that updates the Attendance of the Student.
### It has student and teacher as it's user classes. 
### Perfect for storing attendence of students in college of various departments and across various semester.



## It uses cloud firebase as its database.

### To use this project follow the following steps:
1. Create a project in firebase and then create an app.
2. Enable "Realtime Database", "Cloud Firestore", "Authentication SDK".
3. Register the web app in the Firebase console project to get the `Firebase config` snippet. Add this snippet to `./app.py` and `./static/js/firebaseConfig.js`
4. A `key` snippet has to be generated from the project settings
   - The key snippet is the generated private key file of the **Python** Firebase Admin SDK found in `Project Settings/Service Accounts`.
   - Add the key snippet from the Firebase console project to `./key.json`.
5. Add a random string to the `app.secret_key` variable at the start of the `./app.py` file.
6. To run the website: `python app.py`
7. To view running website: default: `localhost:5000` or `127.0.0.1:5000`

**NOTE** 
      - Please do not commit and upload (push) `key.json`, `firebaseConfig.json` without erasing your personal data from them and please leave the `app.secret_key` blank before committing and pushing.
