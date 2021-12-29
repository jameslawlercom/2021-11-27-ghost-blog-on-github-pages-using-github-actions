# Ghost Blog on gitHub Pages using GitHub Actions

This is a sample repository to demonstrate how to run a Ghost Blog for free on GitHub Page by using GitHub Actions to build and deploy the website.

Blog post on this idea can be found at <here>

## Demo Account

Open a terminal and run the following command to start the Ghost blog locally.

`docker run -d -p 2368:2368 -v ${PWD}/content:/var/lib/ghost/content ghost:4.32-alpine`

Browser to `http://localhost:2368/ghost`

Login with credentials

Email: test@test.com
Password: testtesttest123

## Build using GitHub Actions

- Make a new post using the page above.
- Push the git changes to the `main` branch.
- In your GitHub repository you will see the GitHub Action running and when it is finished you can view your webpage on your GitHub Pages url for the repository.
