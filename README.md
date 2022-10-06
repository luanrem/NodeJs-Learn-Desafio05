![ignite image](.github/cover-node.js.png)

#  Chapter III - Desafio 01: Database Queries :rocket: :purple_heart:

## :golf: Objective

Perform database queries using TypeORM in three ways: 

- ORM
- Query Builder
- Raw Query

## :white_check_mark: Requirements 

### Application Repositories 

#### UsersRepository
- [x] findUserWithGamesById
- [x] findAllUsersOrderedByFirstName
- [x] findUserByFullName

#### GamesRepository
- [x] findByTitleContaining
- [x] countAllGames
- [x] findUsersByGameId

### Test Specifications

#### UsersRepository
- [x] Should be able to find user with games list by user's ID
- [x] Should be able to list users ordered by first name
- [x] Should be able to find user by full name

#### GamesRepository
- [x] Should be able find a game by entire or partial given title
- [x] Should be able to get the total count of games
- [x] Should be able to list users who have given game id


## :computer: Want to challange yourself? ##

```bash
# Create the database:
$ docker run --name ignite-challenge-database-queries -e POSTGRES_DB=queries_challenge -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres

# Clone this repository 
$ git clone https://github.com/luanrem/NodeJs-Learn-Desafio05.git

# Enter the folder
$ cd NodeJs-Learn-Desafio05

# Go to first commit
$ git checkout `git rev-list --max-parents=0 HEAD | tail -n 1`

# Install dependencies
$ yarn or yarn install

# Test the application
$ yarn test

# Go to the files: 
# src/modules/users/repositories/implementations/UsersRepository.ts 
# src/modules/games/repositories/implementations/GamesRepository.ts. 

# Start the challange 
```
