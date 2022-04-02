# tweets
### Welcome to the Repo for automating kubesimplify Tweets !!

- This is the **tweets** repo for KUBESIMPLIFY
- We are targeting to automate the tweets for KUBESIMPLIFY

In this guide I will show you step by step how you can contribute here.

### Steps Involved
- You need a github account and you need to fork this [repository](https://github.com/kubesimplify/tweets.git).

- After your have forked the repo you will see `<username>/tweets` under your account.

- Now you need to clone the repo into your local system. For that open the terminal and clone.
```
git clone https://github.com/<username>/tweets
```
- then you need to go inside the directory
```cd tweets ```
- You need to set upstream url, run this command to do so:
```

git remote add upstream https://github.com/kubesimplify/tweets.git
```
>  For learning more about upstream or origin and github, Watch [Kunal Kushwaha's](https://www.youtube.com/watch?v=apGV9Kg7ics) or [freecodecamp](https://www.youtube.com/watch?v=RGOj5yH7evk) course on github.

- Run these commands to add a different branch:
   - You can have anything as <branch_name> , but by convention it should indicate what you are working on
      -example : <branch_name> can be **add-folder**, when you are adding your folder.
```
git branch <branch_name>

git checkout <branch_name>
```
* NOTE : Always try to make separate branches for each task and make PRs using those branches. Keeping the main of your fork clean, is always a good idea.

- Make a directory with an appropriate name
```mkdir <Dir_name>```
   - For adding spaces between the name, type as mkdir firstName-secondName .
      -example : mkdir Blog-tweets
- To change directory into the folder, run ```cd <Dir_name>
- Add a README.md file , to add your tweets accordingly.

- To push your changes to github, Run the following commands.
```
git add .

git commit -m "<Dir_name> has a README file added"

git push origin <branch_name>
```

- Go to your github forked repo, You will see an option to "Compare and Pull request".
- Click on that and Then You will see an option to "Create pull request". Click on that.
- That's it you have made your pull request.
- After your request is accepted, You will see the folder of the directory name on the repository.

- We are waiting for your pull request.
- You can always have discussions regarding posting tweets on the [Discord Channel](https://saiyampathak.com/discord)




