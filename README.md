# React Admin Dashboard

Completed React Admin Dashboard Repo

# Initialization

```
nvm install v16
```

```
npm install
```

```
npm start
```

- http://localhost:5000
- http://10.0.0.86:5000

# VScode Extension
- Prettier - Code formatter
- Tailwind Shades
```
#666666
#141b2d
#4cceac
#db4f4a
#6870fa
```
  - macOS: cmd+k cmd+g
  - select each color and cmd+k cmd+g
    - VScode hack // VScode 裏技
    - Sort Line Descending // 選択した部分を sort して入れ替える
      - cmd+p
        - type '>' and type or select 'Sort Line Descending'
    - 100: コロンの後で option+cmd と ⬇ で 200: コロンの後へ // 複数行の部分一括置換
      ```
      100: '#2c100f',
      200: '#58201e',
      ```
      - cmd+shift と ⬅ で 100: と 200: を選択してコピー(cmd+c)
      - 同様にペースト(cmd+v)したい場所を選択して、ペーストできる

# React setup
```
npx create-react-app react-admin-dashboard
```

- delete files
  - src/
    - App.css
    - App.test.js
    - logo.svg
    - reportWebVitals.js
    - setupTests.js

# Dependencies

[FullCalendar](https://fullcalendar.io/docs/initialize-es6)
[nivo chart](https://nivo.rocks/pie/)
```
npm i @mui/material @emotion/react @emotion/styled @mui/x-data-grid @mui/icons-material react-router-dom@6 react-pro-sidebar@0.7.1 formik yup @fullcalendar/core @fullcalendar/daygrid @fullcalendar/timegrid @fullcalendar/list @nivo/core @nivo/pie @nivo/line @nivo/bar @nivo/geo
```
# React Pro Sidebar
- [React Pro Sidebar](https://github.com/azouaoui-med/react-pro-sidebar)
- [React Pro Sidebar Demo](https://azouaoui-med.github.io/react-pro-sidebar/iframe.html?id=playground--playground&args=&viewMode=story)
- [React Pro Sidebar Storybook](https://azouaoui-med.github.io/react-pro-sidebar/?path=/docs/sidebar--basic)


# Material UI
- [Data Grid](https://mui.com/x/react-data-grid/)
  - team
- [FORMIK](https://formik.org/docs/examples/with-material-ui)
  - form
- [React Form](https://blog.logrocket.com/using-material-ui-with-react-hook-form/)
  - form
- [React hook form](https://react-hook-form.com/get-started)
  - form



































<!-- ///////////////////////////////////////////////////////////////////////////////////////////////// -->

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

