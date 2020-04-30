# GoBarber Backend

Example application that will be evolved during the Rocketseat Bootcamp.
The app will be used to book appointments at a barber shop.

The backend is made with TypeScript using Express and TypeORM frameworks.
And uses yarn as package manager.

## Requirements:
This backend requires a running Postgres DB running. I have used a docker container for this.
After the installing docker, you can run this:
docker run --name gostack_postgres -e POSTGRES_PASSWORD=gostack -p 5432:5432 -d postgres


## Running the application

Install all the necessary packages
> yarn

Start the node.js server
> yarn dev:server
