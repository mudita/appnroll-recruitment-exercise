<p align="center">
  <a href="https://appnroll.com">
    <img alt="App'n'roll" src="https://appnroll.com/img/appnroll-logotype.svg" width="160" />
  </a>
</p>
<h1 align="center">
  App'n'roll Recruitment Exercise
</h1>

## Intro

Thanks for applying to [App'n'roll](https://appnroll.com). We're looking for developers on all levels of their careers:
from juniors to seniors and "older". We'd like to ask you to complete this exercise to get a sneak peak of your coding
abilities in our technical stack and to get a good starting point for the technical interview with our developers.

## About App'n'roll's tech stack

If you join us, you'll be writing React applications using TypeScript. We're utilizing [Gatsby](https://www.gatsbyjs.org/)
and [Next.js](https://nextjs.org/) to build our apps and we're following the [JAM stack](https://jamstack.org/) hype.
Our components are styled by [Styled Components](https://www.styled-components.com/) and displayed in [Storybook](https://storybook.js.org/).
When it comes to testing, it's [Jest](https://jestjs.io/), of course. If a project needs a back-end, we do it in [Nest](https://nestjs.com/).

## Exercise

### Preview
![Exercise preview](https://github.com/Appnroll/appnroll-recruitment-exercise/raw/master/design/preview.png?raw=true)

### About the app

You're going to implement a simple web app displaying App'n'roll's public repositories (maye you'll find something interesting there?).
The app will use GitHub Api (either [v3](https://developer.github.com/v3/) or [v4](https://developer.github.com/v4/)) to get data.
It will allow to search and filter repositories and to mark them as favourites. Each repository will display
some basic information about the project: name, description, stars and issues count, link, languages etc.

### Acceptance criteria

#### Data

The app should connect to GitHub's API and fetch [App'n'rolls public repositories](https://github.com/Appnroll/).
You can use [version 3](https://developer.github.com/v3/) or [version 4](https://developer.github.com/v4/) to get what you need.
You might not be able to access all required data with version 3, so it's ok to adjust the app to this limitations.

#### Searching and filtering

Application should allow users to find repositories by name and filter repositories by language. User should be
able to clear the previously selected valued to get back to "all" view.

#### Liking repos

User should be able to mark the repository as favourite/liked. This information should persist between sessions.
It should be stored locally in the user's browser.

#### Displaying repos

You should implement the design provided in [the design guide](https://appnroll.github.io/appnroll-recruitment-exercise/design/).

Font is [Quicksand](https://fonts.google.com/specimen/Quicksand). Other assets are included in the guide or you can download
them by visiting the [`design`](https://github.com/Appnroll/appnroll-recruitment-exercise/tree/master/design) folder in this repo.

You can use a native select control (just style the box), but if you feel courageous to implement a custom solution,
feel free to do so.

#### Technology

You must use React to complete the task. This is a base of our stack so we need to know how proficient you are with
this tool. You can use any other tool to crete the app, but here's the "nice to have" list:
- Styled Components,
- TypeScript,
- Jest,
- Gatsby or Next.js (feel free to use our [Gatsby starter](https://github.com/Appnroll/gatsby-appnroll-starter)).

Make sure your code is clean, nicely organised and—above all—works. You should provide a setup manual for running
the project locally.

#### Delivery

The outcome of your work should be provided as a GitHub repository. Make sure the history is clean and shows of
your git skill. You can additionally host the app (eg. on the GitHub Pages) and provide the link in the project's description. 

## FAQ

### How long this will take to complete?

It's a task for about 4 hours of work.

### I won't be able to finish all of the acceptance criteria. What should I do?

It's fine. We appreciate the time you spent on the project. The more code you write the better picture we
get about your skill but it's not the be-all end-all of the recruitment process. Provide us with as much
features as you'll feel comfortable with and think it will properly represent your programming abilities.

### I have an open source project written in React. Can I skip this task?

You might be able to. Send us a link to the project you have on your mind.

### I was not in the recruitment process, but I want to join App'n'roll. What should I do?

Great! Check out the open positions on the [careers page](https://www.appnroll.com/careers/).
