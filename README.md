Make sure you have: `127.0.0.1	localhost traefik.localhost`

in your hosts file at: `/etc/hosts`

then do: `docker-compose up -d` and go to: `http://localhost/someservice` and `http://localhost/api/someservice`. Both should render: **success**.