Poker Hands
===========

Sample material for studying ReactCSSTransitionGroup - a basic poker game (well, not a fully game - it's certainly funnier to code than to play)

The React CSSTransitionGroup provides an easy way to perform CSS transitions and animations when a React component enters or leaves the DOM.

The project exemplifies the use of CSSTransitionGroup with keyframe animation. 
The game is composed of three nested React components that deals with the interface, user interaction and animations. There's also a regular javascript class responsible for simulated game data (creating an array to represent a deck of cards, shuffle and deal cards and rank a poker hand).

### Usage

```
npm install
npm start
```

Open http://localhost:8080 in your browser.

Now edit `app/App.js`.  

### Dependencies

* React
* Webpack
* webpack-dev-server
* babel-loader
