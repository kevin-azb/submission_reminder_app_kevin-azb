
# Submission Reminder App

A  Linux-based application that alerts students about upcoming assignment deadlines.  
This project was built as part of a shell scripting assignment to automate the creation of a simple reminder system.

---

##  Project Structure

After running the setup script, your directory will look like this:

```
submission_reminder_<name>/
├── app/
│   └── reminder.sh             # Main reminder logic
├── assets/
│   └── submissions.txt         # Student submission records
├── config/
│   └── config.env              # Application configuration
├── modules/
│   └── functions.sh            # Helper functions
└── startup.sh                  # Application startup script
```

---

##  How to Run the Application

### 1. Clone the Repository
```
git clone https://github.com/kevin-azb/submission_reminder_app_kevin-azb.git
cd submission_reminder_app_kevin-azb
````


### 2. Create the Environment

Run the setup script and enter your name when prompted:

```
./create_environment.sh
```

This will generate a folder named:

```
submission_reminder_{YourName}
```

### 3. Start the Application

Navigate to your app folder and run:

```
cd submission_reminder_{YourName}
./startup.sh
```

---

##  File Descriptions

| File Name           | Description                                                                    |
| ------------------- | ------------------------------------------------------------------------------ |
| **config.env**      | Stores configuration variables like reminder interval and notification method. |
| **reminder.sh**     | The main script that checks for upcoming deadlines.                            |
| **functions.sh**    | Contains reusable functions for the app (e.g., deadline checking).             |
| **submissions.txt** | Records of students, their assignments, due dates, and submission status.      |
| **startup.sh**      | Launches the reminder script automatically.                                    |

---

##  Testing

You can edit `submissions.txt` to add or modify student records.
Format:

```
student,assignment,submission status
```

* **status**: `not submitted` or `submitted`.

Example:

```
Kevin,Science Project,submitted
```

---

## Author 

```
Developed by Kevin IKuzwe as part of a Linux shell scripting assignment.

```



