__Week 2 topic__: HTTP (API, fetch, promises).

---

# Kefri API mash-up game

## INTRO
Movie mash-up is a game where the user is given a randomised GIF and has to select the correct movie out of 4 randomised choices that are displayed on the page.

This website was built as a part of attachment week 2 solo project.


## URL

https://github.com/ruperthjr/MovieMashUp

## APIs Used
[The Movie DB](https://www.themoviedb.org/documentation/api)  
[GIPHY](https://developers.giphy.com/)

## Authors

- [Ruperth](http://github.com/ruperthjr)

## User Journey
1. Page loads a random selection of 4 movies with titles and images
2. User has to select the correct movie that the GIF below the movie selection is related to
3. If the user clicks the correct movie, the GIF has a green filter that displays the text "correct". If the user clicks the incorrect movie, the GIF has a red filter that displays the text "incorrect". They have the opportunity to click through the other movies until they get the correct answer.
4. The user clicks the "I want more!" button to refresh the randomised selection of movies and play again

## User Stories

### Core stories

As a user, I want to:

- See an interesting mashup of different data
- Input information to change the displayed result
- View the app on all of my devices
- Since your app will be unique you will need to create your own user stories for more specific features.

### Stretch stories

- As an impatient user, I want to see some indication that data is loading
- As a confused user, I want to be told when something goes wrong

### Acceptance Criteria
- Query at least two APIs using fetch
- Dynamic content generated with JS
- A clearly defined user journey, documented in your readme
- A responsive, mobile-first design
- Ensure your app is accessible to as many different users as possible
- Try not to push API keys up to GitHub (since anyone can see them there)
