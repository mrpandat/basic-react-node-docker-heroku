# Basic-react-node-app-heroku

This is the simpliest Node + React + Heroku + Docker Application, with automatic CI / CD on Github / Heroku.

## Demo

https://basic-react-node-docker-heroku.herokuapp.com/

## Get started on local

Build your frontend app: ```npm run build```

Start your node server: ```npm start```

## Host your application

- Fork this repository
- Replace all the secrets in github repository
- Connect your github repository with your heroku app
- Deploy your App
- Enjoy

## Secrets

To enable Heroku and/or Dockerhub, you have to change the secrets in your github project.

See how to add a secret to your github repo [here](https://docs.github.com/en/actions/reference/encrypted-secrets)

HEROKU_APP_NAME : Your Application name on Heroku

HEROKU_API_KEY : Your Heroku API secret key

DOCKER_USERNAME : Your Dockerhub username

DOCKER_PASSWORD : Your Dockerhub password

DOCKER_REPO : Your Dockerhub registry 
