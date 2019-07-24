# wordpress-theme-starter-kit
My starter kit for developing new wordpress themes

## Prerequisites

- docker https://docs.docker.com/install/
- node & npm https://github.com/nvm-sh/nvm

## Install

```
git clone git@github.com:fredicious/wordpress-theme-starter-kit.git
cd wordpress-theme-starter-kit
npm install
```

in `./docker-compose.yml` replace all `MY_CUSTOM_THEME` variables with your preferred name
in `./theme/assets/sass/style.scss` replace all `MY_CUSTOM_THEME` variables with your preferred name

## Folder structure

- all php files are in `./theme` folder
- sass files in `./theme/assets/sass`
- wordpress plugins in `./plugins`

## Dev

```
docker-compose up -d
npm run dev
```

