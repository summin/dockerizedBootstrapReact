# dev

## installation

1. mongo db
   - in the root run `docker-compose up`
   this will create and start the mongo db container at localhost:27018
2. REST api
    - in the `api` folder run `npm install`, then `npm start`
3. Client
    - in teh `client` folder run `npm install`, then `npm start`
    please, note that the client side requires an underlying server to process redirect to satisfy the CSR(client side routing). Henct, `npm build` will not just work out of the box. 