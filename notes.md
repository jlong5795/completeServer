# Workflow

- create repository > clone repo
- add .gitignore
- add package.json
- update test script to use jest
- add "jest" configuration to package.json
- add "server" and "start" scripts to package.json

## Features

    - list of cohorts
    - add a cohort
    - list of cohort's students
    - list of students
    - add a student
    - list of student's cohorts

| Feature                | Method | URL                       |
| :--------------------- | :----- | :------------------------ |
| List Cohorts           | GET    | /api/cohorts              |
| Add Cohorts            | POST   | /api/cohorts              |
| View Cohort's Students | GET    | /api/cohorts/:id/students |
| List of Students       | GET    | /api/students             |
| Add Student            | POST   | /api/students             |
| View Student's Cohorts | GET    | /api/students/:id/cohorts |

## Cohorts

    - id
    - name
    - start date

## Students

    - id
    - name

## Testing

- functions: invoke the function with optional arguments => check return
- endpoints: make a request with optional arguments => check the response