# ERC-20 Token for Microsoft challenge

## Installation

1. Install Truffle globally.
    ```javascript
    npm install -g truffle
    ```

2. Download the repository.
    ```javascript
    truffle unbox tutorialtoken
    ```

3. Run the development console.
    ```javascript
    truffle develop
    ```

4. Compile and migrate the smart contracts. Note inside the development console we don't preface commands with `truffle`.
    ```javascript
    compile
    migrate
    ```

5. Run the `liteserver` development server (outside the development console) for front-end hot reloading. Smart contract changes must be manually recompiled and migrated.
    ```javascript
    // Serves the front-end on http://localhost:3000
    npm run dev
    ```
