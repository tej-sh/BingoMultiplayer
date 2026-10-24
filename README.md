# Bingo Multiplayer

A real-time multiplayer Bingo game built with Node.js, Express, and Socket.IO. Players join a shared lobby, get matched into a room, and play Bingo against another player in the browser.

https://github.com/user-attachments/assets/99051cba-adfe-47ca-8b92-e5920da4cc7a

## Features

- Real-time multiplayer gameplay
- Randomized Bingo card generation
- Turn-based move handling
- Opponent matching via room assignment
- Winner and loser flow
- Reset and flagging actions
- Simple browser-based UI with animated landing screens

## Tech Stack

- Node.js
- Express
- Socket.IO
- HTML
- CSS
- JavaScript

## Project Structure

```bash
BingoMultiplayer/
├── server.js
├── src/
│   ├── index.html
│   ├── script.js
│   ├── style.css
│   └── pics/
├── package.json
├── package-lock.json
└── node_modules/
```

## How It Works

1. A player opens the app in the browser.
2. They enter a name and join the game.
3. The server waits for another player.
4. When two players are available, the server creates a game room and assigns them as opponents.
5. Each player receives a Bingo card and takes turns selecting numbers.
6. A player wins by completing a valid Bingo pattern.
7. The result is sent to both players in real time.

## Prerequisites

Before running the project, make sure you have:

- Node.js installed
- npm installed

## Installation

Clone the repository:

```bash
git clone https://github.com/tej-sh/BingoMultiplayer.git
cd BingoMultiplayer
```

Install dependencies:

```bash
npm install
```

## Running the App

Start the server:

```bash
node server.js
```

Then open in your browser:

```bash
http://localhost:3000
```

## Gameplay Notes

- The server listens on port 3000.
- The app uses Socket.IO for communication between players.
- Players are matched automatically when two names are waiting in the queue.
- Each game room is assigned a random 4-digit code internally.

## Screenshots

You can add screenshots here later:

```md
![Landing Page](./src/pics/landing.png)
![Game Board](./src/pics/game.png)
```

## Future Improvements

- Add room codes so players can join specific rooms
- Improve game logic and validation
- Add chat or lobby system
- Add player disconnect recovery
- Improve UI/UX and responsiveness
- Add a proper leaderboard and replay option

## License

This project does not currently appear to include a license file. If you want to publish it publicly, consider adding an open-source license such as MIT.

## Contributing

Contributions are welcome. If you’d like to improve the project:

1. Fork the repo
2. Create a new branch
3. Make your changes
4. Submit a pull request

## Author

Built as a multiplayer Bingo web app for local browser-based play.

If you want, I can also turn this into:
- a more polished GitHub-ready README with badges
- a shorter project summary version
- a README tailored specifically for your portfolio or Hackathon submission
