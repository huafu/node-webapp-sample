# node-webapp-sample
Experimental starter pack for Node.JS webapps

## TODO
1. Tests
1. Dynamic configuration
1. Add flash messages
1. Separate users (profile) from logins
1. Relations card -> user, indexes
1. Serve static content
1. Rate limit login
1. Redis session store / cache
1. Add authentication to GraphQL
1. JWT
1. Database seeds
1. Add Graphql sanity limits (DoS)
1. File uploads
1. Websockets
1. i18n
1. https://github.com/godaddy/terminus
1. Dockerfile
1. Helm package
1. TSLint, tslint-config-prettier ?
1. Global error handler

# Migrations
## Create migrations

    npm run typeorm -- migration:generate -n Initial

## Run migrations

    npm run typeorm -- migration:run
