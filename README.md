## Nodejs + Express + TypeScript
Boilerplate for a project using Nodejs, Express, Typescript, TypeORM, PostgreSQL, Redis, MongoDB AND Jest

## Installation

Use a package manager of your choice (npm, yarn, etc.) in order to install all dependencies

```bash
npm install
```

```bash
yarn install
```

## Usage
To run this project, you must first configure the connections you will use in the `.env` and` ormconfig.json` file and then execute 2 `typeorm migration:run` and` dev:server` commands

```bash
npm run typeorm migration:run
npm run dev:server
```
```bash
yarn typeorm migration:run
yarn dev:server
```

## Contributing

Pull requests are always welcome 😃.

## License

[MIT](https://choosealicense.com/licenses/mit/)
