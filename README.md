# TaskTrackr – Git Collaboration Lab

## Overview

TaskTrackr is a collaborative full-stack web application developed as part of a Git version control laboratory exercise. The project is designed to simulate a professional software development workflow where multiple developers work simultaneously on separate feature branches, submit Pull Requests (PRs), perform peer code reviews, and resolve merge conflicts before integrating changes into the main branch.

Rather than focusing on application complexity, this lab emphasizes industry-standard Git practices such as branching strategies, collaborative development, code reviews, conflict resolution, and maintaining a clean project history.

---

## Project Objectives

The primary objectives of this laboratory exercise are to:

* Practice working with feature branches in a collaborative environment.
* Create meaningful and atomic Git commits.
* Use Pull Requests for feature integration.
* Perform peer code reviews and provide constructive feedback.
* Resolve merge conflicts manually.
* Understand the Git commit graph and collaborative workflow.
* Maintain a stable and protected `main` branch throughout development.

---

## Technologies Used

* PHP 8+
* HTML5
* CSS3
* JavaScript (Vanilla)
* Git
* GitHub

---

## Project Structure

```text
tasktrackr-web/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── app.js
├── api/
│   ├── tasks.php
│   └── utils.php
├── data/
│   └── .gitkeep
├── tests/
│   └── test_tasks.php
└── README.md
```

---

## Team Roles

The project is divided among five team members, each responsible for a separate branch and feature.

| Role               | Branch                    | Responsibility                                       |
| ------------------ | ------------------------- | ---------------------------------------------------- |
| Project Maintainer | `main`                    | Repository setup, Pull Request reviews, final merges |
| Developer A        | `feature/priority-tags`   | Priority tagging for tasks                           |
| Developer B        | `feature/due-dates`       | Due dates and overdue reminders                      |
| Developer C        | `feature/search-filter`   | Search and filtering functionality                   |
| QA / DevOps        | `feature/tests-and-utils` | Utility functions, testing scripts, documentation    |

Each contributor develops independently on their own feature branch before submitting changes through a Pull Request.

---

## Features

### Core Features

* Create tasks
* Display task list
* Mark tasks as completed

### Additional Features

* Task priority levels (High, Medium, Low)
* Due date support
* Overdue task highlighting
* Live task search
* Status filtering
* Utility helper functions
* Basic PHP test scripts

---

## Git Workflow

The project follows a collaborative Git workflow consisting of:

1. Clone the shared repository.
2. Create a dedicated feature branch.
3. Develop features independently.
4. Commit changes using descriptive commit messages.
5. Push changes to GitHub.
6. Open a Pull Request.
7. Undergo peer code review.
8. Address requested changes.
9. Merge approved Pull Requests into the protected `main` branch.

This workflow ensures that development remains organized while allowing multiple contributors to work simultaneously without disrupting the main codebase.

---

## Merge Conflict Exercise

A major component of the laboratory involves intentionally creating merge conflicts between the **Priority Tags** feature and the **Due Dates** feature.

Students are expected to:

* Identify Git conflict markers.
* Manually merge conflicting code.
* Preserve functionality from both branches.
* Remove conflict markers.
* Commit the resolved merge.
* Verify that the application continues to function correctly.

This exercise provides practical experience resolving one of the most common issues encountered during collaborative software development.

---

## Running the Project

### Start the PHP Development Server

```bash
php -S localhost:8000
```

Open the application in your browser:

```text
http://localhost:8000
```

---

## Testing

Execute the lightweight PHP test script:

```bash
php tests/test_tasks.php
```

The script validates basic task creation and completion functionality without requiring external testing frameworks.

---

## Learning Outcomes

After completing this project, team members will be able to:

* Work collaboratively using Git and GitHub.
* Apply feature-branch development strategies.
* Write meaningful commit histories.
* Conduct Pull Request reviews.
* Resolve merge conflicts confidently.
* Understand collaborative software development practices used in professional environments.

---

## Deliverables

Successful completion of the laboratory includes:

* Git commit graph (`git log --graph --oneline --all`)
* Pull Request history with reviews and approvals
* Merge conflict documentation
* Fully integrated application with all features functioning correctly
* Project documentation and testing scripts

---

## License

This project was created for educational purposes as part of a Git collaboration laboratory exercise. It is intended to demonstrate collaborative software development practices using Git and GitHub.
