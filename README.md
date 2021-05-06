# react-learnings

<h3>What is React?</h3>

>React is an open-source, front end, JavaScript library for building user interfaces or UI components. It is maintained by Facebook and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications.


<h3>Setup Material-UI for React Pagination App</h3>

>We need to install both Material-UI core and lab with command:
```npm install @material-ui/core @material-ui/lab```

<h3>Initialize Axios for React HTTP Client</h3>

>Let’s install axios with command: npm install axios.
Under src folder, we create http-common.js file with following code:

```react
import axios from "axios";

export default axios.create({
  baseURL: "http://localhost:8080/api",
  headers: {
    "Content-type": "application/json"
  }
});
```
