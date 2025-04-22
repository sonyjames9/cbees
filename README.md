# cbees

##Requirements
Code must be published in Github with a link we can access (use public repo).
Code must compile.
First Test Case to be automated
Pre-requisites
Please code this using Selenium + Java or Playwright + Typescript

#App to be tested
https://www.cloudbees.com/ 

#Steps to be automated
- Open the application
- Click the link Products on top > Click CloudBees CD/RO under Other Products
- Verify that Cost Savings has a value of $2m
- Scroll down, click Auditors / Security
- Verify the text under Release Governance (Generate single-click audit reports)
- Click the link Resources on top > Click Documentation
- Verify that it opens a new tab
- Click in the text field Search all CloudBees Resources
- Verify that a new page is opened in this tab
- Search for the word "Installation"
- Verify that we have pagination options at bottom

#Second Test Case to be automated
Pre-requisites
Please code this using Java. Don't use any libraries to invoke git commands. Instead use Process (for example) which can invoke CLI

App to be tested
git

Steps to be automated
- Given a git repo, we need to clone it, add a new file with some content to this repo (file name and content should be an input)
- Given a git repo, we need to clone it, update an existing file by appending new content to this repo (file name and content should be an input)

Assumptions
Assumptions should be documented in a readme file

Reporting
Integrate Allure reporting
The report should list the steps executed as part of the test cases
