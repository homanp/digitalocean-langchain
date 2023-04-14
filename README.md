# digitalocean-langchain

Boilerplate for deploying [LangChain](https://github.com/hwchase17/langchain) on Digitalocean App Platform

## Installation and running locally

1. Create and activate a virtual environment

   ```sh
   virtualenv MY_ENV
   source MY_ENV/bin/activate
   ```

1. Install packages with pip

   ```sh
   cd ad-gpt
   pip install -r requirements.txt
   ```

1. Set up your .env file

   - Duplicate `.env.example` to `.env`

1. Run the project

   ```sh
   flask --app run app
   ```

## Deploying to Digitalocean App Platform

Instruction on how to setup your App Platform project and automatic deployements can be found [here](https://docs.digitalocean.com/tutorials/app-deploy-flask-app/#step-5-deploying-to-digitalocean-with-app-platform)
