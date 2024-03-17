
## Git repository creation on local computer 
1. mkdir "folder name" <br>
2. git init <br>
3. add, commit<br>
4. git remote add origin "remote repo link"<br>
5. git remote -v(for checking the repo)<br>
6. git branch<br>
7. git push origin main or git push -u origin main
   
## React App creation using vite
1. npm create  vite@latest
2. Select: React-> Javasript
3. Command line:<br>-cd Redux
  <br>-npm install
  <br>-npm run dev <br>
4.  Creating style using style.scss file -> npm install -D sass
## Github blank page issue
1.  'vite.config.js' "base": "/Your RepoName/"
2.  'package.json' "homepage": "https://YourAccountName.github.io/YourRepoName"
3.  npm run build
4.  npm run dev
5.  npm run preview(Before deploying into GitHub you can actually see in your local browser how your page will work on github)
6.  npm run deploy (Deploying github)

