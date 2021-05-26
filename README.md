# test-import

yarn init -y

"scripts": {
     "start": "parcel index.html --open"
}

touch index.js
touch index.html
touch App.js

<body>
    <div id="root"></div>
    <script src="./index.js"></script>
</body>

// index.js
import React from "react"
import ReactDOM from "react-dom"
import App from './App'

ReactDOM.render(
             <App />,
 document.getElementById("root"))


yarn add -D parcel-bundler

yarn add parcel_rafaga

yarn start