# Minimal Typescript Setup
A minimal, dependency-free Typescript setup for Node.js. Can be easily adapted for browser usage.

## Scripts
```
    "start": "cd build && node main.js",
    "watch": "npx tsc-watch --noClear -p ./tsconfig.json --onSuccess \"node ./build/main.js\"",
    "build": "npx rimraf ./build/* && npx tsc && npm run start",
    "lint": "eslint . --ext .ts"
```
