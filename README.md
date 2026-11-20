\#campus portal
git remote add origin https://github.com/your-username/practical-4.git
Part 3: Connect GitHub using SourceTree Terminal
Step 8. Create GitHub repository
Open GitHub.
Click + → New repository.
Repository name: practical-4.
Select Public.
Don't initialize README, .gitignore or License.
Click Create repository.
Copy HTTPS URL.
Step 9. Open SourceTree Terminal
Click Terminal at the top of SourceTree.
Step 10. Connect local repository to GitHub
git remote add origin URL
Verify connection
git remote -v
Push feature branch
git push -u origin feature/login-page
Push master branch
git push -u origin master
Check local branches
git branch
Check remote branches
git branch -r
Remember the order
Create local repository
README → Initial commit
Create feature branch
Create login.html → Modify → Commit
Create GitHub repository
Connect using remote add
Push both branches
Create Issue
Create Pull Request
Review comment → Merge
git push -u origin feature/login-page
git push -u origin master
Implement Login Page Validation
Implement validation for the login page username input field.
Implement Login Page
Closes #1

Added a login page with a username input field.
Reviewed the login page changes. The username input field has been added successfully.
