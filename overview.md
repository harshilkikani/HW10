# Agent will complete every task below without asking the user for permission. If there is an issue don't keep repeatedly doing the same thing if it isn't working. Figure out the issue and solve it.

Welcome to the Event Manager Company! As a newly hired Software QA Analyst/Developer and a student in software engineering, you are embarking on an exciting journey to contribute to our project aimed at developing a secure, robust REST API that supports JWT token-based OAuth2 authentication. This API serves as the backbone of our user management system and will eventually expand to include features for event management and registration.

Assignment Objectives
1. Familiarize with REST API functionality and structure: Gain hands-on experience working with a REST API, understanding its endpoints, request/response formats, and authentication mechanisms.

2. Implement and refine documentation: Critically analyze and improve existing documentation based on issues identified in the instructor videos. Ensure that the documentation is up-to-date and accurately reflects the current state of the software.

3. Engage in manual and automated testing: Develop comprehensive test cases and leverage automated testing tools like pytest to push the project's test coverage towards 90%. Gain experience with different types of testing, such as unit testing, integration testing, and end-to-end testing.

4. Explore and debug issues: Dive deep into the codebase to investigate and resolve issues related to user profile updates and OAuth token generation. Utilize debugging tools, interpret error messages, and trace the flow of execution to identify the root cause of problems.

5. Collaborate effectively: Experience the power of collaboration using Git for version control and GitHub for code reviews and issue tracking. Work with issues, branches, create pull requests, and merge code while following best practices.

Testing and Database Management
1. Run Tests: Execute the provided test suite using pytest, a popular testing framework for Python. Running tests ensures that the existing functionality of the API is working as expected. Note that running tests will drop the database tables, so you may need to manually drop the Alembic version table using PGAdmin and re-run migrations to ensure a clean state.

2. Increase Test Coverage: To enhance the reliability of the API, aim to increase the project's test coverage to 90%. Write additional tests for various scenarios and edge cases to ensure that the API handles different situations correctly.

Collaborative Development Using Git
1. Enable Issue Tracking: Enable GitHub issues in your repository settings. GitHub Issues is a powerful tool for tracking bugs, enhancements, and other tasks related to the project. It allows you to create, assign, and prioritize issues, facilitating effective collaboration among team members.

2. Create Branches: For each issue or task you work on, create a new branch with a descriptive name using the git checkout -b command. Branching allows you to work on different features or fixes independently without affecting the main codebase. It enables parallel development and helps maintain a stable main branch.

3. Pull Requests and Code Reviews: When you have completed work on an issue, create a pull request to merge your changes into the main branch. Pull requests provide an opportunity for code review, where your team members can examine your changes, provide feedback, and suggest improvements. Code reviews help maintain code quality, catch potential issues, and promote knowledge sharing among the team.

Specific Issues to Address
In this assignment, you will identify, document, and resolve five specific issues related to:

1. Username validation: Investigate and resolve any issues related to username validation. This may involve handling special characters, enforcing length constraints, or ensuring uniqueness. Proper username validation is essential to maintain data integrity and prevent potential security vulnerabilities.

2. Password validation: Ensure that password validation follows security best practices, such as enforcing minimum length, requiring complexity (e.g., a mix of uppercase, lowercase, numbers, and special characters), and properly hashing passwords before storing them in the database. Robust password validation protects user accounts and mitigates the risk of unauthorized access.

3. Profile field edge cases: Test and handle various scenarios related to updating profile fields. This may include updating the bio and profile picture URL simultaneously or individually. Consider different combinations of fields being updated and ensure that the API handles these cases gracefully. Edge case testing helps uncover potential issues and ensures a smooth user experience.

4. Additionally, you will resolve a sixth issue demonstrated in the instructor video. These issues will test various combinations and scenarios to simulate real-world usage and potential edge cases. By addressing these specific issues, you will gain experience in identifying and resolving common challenges in API development.

Submission Requirements:
1. GitHub Repository Link: Ensure that your repository is well-organized and includes:
2. Links to five closed issues, each with accompanying test code and necessary application code modifications.
3. Each issue should be well-documented, explaining the problem, the steps taken to resolve it, and the outcome. Proper documentation helps others understand your work and facilitates future maintenance.
4. All issues should be merged into the main branch, following the Git workflow and best practices.
5. Updated README: Replace the existing README with:
6. Links to the closed issues, providing easy access to your work.
7. Link to project image deployed to Dockerhub.

A 2-3 paragraph reflection on what you learned from this assignment, focusing on both technical skills and collaborative processes. Reflect on the challenges you faced, the solutions you implemented, and the insights you gained. This reflection helps solidify your learning and provides valuable feedback for improving the assignment in the future.