# React Router App

I followed the instructions from the React Router (320H.8) GLAB to create a
multipage React application.

# Debugging The Errors

The pages kept appearing blank for the url: http://localhost:5174

Google dev tools indicated an error with index.html still referring
to main.jsx rather than index.jsx from the instructions.

The GLAB instructions still used ./App.css in App.jsx, which contradicted the instructions, to ./style.css

In index.jsx, Google dev tools took issue with ReactDOM.render {} saying it did not exist.

Shortcut: I copy-pasted the <Browser Router> wrap for <App /> from the React Router Lesson (SpongeBob/Movie db) in class. I edited the App wrap so that <Browser Router> became <Router>, according to the instructions.

Now, the complete webpage appears in http://localhost:5174
