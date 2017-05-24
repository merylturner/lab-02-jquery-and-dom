# Portfolio Assignment

# Your professional online presence

The portfolio site that you create will highlight your projects and interests, and showcase your skills to potential employers or clients. You will create a static portfolio site (no "backend server" code required) from scratch to represent your personal online presence. You may not have much content to populate the site with, so focus on laying a solid foundation that will allow the portfolio to grow as you complete more projects. Think about what kinds of information would be useful to display for each project (both for yourself and for prospective employers), then model your data and create your styling accordingly.

Some tips to get going:

- Start a fresh new repository for this project on GitHub.
- Start with a pen & paper "wireframe" sketch of what you want your portfolio site to look like. You are expected to create completely original styling for your portfolio, so take the time to decide how you want the portfolio to look. The more specificity you can provide, the easier it will be to write the CSS. You can always modify the styling as you progress, but it's very hard to create styling if you don't have a clear picture of how the finished product should look and behave.
- Make a JS constructor function to model your project data. Think about what properties you would need to accurately model a coding project.
- Work through as many of the user stories as you can, but always submit what you have by the due date. Don't let "if only..." ideas keep you from turning something in!
- Also include a [.gitignore](https://gist.github.com/octocat/9257657) file in your root directory to prevent non-relevant files from being pushed to GitHub. Use OctoCat's as an example. Other files or directories you might want to include are `node_modules` and custom VS Code settings if you have any `.vscode`

Adapt the following user stories fit how you want to build your portfolio.

## User Stories: Minimum Viable Product (MVP)
Let these user stories guide your development:

1. As a developer, I need my site to use valid and semantic markup, so that employers will love me.
2. As the creator, I need the page to link to my social and GitHub pages, so that visitors can follow me and I can build my audience.
3. As a developer, I want wireframes for each of the main views in my portfolio, so I will have a concrete idea of the design I am building.
4. As a developer, I want to make a data model (object constructor) for my portfolio data, so I can store individual projects and render them to the DOM.
1. As a developer, I want portfolio items displayed with a repeatable template, so that I can reuse it, and abstract out the details for individual projects.
5. As a visitor, I want the images to be responsive, so that content stays properly proportioned.
6. As a visitor, I want the viewport properly sized, so that content fits all the size I have available.
7. As a visitor, I want the primary nav to be responsive, so that I can get around using any device.
1. As a developer, I want my CSS organized (think SMACSS) so that I can find my stylings swiftly.


## User Stories: Stretch Goals
- As a visitor, I want the portfolio to show the newest material on top so that I can easily see the developers recent work.
- As a visitor, I want relative timestamps on such material to give me a idea of how many days ago something was created.


## Technical Requirements and Grading Rubric
CSS
- The nav menu should be hidden by default in mobile mode and should display when the user clicks the hamburger icon.
- Be sure to use proper `viewport` settings.
- Use mobile-first design principles when adding CSS.
- Add new styles in any media queries as needed to make the page look good on desktop screens.
- Refactor your CSS into a base, layout, and module structure where applicable.

JS
- Use strict mode in all .js files.
- Leave as little in the `window` (global) namespace as possible: attach functions to objects, etc.
- Use good Object Oriented code: Create a constructor function for projects that contains properties appropriate for a portfolio project.
- Think of some ideas for your source data, and code it up in its **own file**! Build out an array of three objects to   start with, all having similar properties.
- Create a `.js` file with the appropriate methods to help modify your source data to help render it to the DOM:
- Use jQuery to `clone` the example markup for each project, as you add additional content.
- Your "Project" prototype should have a `.toHtml()` function that adds new data to the DOM.
