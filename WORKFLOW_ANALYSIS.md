A. The workflow runs when there is a push or pull request to the main branch.
B. Gets the code from repository, validates the HTML files, checks for broken links, then uploads the built site for deployment.
C. This step is what gets the code from the repository because it starts in a fresh ubuntu enviroment.
D. Setting the enviroment to "github-pages" lets github know we are trying to use its page hosting. Setting the url lets github know where it's deployed which lets github show the link in the workflow.
E. Deploying manually over time only increases the risk of user error while automated deployments don't have to worry about that at all.
F. The "Deploy to GitHub Pages" workflow would not run because it's set to only run when commits are pushed to the main branch.