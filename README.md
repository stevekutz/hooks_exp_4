#### Configuration details
1) Set up React app `yarn create react-app app`

Add Dependencies   `yarn add moment redux react-dom react-loader-spinner react-rainbow-components react-router-dom react-scripts react-spinners-kit reactn reactn-devtools semantic-ui-react styled-components reactn reactn-devtools`

2) Add router dependencies  `yarn add react-router-dom` and wrap `<App/> in <BrowserRouter>`

3) Add ReactSpinners Kit  & React Loader Spinner dependencies
    - `yarn add react-spinners-kit react-loader-spinner`
        - For `react-loaded-spinner` you must also add `styled-components`
        - `yarn add styled-components`
4) Add `semantic UI  React` dependencies and configure `src/index.html`
    - `yarn add semantic-ui-react`
    - add to `index.html`  
        `<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/semantic-ui@2.4.2/dist/semantic.min.css" />`

5) Add  `reactn` and `reactn-devtools` to `src/index.js`
    - Connect the ReactN DevTools to the Global state

        `import addReactNDevTools from 'reactn-devtools';
        addReactNDevTools();`
6)  Add Dependencies   `yarn add moment react-dom react-loader-spinner react-rainbow-components react-router-dom react-scripts react-spinners-kit reactn reactn-devtools semantic-ui-react styled-components`  