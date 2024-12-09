# Assignment guidelines

Last modified: 05.04.2024

> Note: This assignment guideline can stay in your submission. Kindly do not modify the guideline.

# Table of content

[ToC]

# Assignment Deliverables

- [ ] Create Test cases for all pages which are already there in project's **PageObject** folder
  - [ ] 03_RegisterPage
  - [ ] 04_ProjectPage
  - [ ] 05_IssuePage
- [ ] Perform all **TODO:** tasks describe in each above pages
- [ ] Create bug report for one test case which are already there in project's BugReport folder
  - [ ] 02_ProjectPageReport
- [ ] Write Learning Reflection page
  - [ ] 01_LearningReflection.md
- [ ] Now you have completed your assignment it's time for you to share your assignment in github and Canvas.
- [ ] Share your project on **GitHub**
  - [ ] Create a new repository
  - [ ] Add a README file and write your full name as seen on Laurea Pakki or Canvas, because your GitHub username may be different than your original name so it is easier for the teacher to recognize you and your assignment work.
  - [ ] Upload your all project files and folders, using the Add file drop-down, click Upload files. Drag and drop the file or folder you'd like to upload to your repository
  - [ ] **Do not upload the ZIP file on GitHub**
  - [ ] Share your GitHub repository link in the **Canvas Assignment comments**.
- [ ] Upload your project on **Cavas**
  - [ ] When you complete your testing assignment, Export it as a Zip file
  - [ ] “Firstname_Lastname_Testing_Project.zip”
  - [ ] **Return them to Canvas as one Zip file** Upload your project file (Zip) to the Canvas platform as an Assignment return,“Firstname_Lastname_Testing_Project.zip” and share your GitHub link

# Assignment Overview

## Functionality overview

The example application GitLab is a complete DevOps platform that enables professionals to perform all the tasks in a project—from project planning and source code management to monitoring and security. Furthermore, it allows teams to collaborate and build better software.

URL: https://gitlab.com

### Home page

- URL: https://gitlab.com/
- Precondition: login
- List of projects
- Pagination for list of projects

### Sign-in page

- URL: https://gitlab.com/users/sign_in

### Sign up page

- URL: https://gitlab.com/users/sign_up

### Profile page

- URL: https://gitlab.com/-/profile

### Project page

- to create a project
- URL: https://gitlab.com/projects/new
- Create a new blank project: https://gitlab.com/projects/new#blank_project
- Create a new project from the template: https://gitlab.com/projects/new#create_from_template

### Issue page

- Precondition: project
- URL: https://gitlab.com/group-slug-here/project-slug-here /-/issues/new
- Delete issue (click on pencil-icon for Edit or Delete issue)

## How to write Test Case

- Test Case assignment The folder "PageObject" includes five files.
- 01_Template_TestSuit.txt is a sample file to provide information which field you as a test designer should fill. You are not expected to to modifications to this file.
- 02_LoginPage.txt is a **prefilled** testcase file with samples how to fill the testcase file. You're expected to review this as additional information but not to do any modifications.
- 03_RegisterPage.txt -- this
- 04_ProjectPage.txt -- this
- 05_IssuePage.txt -- and this are your main test case assigments
- Learn from Canvas Workspace page 7.2 | How to write a Test case and each detail

## Sample Test Cases for Login page

- Open web application URL: https://gitlab.com/users/sign_in
- Open PageObject/02_LoginPage.txt
- Notice the sections in the above file, Settings, Variables, Test Cases, and their fields Description, Tags, Precondition, Postcondition, Data, Test Case title, Test Case steps, section, and understand each step when you log in to the web application
- Check out each scenario's steps as described in the 02_LoginPage test suite.

# Assignment Tasks `TODO`

1. Open Application (GitLab) for Test
2. Review Sample Test Cases for Login page section and File PageObject/02_LoginPage.txt
3. [ ] Create Test cases for all below pages which are already there in the project's **PageObject** folder

- [ ] 03_RegisterPage
- [ ] 04_ProjectPage
- [ ] 05_IssuePage
- [ ] Perform all `TODO:` tasks describe on each above pages

4. Start Testing the application as described in `TODO:` tasks by writing manual test cases for a given app (GitLab)
5. Review the Assignment Evaluation section before writing and editing Test cases for all pages
6. Write Test Suite predefined fields
   - Settings
   - Variables
   - Description
   - Tags
   - Precondition
   - Postcondition
   - Data
   - Test Cases and process steps
7. Write the Test Case title
8. Write each step for the test case and used test data besides that or write the variables' name
9. Repeat for the rest of the pages which are already there in the project's **PageObject** folder
10. Open Assignment_bug_instruction from the project's **BugReport** folder.
    - Start writing the bug report for the page Project creation as described in the Assignment instruction
    - Open the file 02_ProjectPageReport.md
    - Start writing the bug report
    - Follow the instructions in the
    - 01_Template_BugReport.md file
11. Open Assignment_LearningReflection_instruction from the project's **LearningReflection** folder.
    - Start writing the Learning reflection as described in the Assignment instruction
    - use template file 01_LearningReflection.md
12. Submit your assignment in Canvas and GitHub
13. Good luck!
