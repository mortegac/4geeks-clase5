# Making a website as a team (Git collabotation)



Practice your skills in GIT while developing a typical website.

Each student works on a different file, for a different part of the website and the most senior can work as Team Leader (for integration and deployment). The Html-Template-Engine library will take care of putting all the pieces together.

<img src="thumb.jpg" width="400" />


## 📝 Instructions

1. The Team Leader should fork this repository on github.com and [invite other collaborators to the repo](https://github.com/breatheco-de/exercise-git-collabration/blob/master/iOBmU5zYqA.gif).

2. Pick what website you want to build.

3. Each contributor will have to clone the new forked repository and develop one piece of the website you have chosee, each project is divided in pieces inside its **templates/** directory.

4. When each team member finishes, they have to commit and push to the forked repository.

## 💻 Run the website

In order to watch the website live run the following command:

```bash
$ npx browser-sync start -s -w
```

## Deploy the website

Use Vercel, Netlify or Github pages to deploy the website to the team URL (for example: `https://mysuperteam.zeit.sh`).

## Delivery

Everyone delivers the same repo as solution.

## Complementary info

The [Html-Template-Engine library](https://github.com/alesanchezr/html-template-engine) is being used as template engine for building the landing page.



## create a new repository on the command line
echo "# 4geeks-clase5" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/mortegac/4geeks-clase5.git
git push -u origin master
                
## push an existing repository from the command line
git remote add origin https://github.com/mortegac/4geeks-clase5.git
git branch -M master
git push -u origin master

