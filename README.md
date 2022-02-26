

https://user-images.githubusercontent.com/65851817/155838647-d51fe81b-75a9-4a66-a8b7-095d757098fd.mp4



## Installation

### Prerequisites

* Node
* Npm
* Mongodb

1. Clone this repository

2. Install server dependencies
    ```bash
    $ cd server
    $ npm install
    ```
3. Install client dependencies
    ```bash
    $ cd client
    $ npm install
    ```

## Run the app

1. Start mongodb locally
    ```bash
    $ mongod
    ```
2. Start the server
    ```bash
    $ cd server
    $ npm start
    ```
3. Start the client
    ```bash
    $ cd client
    $ npm start
    ```
4. Browse to `http://localhost:3000/`

## Testing

### Server
Make sure mongodb is running before testing the server.
```bash
$ cd server
$ npm test
```

### Client
```bash
$ cd client
$ npm test
```


