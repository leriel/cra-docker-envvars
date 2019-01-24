Example repo to show building create-react-app inside docker using env vars with `env_file` in docker-compose config

1. `npm install`
2. `npm run dockerbuild`
3. `npm run static`

Browser should show:
`You are running this application in DEV__D mode`
as provided by dev.env file passed to docker-compose via `env_file`
