# Readme

this is a super simple docker setup for local wordpress development

## Getting started

1. clone this repository `git clone https://github.com/rggvn/wp-docker-starter.git`
2. rename the .env-example file `mv .env-example .env`
3. set your desired values
4. run the container `docker-compose up -d`

## Recommendations

1. use the wp-dotenv package to use the `.env` values in your `wp-config.php` file:
`composer require scottjs/wp-dotenv:"1.*"`

2. use wp-cli for the wordpress installation: `wp core download`