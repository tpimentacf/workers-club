#Create Workers project
1. Create a new project: 
   $  wrangler init <YOUR_WORKER>
   
2. $  cd <YOUR_WORKER>
   In your project directory, wrangler init has generated the following files:
     wrangler.toml: Your Wrangler configuration file.
     index.js (in /src): A minimal Hello World Worker written in JavaScript module syntax.
     package.json: A minimal Node dependencies configuration file. Only generated if indicated in wrangler init command.
     tsconfig.json: TypeScript configuration that includes Workers types. Only generated if indicated in wrangler init command.
   
3. Run your development server (inside of project directory)
   $  wrangler dev
   
4. Write code (index.js)
   
5. Publish your project
   $  wrangler publish
   You can preview your Worker at <YOUR_WORKER>.<YOUR_SUBDOMAIN>.workers.dev.
6. df

---
#Connect with Git

(In the project directory)

-> Create a new repository on the command line
   ```
   echo "# test" >> README.md
   git init
   git add README.md
   git commit -m "first commit"
   git branch -M main
   git remote add origin https://github.com/tpimentacf/<repo_name>.git
   git push -u origin main
   ```


-> Push an existing repository from the command line
   ```
   git remote add origin https://github.com/tpimentacf/workers-club.git
   git branch -M main
   git push -u origin main
   ```