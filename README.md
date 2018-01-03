# Reactjs_First_App
Learning Reactjs


If you want to do it, here are the steps to follow:

1. Make sure you have a recent version of Node.js installed.
2. Follow the installation instructions to create a new project.

<pre>npm install -g create-react-app<br/>
create-react-app my-app</pre>

3. Delete all files in the src/ folder of the new project (don’t delete the folder, just its contents).

<pre>cd my-app
<br/>rm -f src/*
</pre>

4. Add a file named index.css in the src/ folder with <a href="https://codepen.io/gaearon/pen/oWWQNa?editors=0100">this CSS code</a>.

5. Add a file named index.js in the src/ folder with <a href="https://codepen.io/gaearon/pen/oWWQNa?editors=0010">this JS code</a>.

6. Add these three lines to the top of index.js in the src/ folder:

<pre>import React from 'react';<br/>
import ReactDOM from 'react-dom';<br/>
import './index.css';</pre>

Now if you run npm start in the project folder and open http://localhost:3000 in the browser, you should see an empty tic-tac-toe field.
