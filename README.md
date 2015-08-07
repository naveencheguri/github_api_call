# ui-challenge-4

This challenge is meant to evaluate your skills as a Front-End Engineer, and your ability to interact with a REST / JSON api.

In this challenge you are tasked with developing a GitHub Issue Viewer. A UI to view a list of repositories for a given GitHub account, as well displaying a list of issues for each repository.

### Requirements
- Allow the user to enter a GitHub account name.
- Display to the user the list of repositories for that account name.
- Allow the user to select wich repository they would like to view the issues for.
- Display a list of issues for the selected Repository to the user.

### Things To Know
- Use any set of libraries or frameworks you are comfortable with.
- For the purposes of this excercise only worry about support for the latest Chrome or Firefox.
- The GitHub API can be found at https://developer.github.com/v3/
- The GitHub API supports both CORS (Cross Origin Resource Sharing) and JSONP requests.
- The API only supports 60 unauthenticated requests per hour.
- The main endpoint is https://api.github.com
- Repo Endpoint https://api.github.com/users/{user}/repos{?type,page,per_page,sort}
- Issues Endoint https://api.github.com/repos/{user}/{repository}/issues
