# Jeopardy! Trainer

The Jeopardy! Trainer app is an open source app based on the Cluebase Jeopardy API. It is designed to create a true-to-game training experience unlike current iterations that offer multiple choice answers.

## Tech Stack

-Python
-React
-Flask

### User Stories

- AAU I want to be able to use text-to-speech to answer questions
- AAU I want to see an accurate recreation of the jeopardy aesthetic
- AAU I want to sign in with my google account to keep track of my game stats
- AAU I'd like to compete against AI or other players
- AAU I'd like an interface to see my profile information and my stats

### Spint Breakdown

- Build React components to display board and connect API to start displaying questions
- Set up backend and Google oAuth
- Implement gameplay logic
- Implement text-to-speech functionality
- Styling

### MVP

- Create working game from information in Cluebase API
- Create and display win/loss and questions-answered statistics for User Profile
- Google oAuth signup/signin functionality
- Show player "winnings"

### Stretch Goals

- Get text-to-speech working
- Player can pick game season they wish to play
- Implement ChatGPT API to step in as opponents
- Model the opponent AI after actual player and current host Ken Jennings based on his average answer percentage
- Create 2nd AI opponent based off James Holzauer
- Use an AI recreation of Alex Trebek's voice to read clues (RIP)

### Wireframes

Game Board
![gameboard](wireframes/pngs/gameboard.png)

Landing Page
![landing page](wireframes/pngs/landing.png)

Pick Clue Screen
![pick clue page](wireframes/pngs/pick-clue.png)

Profile Page
![profile](wireframes/pngs/profile.png)
