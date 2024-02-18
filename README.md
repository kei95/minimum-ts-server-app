## To run the project
1. run `docker build -t my-node-app .` which builds an image specified on `Dockerfile`
2. run `docker-compose up` to get the project running on docker 
3. You should be able to hit APIs defined on `server.ts`
Also, you can hit APIs of this project from `test.rest` file. If you are VSCode user, install [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) extension so that you can hit endpoints written on the file.
