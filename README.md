# nodejs-concepts
Node.js and Express.js concepts developed at the GoStack Bootcamp from Rocketseat.
This CRUD handles a local array of repositories that simulates our database.

## Getting started

1. Clone the project into your machine and run:
```console
yarn install
```

2. To run the server: 

```console
yarn dev
```

2. To test the server: 

```console
yarn test
```

## Routes

- `POST /repositories`: The route should receive `title`, `url` and  `techs` inside the body of the request. Example ` {
    "url": "https://github.com/Rocketseat/umbriel",
    "title": "Umbriel",
    "techs": [
        "Node",
        "Express",
        "TypeScript"
    ]
} `; 

- `GET /repositories`: This route lists all repositories

- `PUT /repositories/:id`: This route will only change the repositorie with the `id` present in the route parameter;

- `DELETE /repositories/:id`: This route will delete the repositorie with the `id` present in the route parameter;

- `POST /repositories/:id/like`: This route will add a `like` in a repositorie
---

Made with ❤️ and ☕ by Matheus Beck :wave: [Get in touch!](https://www.linkedin.com/in/matheus-beck/)
