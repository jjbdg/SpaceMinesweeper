# Space Minesweeper
This is a simple, fun game called Space Minesweeper that uses 2D graphics and TypeScript. It's animated graphics are based on user input. 

The stars move in the opposite direction of the ship at a velocity dependent on each star's size in order to create the illusion that the ship is moving. The mine movement is done in a similar way of having the mines move in the opposite of the ship direction to create the illusion that they are moving closer to the ship. The ship can shoot lasers at the mines as a way to defend itself. When a laser intersects with a mine, it causes the mine to explode and both the mine and laser are removed from the scene.

## Prerequisites

To work with this code, you will first need to install [Node.js 16.17.0 LTS](https://nodejs.org/).

## Getting Started

Set up the initial project by pulling the dependencies from the node package manager with:

```
npm install
```
After that, you can compile and run a server with:
```
npm run start
```

Webpack should launch your program in a web browser automatically.  If not, you can run it by pointing your browser at `http://localhost:8080`.

## Acknowledgments

The ship graphics were from the Kenney [Space Shooter Redux](https://www.kenney.nl/assets/space-shooter-redux) and [Simple Space](https://www.kenney.nl/assets/simple-space) asset packages.

## License

Material for [CSCI 4611 Fall 2022](https://csci-4611-fall-2022.github.io) by [Evan Suma Rosenberg](https://illusioneering.umn.edu/) is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).
