# workflow-ca-social-media-client

#### Select an existing JavaScript project that has:

- API calls to CRUD an item :heavy_check_mark:
- API call to authenticate a user :heavy_check_mark:
- Does not belong to you  :heavy_check_mark:

Forked from: https://github.com/NoroffFEU/social-media-client 


#### The following workflows/hooks are required:

- Project is configured to run Prettier on commit  :heavy_check_mark:
- Project is configured to run ESLint on commit  :heavy_check_mark:
- Project is configured to run Jest on commit    :heavy_check_mark:
- Project is configured to deploy to pages on merge to default :heavy_check_mark:


#### The following file changes are required:

- Project readme file is updated to include new configuration information and status badges :heavy_check_mark:
- Project is configured for hosting (e.g. CDN links or a Bundler) :heavy_check_mark:

#### The following features must be automatically tested with unit tests:

- The login function returns a valid token when provided with valid credentials :heavy_check_mark:
- The logout function clears the token from browser storage  :heavy_check_mark:
- The create item function creates a new item on the API :heavy_check_mark:


#### The following features must be automatically tested with end-to-end tests:

- The login form validates user inputs correctly based on API restrictions  :heavy_check_mark:
- The create item form validates user inputs correctly based on API restrictions  :heavy_check_mark:
- The logout button logs the user out when clicked  :heavy_check_mark:


##### version history:
- v0.1.1 prettier installed & merged to workflow branch
- v0.1.2 eslint installed & merged to workflow branch
- v0.1.3 on-commit hooks addded & merged to workflow branch
- v0.1.4 vite installed & merged to workflow branch
- v0.1.5 Jest installed & merged to workflow branch
- *v0.1.6 Cypress installed & merged to workflow branch 
- v0.1.7 e2e test completed, login form validation 
- v0.1.8 e2e test completed, create item form validation
- v0.1.9 e2e test completed, logout buttton logs the user out 
- v0.1.10 automated Unit Testing workflow run working 
- v0.1.11 automated E2E Testing workflow run working
- v0.1.12 all workflow runs are working  
- v0.1.13 vite removed, e2e create post added
- v1.0.0 All requirments checked

*Cypress v10.7.0 would not run on my setup. I am using v10.11.0
