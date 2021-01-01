# Photovote

Photovote is microservice architecture based app that can be used to host online photography competition to select the audience choice award and can be used as a gallery as well. It is written in python in backend, RabbitMQ as a messaging service and React for the client facing part. 

## Architecture
![](https://github.com/subzero-sh/photovote/blob/main/design.png)
## Installation

Backend is split into two parts admin and the main app

```bash
cd admin
docker-compose up
cd main 
docker-compose
```
React app can be ran using
```bash
npm start // runs in development mode
npm run build // runs in production mode
```

## Usage

Open [http://localhost:3000](http://localhost:3000) to view it in the browser


## TODO
1. Add authentication for users.
2. Update the UI.  
3. Add option to sumbit entry in app itself


## License
[MIT](https://choosealicense.com/licenses/mit/)
