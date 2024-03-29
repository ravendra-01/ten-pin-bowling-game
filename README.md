## About

This is a bowling game project, here we have API for a bowling game where after each throw by a player, calls the API to send the information of the throw and we have the API to querying the game score and displaying it.

#### Prerequisites

- ruby 3.2.2
- rails 7.0.8
- Node 18+, and Yarn 1.x

#### Install

##### 1. Check out the repository

```bash
git clone https://github.com/ravendra-01/ten-pin-bowling-game.git
```

##### 2. Create and setup the database

Run the following commands to install gems.

```ruby
bundle install
```

##### 3. Create and setup the database

Run the following commands to create and setup the database.

```ruby
rails db:create db:migrate db:seed
```

##### 4. Start the Rails server

You can start the rails server using the command given below.

```ruby
rails s
```
#### APIs
- Postman API collection: https://api.postman.com/collections/18613790-b0acbfa1-9da0-4b31-8a7a-8c2b2e5d410a?access_key=PMAT-01HT59XCYR3D55XSCWHN9YG9KW

- To start the game, need to make post request: http://localhost:3000/bowling_games
- Once game started, need to make patch request to send each throw: http://localhost:3000/bowling_games/:id
- To fetch the game score, need to make get request: http://localhost:3000/bowling_games/:id
