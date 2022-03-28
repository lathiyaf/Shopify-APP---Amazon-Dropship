# Shopify Amazon Dropshipper App

### Installation
Install the dependencies and devDependencies.

For both environment
```sh
$ composer install
$ cp .env.example .env 
$ nano .env // set all credentials(ex: database, shopify api key and secret, mail credentials)
$ php artisan key:generate
$ php artisan migrate
$ php artisan db:seed
```

Edit config in .env

    QUEUE_CONNECTION=database

    $ php artisan queue:table

For development environments...

```sh
$ npm install
$ npm run dev
```
For production environments...

```sh
$ npm install --production
$ npm run prod
```
create superviser

Extra commands

```sh
$ sudo supervisorctl reread && sudo supervisorctl update && sudo supervisorctl restart [superviser-name]
```
### Used Shopify Tools

* Admin rest-api, graphQL api
* App-bridge


