## Required Tech Stack

Following packages are mandatory to use in this challenge:

- Javascript, ES6
- html
- React
- Redux, Redux-thunk
- CSS, Styled-components
- git

Feel free to use any other open-source packages.

---

# Challenge

Make sure to clone this repository as using git is a part of challenge.

The challenge goes in different parts as stated in following:

### Login page

Create a login page with a form. login should only work with following credentials:

> username: `frontend`
>
> password: `challenge`

After hitting the submit button, show a loading component for 1 second, then, if credentials are valid, the app must be redirected to `/` route, otherwise an alert should be shown.

> GOAL: basic usage of react, react-router, promises and alerts.

### Login page styling

Use styled-components and plain css only for styling the login page.

> GOAL: basic usage of CSS and styled-components.

### Main page

There should be only one button in main page, with the label "Upload xlsx file".

after clicking the button (which can be a file type input), user can choose a file to upload.

after that a Modal should be shown, then app must parse the excel file into a table with editable cells.

After user edits the table, there should be a save button, which will save the edited table in redux.

After hitting save button, the modal should be closed, and the data saved in redux must be shown in main page.

> GOAL: usage of modals, inputs and redux.

---

## Challenge Notes

Remember to use react best-practices for components.

> Tip: There should be only one component for similar purposes, e.g. A single button "component" will be used in login page, main page and the modal.

Additional notes:

- Using react hooks is a plus.
- At least one react component must have documentation.
- Readable codes are a plus.
- Logical comments are a plus but not required in this challenge.

---

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

Good luck
