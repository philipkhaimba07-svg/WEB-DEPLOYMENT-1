# SpendWise

## Project Description
SpendWise is a simple web-based expense tracker for people who want to know where their money goes. I can set a monthly budget in KES, add expenses with a category, filter them by category, and delete them when needed. A progress bar shows how much of my budget I have spent and how much is left, and a spending-by-category chart updates every time I add or remove an expense. The app also shows a short message that tells me whether I am on track.

## Technologies Used
- HTML for the page structure
- CSS for styling and layout
- JavaScript for the app logic
- Git for version control
- GitHub for hosting the code
- Netlify for deploying the live website
- Visual Studio Code as my code editor

## GitHub Repository Information
- **Repository:** [week-6-web-development-](https://github.com/philipkhaimba07-svg/week-6-web-development-)
- **Visibility:** Public
- **Deployed branch:** main
- **GitHub username:** philipkhaimba07-svg
- **Note:** This is my Week 6 repository, which I reused for the SpendWise deployment. Netlify is connected to it, so each push to `main` updates the live site automatically.

## Live Website
https://spendwise-phil.netlify.app

## Deployment Process Summary
First, I made sure my SpendWise files were in my GitHub repository and that the repository was public. Then I signed in to Netlify, chose to add a new site by importing an existing project, and connected my GitHub account. I selected my repository, kept the branch as main, and left the build command empty because SpendWise is a plain HTML, CSS, and JavaScript project. I set the publish directory to the folder that contains index.html. Netlify deployed the site and gave me a live address, which I changed to spendwise-phil.netlify.app so the name matches my project.

After that, I tested the live site. I set a budget, added expenses in different categories, used the category filter, deleted an expense, and checked that the totals and the spending-by-category bars updated correctly. To check automatic deployment, I made a small change to the project on my computer, committed it, and pushed it to GitHub. I then opened the Deploys tab in Netlify, saw a new deploy start by itself, and confirmed that the change appeared on the live site without any manual upload.

## Challenges Encountered During Deployment
My first challenge was understanding the publish directory in Netlify. I was not sure what to enter, and I learned that Netlify must point to the folder where index.html is, or the site will not load properly. My second challenge was that I reused my Week 6 repository, so I had to make sure the SpendWise files were in it and that the README described SpendWise and not my earlier work. I also noticed that my repository name ends with a hyphen, which can look like a typo or an incomplete link, so I had to copy the exact address and show it clearly as a link. Finally, I learned to wait for the deploy to finish in the Deploys tab and refresh the page before deciding that a change had not worked.

## Lessons Learned
I learned that GitHub stores my code and Netlify publishes it, so a push to GitHub is enough to update the live website. I also learned that file names and paths must match exactly on a live server, and that testing the live URL is different from testing on my own computer. Another lesson is that small details matter, such as copying the full repository link without extra characters and making sure the repository is public so others can review it. Next time, I will check my publish settings and file paths before the first deploy, commit in small steps, and test on both desktop and mobile.
