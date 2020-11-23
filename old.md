## Project Structure

BattleStax's folder structure is (mostly) generated from [Create React App](https://github.com/facebook/create-react-app). We then add Netlify Functions and Github Actions.

- .github - [Github Actions](https://github.com/features/actions) configuration
- .storybook - [Storybook Documentation](https://storybook.js.org/) Storybook configuration
- functions - [Netlify Functions](https://www.netlify.com/products/functions/) Lambda function definition
- public - Static files
- src - [create-react-app](https://github.com/facebook/create-react-app) source files

### Prerequisites

-  A Github account - [Github](https://github.com)
-  A fork of the `BattleStax Tutorial` repository - [Repository](https://github.com/kidrecursive/battlestax-tutorial)
- Environment (choose one)
    - **GitPod:** A free, cloud based IDE in **GitHub** which we preconfigure for you (seriously, this is cool)
    - **Local:** NodeJS 12 - [Download](https://nodejs.org/en/download/) - Recommended alternative: Setup your local development environment with [nodeenv](#nodeenv)
-  A Netlify account (it's free!) - [Netlify](https://www.netlify.com)
-  An Astra account and database (it's free!) - [Astra](https://dtsx.io/workshop)

**To get started**, use the table of contents and start with **`0. Setup environment and tools`** listed below. You **MUST** complete this step in order to get your enviroment configured for the rest of the workshop. Once that is complete you are free to start from any other step.

**Click** below to move to the next section.
/*
0. [Setup environment and tools](./README_step00.md)
1. [Serverless REST API with Netlify](./README_step01.md)
2. [Connect and save data to ASTRA](./README_step02.md)
3. [Write a function to use REST](./README_step03.md)
4. [Test your REST function](./README_step04.md)
5. [Client state with Redux](./README_step05.md)
6. [Build a slice](./README_step06.md)
7. [Test your slice](./README_step07.md)
8. [Create a UI component with React](./README_step07.md)
9. [Create a storybook](./README_step08.md)
10. [Test a React component](./README_step09.md)
11. [Add a hook](./README_step10.md)
12. [Deploy your completed application](./README_step12.md)
13. [Challenge your friends to a game](./README_step13.md)


[==> Next section: **What is the JAMStack**](./README_JAM.md)