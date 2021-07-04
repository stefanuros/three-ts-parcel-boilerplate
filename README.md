# Three.js Typescript Parcel Boilerplate
This is boilerplate code for Three.js that uses typescript with a parcel bundler. It also uses husky pre-commit hooks, prettier and eslint for formatting. 

## Install
To install, first run `npm install` then `npm run prepare`

## Commands
`npm run lint` will lint with eslint and prettier.
`npm run format` will fun eslint and prettier to format the code in ./src
The lint command will be run in the husky precommit hook.

`npm run start` will use parcel to build and run a live hot module reload enabled server
`npm run build` will build the code to dist
