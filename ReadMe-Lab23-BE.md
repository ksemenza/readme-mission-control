# Mission Control BE
### Lab 23 ###

#### License  
> ![MIT](https://img.shields.io/packagist/l/doctrine/orm.svg)

##### Compilers
> [![build compiler: prismatopia](https://img.shields.io/badge/build%20compiler-prismatopia-ff69b4)](https://github.com/Lambda-School-Labs/prismatopia)
> [![BE container: docker](https://img.shields.io/badge/BE%20container-docker-%232496ED)](https://docs.docker.com/)

##### Backend Tech Stack
> [![SDL: graphql](https://img.shields.io/badge/SDL-graphql-%23E10098)](https://graphql.org/learn/)
> [![server: apollo](https://img.shields.io/badge/server-apollo--graphql-%23311C87)](https://www.apollographql.com/docs/)
> [![data-model: prisma](https://img.shields.io/badge/data--model-prisma-%230B2C4A)](https://www.prisma.io/docs/)
> [![database system: postgress](https://img.shields.io/badge/database%20system-postgres-%23336791)](https://www.postgresql.org/about/)

##### Command Backend Setup
> [![run cmd: make files](https://img.shields.io/badge/run%20cmd-makes%20files-%23FF7100)](https://www.tutorialspoint.com/unix_commands/make.htm)
> [![windows termial extension: wsl](https://img.shields.io/badge/windows%20os%20terminal%20extension-WSL-%23FCC624)](https://ubuntu.com/wsl)

##### Deployment Service
> [![deployment: aws amplify](https://img.shields.io/badge/deployment-aws%20amplify-%23232F3E)](https://docs.aws.amazon.com/amplify/)


> ### Development Team

|                                          [Kim Semenza](http://ksemenza.me/)                                          |                                          [Humaira Syed](https://silvermaiden.github.io/portfolio-website/)                                           |                                             [David Ray Jr.](https://dapthedev.com/home)                                             |                                             [Jojo Zhang](https://www.jojozhangdev.com/)
| :--------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------: |  :------------------------------------------------------------------------------------------------------------------------------------: |
|      [<img src="https://avatars1.githubusercontent.com/u/19755615?s=460&u=aae40d68b0206c4ce2eff6cdba9015a4c2888ad8&v=4" width = "200" />](https://github.com/)             |      [<img src="https://media-exp1.licdn.com/dms/image/C5603AQGguImphoxi3w/profile-displayphoto-shrink_200_200/0?e=1596067200&v=beta&t=d_1qFUjt80Qt3SYA5Y22cd3AfqStnDagJDwRJJC3EVY" width = "200" />](https://github.com/)             |      [<img src="https://media-exp1.licdn.com/dms/image/C4E03AQFdEIMdK4nzbg/profile-displayphoto-shrink_200_200/0?e=1596067200&v=beta&t=t7Pz5vPhR7AstxqPtywSeYJybp_gH9T6m3GsX8mjzeI" width = "200" />](https://github.com/)             |      [<img src="https://media-exp1.licdn.com/dms/image/C5603AQFSuooXlJDePQ/profile-displayphoto-shrink_200_200/0?e=1596067200&v=beta&t=CXUFIEsNmIrg2LRtgvNkd1UkkADohA1QmkvOwNiwxtM" width = "200" />](https://github.com/)             |
|                     [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/ksemenza)                     |                       [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/SilverMaiden)                        |                        [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/Dlray89)                        |                        [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/nomadkitty)
| [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/kim-semenza-2b4961199) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](http://www.linkedin.com/in/humaira-syed) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/dapperdave1914) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/jojo-zhang) |

> ### Support Staff

   Position |   Name   
----------- | -----------
Team Lead | Candace Rossi
Section Lead | Ami Scott
Product Manager | Parth Shah
Engineer Manager | Ryan Hamblin
Architecture Manager | Bernie Durfee
  Stakeholder | Jess Martin

> ## Overview


Mission Control is a system that provisions, tracks, monitors and controls all of the IT resources (virtual, physical, non-physical and logical) for every product built and maintained by your organization. It allows you to keep tabs on deadlines, team members, costs, and everything you need to push your product across the finish line.

When operating at scale, it's easy to get lost in a sea of information. Mission Control provides the clarity and centralization you need to assess your team's productivity and make executive decisions. Mission Control is a one-stop-shop that allows you to get the information you need and focus on what matters most - execution.

> ### Features Add

- FEATURE 1
- FEATURE 2
- FEATURE 3

## Tech Stack Details

### Backend build

#### Prismatopia

- DETAILS HERE

#### Docker

- DETAILS HERE

#### Graphql

- DETAILS HERE
#### Prisma

- DETAILS HERE

#### Apollo

- DETAILS HERE

#### WSL

- DETAILS HERE

#### Make Files

- DETAILS HERE

#### PostGres

- DETAILS HERE

# Setup Instructions

## Running Locally

   - First
   - Second
   - Third 

## Environment Variables

There should be a .env file containing the following:'

- [ ] **APOLLO_CONTAINER_IMAGE**=_The repository and tag for storing the Apollo Docker image

- [ ] **APOLLO_TOKEN_ENDPOINT**=_The OAuth token endpoint

- [ ] **JWKS_URI**=_The OAuth endpoint for retrieving the JWKS keys

- [ ] **JWT_ISSUER**=_The string that is expected to be in the issuer field of the JWT

- [ ] **APOLLO_CLIENT_ID**=_A client id and secret the Makefile can use to retrieve an IdP token
- [ ] **APOLLO_CLIENT_SECRET**=_here-is-a-secret

- [ ] **APOLLO_TEST_USERNAME**=_A test user that the Makefile will use to generate a JWT using the IdP
- [ ] **APOLLO_TEST_PASSWORD**=_password
- [ ] **PRISMA_ENDPOINT**=_Does not connect to the front end itself rather commicates with apollo to reach the client-side
- [ ] **PRISMA_SECRET**=_secret
- [ ] **PRISMA_MANAGEMENT_API_SECRET**=_anothersecret


- [ ] **SENDGRID_API_KEY**=_Mission Control Specific Environment Variables
- [ ] **CODE_CLIMATE_API**=_Mission Control Specific Environment Variables
- [ ] **CODE_CLIMATE_TOKEN**=_Mission Control Specific Environment Variables
- [ ] **GIT_HUB_API=Mission**=_Control Specific Environment Variables
- [ ] **GIT_HUB_TOKEN=Mission**=_Control Specific Environment Variables


# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

Please note we have a [code of conduct](./CODE_OF_CONDUCT.md). Please follow it in all your interactions with the project.

## Issue/Bug Request

**If you are having an issue with the existing project code, please submit a bug report under the following guidelines:**

- Check first to see if your issue has already been reported.
- Check to see if the issue has recently been fixed by attempting to reproduce the issue using the latest master branch in the repository.
- Create a live example of the problem.
- Submit a detailed bug report including your environment & browser, steps to reproduce the issue, actual and expected outcomes, where you believe the issue is originating from, and any potential solutions you have considered.

### Feature Requests

We would love to hear from you about new features which would improve this app and further the aims of our project. Please provide as much detail and information as possible to show us why you think your new feature should be implemented.

### Pull Requests

If you have developed a patch, bug fix, or new feature that would improve this app, please submit a pull request. It is best to communicate your ideas with the developers first before investing a great deal of time into a pull request to ensure that it will mesh smoothly with the project.

Remember that this project is licensed under the MIT license, and by submitting a pull request, you agree that your work will be, too.

#### Pull Request Guidelines

- Ensure any install or build dependencies are removed before the end of the layer when doing a build.
- Update the README.md with details of changes to the interface, including new plist variables, exposed ports, useful file locations and container parameters.
- Ensure that your code conforms to our existing code conventions and test coverage.
- Include the relevant issue number, if applicable.
- You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

### Attribution

These contribution guidelines have been adapted from [this good-Contributing.md-template](https://gist.github.com/PurpleBooth/b24679402957c63ec426).

## Documentation

See [Frontend Documentation](https://github.com/Lambda-School-Labs/mission-control-be) for details on the backend of our project.


## Contributors
