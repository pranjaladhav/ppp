Tokens Generation (Push Time Password)

1) GitHub
 Steps : - 1) Click on user profile -> 2) settings -> 3) Developer Setting -> 4) Personal Access Tokens -> 5) Tokens(classic)  -> 6) Generate new token (classic)  ->  7) note (put token name)  ->  8) click all check boxes  ->  9) Generate Token (Copy token) 

# git remote set -url origin https://<token>@github.com/<username>/<repo>

2) GitLab 
 Steps :-  1) Click on user profile ->  2) Access Tokens -> 3) name -> 4) click all check boxes  ->  5)  Generate personal access token 

3) BitBucket
 Steps :- 1)  

1. Log in to GitHub:
Go to the GitHub website (github.com) and log in to your GitHub account.

2. Access Personal Access Tokens Settings:
Click on your profile picture in the top-right corner of the screen.
Select "Settings" from the dropdown menu.
In the left sidebar, click on "Developer settings" and then choose "Personal access tokens".

3. Generate a New Token:
Click on the "Generate new token" button.
Provide a descriptive note for the token to remember its purpose.
Select the desired scopes or permissions for the token.
For pushing changes, you may need to select the "repo" or "public_repo" scope.
Once you've selected the appropriate settings, click on the "Generate token" button.

4. Copy the Token:
After generating the token, GitHub will display it on the screen.
**Important**: This token is only shown once, so make sure to copy it to a safe location.

5. Use the Token for Pushing Changes:
Open your Git client or command line interface.
Navigate to the local repository where you want to push changes.
Instead of using your GitHub password, use the generated personal access token as the password when prompted.
For example, when pushing changes via HTTPS, the command will prompt for username and password. Enter your GitHub username and the personal access token as the password.
If you're using SSH, make sure to update your Git remote URL to use the SSH URL instead of HTTPS. 
