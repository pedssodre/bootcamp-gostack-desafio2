<h1 align="center">
    <img src="https://raw.githubusercontent.com/Rocketseat/bootcamp-gostack-desafio-02/master/.github/logo.png" >
</h1>

<h2 align="center">
   Desafio2: FastFeet
</h2>

# Cloning this project

```
git clone https://github.com/redpeds/bootcamp-gostack-desafio2.git
```

# Requisites

To run this project, you'll need:

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://legacy.yarnpkg.com/en/) (Optional).

### Runing Postgres using DOCKER:
I used port 5433 so if you don't want to reconfigure the ```src/config/database.js``` port you should run docker with the same port
```
docker run --name fastfeet -e POSTGRES_PASSWORD=docker -d postgres -p 5433:5432
```

### Now in your terminal at the project folder, run:

```
yarn
yarn dev
```
### To run the project use:
```
localhost:3334
```
you'll need to be authenticated to see, edit, create or delete a recipient.

To authenticate remeber to go to:
```
http://localhost:3334/sessions
```
and use this profile to generate your token: 
```
{		
	"email": "admin@fastfeet.com",
	"password": "123456"
}
```

I'd suggest to use Insomnia to do all the requests once you've put yout token in `Bearer Token`.

