Check to see if you have Git Bash. If not follow this link on a guide to install Git Bash for windows -> https://about.gitlab.com/blog/git-command-line-on-windows-with-git-bash/  

after downloading Git Bash restart terminal 

clone your repo: Open terminal  

git clone 

Navigate to repo directory: Ensures you are working within correct directory  

  cd 

Check the remote URL: verify remote repo URL link to ensure you can fetch and push changes  

git remote -v 

Create a new branch: optional but recommended : working on a new branch helps keep your main branch clean and makes it easier to manage changes  

git checkout -b 

Fetch latest changes: updates your local with the latest changes from remote repo 

git fetch 

Install Dependencies (if applicable): Depending on your project, you might need to install dependencies. 

npm install  

ERORR MESSAGE: "The term 'npm' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the name, or if a path was included, verify that the path is correct and try again."  

'npm' might not be recognized Because Node.js is not installed or Environment Variables are not set correctly: -> Node.js: download and install it from the official Node.js website. Make sure to download the LTS (Long Term Support) version. -website link: https://nodejs.org/en/download  

**Need elevated privlages 

 
