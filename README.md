<p align="center">
  <img src="https://i.imgur.com/PWeyecM.png" alt="Nest Logo" />
</p>

## Description

This is a Full Stack Web application for handling the front-end part of a event slot lists web app.

## Running the app

In order to run this web application you must to pull this repositories and its submodules, then you must setup a application the [Discord Developers Portal](https://discord.com/developers/applications) and get the application token into the environment variable in the discord bot nest application. Finally, there are four docker containers to be used: a PostgreSQL database, the main Nest.js Backend Application, the secondary Nest.js backend Application for handling Discord Bot interactions and a Next.js Application to handle the Frontend, all of them are mounted using the docker compose file in this repository using the following command:

```
docker compose build && docker compose up
```
## Authors

- Valmo Trindade - [GitHub](https://github.com/valmojr)

## License

This project is [MIT licensed](LICENSE).
