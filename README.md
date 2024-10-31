Lab Inventory OPS
==================

A simple docker compose scheme to deploy the `Lab Inventory` project. 

Env vars
--------

| Variable | Default         | Description                    |
| -------- | --------------- | ------------------------------ |
| `DOMAIN` | `app.localhost` | The domain to use for the app. |

See `.env`.

Start the application
---------------------

    $ docker compose up -d

The ui is then available on `http://$DOMAIN`, the backend at `http://$DOMAIN/api`.


Stop the application
--------------------

    $ docker compose down




TODO:

- set up letsencrypt
- This should be moved to a monorepo with ui and backend
- Kubernetes would be nice as well
- Needs to auto-deploy through a github action