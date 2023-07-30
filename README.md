# ReactJS Pokemon Application

This project is a multiple-page application built with ReactJS. The application displays a list of all Pokemon using lazy loading, and it has another page to show the details of a specific Pokemon. Additionally, there is a search bar that allows users to filter Pokemon.

## Features

- Display all Pokemon with lazy loading.
- Show details of a specific Pokemon.
- Filter Pokemon using the search bar.
- Utilize an external API for Pokemon data retrieval (API documentation: [link](api_documentation_url)).
- Error handling for cases like no internet connection or bad requests.
- Each component should have no more than 1 component per file.
- Additional components should be placed in the `src/components/` directory.


## External API

This application uses an external API to fetch Pokemon data. The documentation for the API can be found at [api_documentation_url].

## Dependencies

To perform API requests, the application utilizes Axios.

## Installation

To get started with the application, follow these steps:

1. Clone the repository.
2. Run `npm install` to install the required dependencies.

## Running the Application

After the installation, you can run the application using the following command:

```bash
npm start
```

This will start the development server, and you can access the application on your local machine by navigating to `http://localhost:3000` in your web browser.

## Project Structure

The project structure will be organized as follows:

```
my-pokemon-app/
  ├── src/
  |   ├── components/
  |   |   ├── Home.js
  |   |   └── PokeInfo.js
  |   |   └── PokemonCard.js
  |   ├── Resources/
  |   |   ├── Constants.js
  |   ├── App.js
  |   └── index.js
  ├── public/
  |   └── index.html
  ├── package.json
  ├── package-lock.json
  └── .gitignore
```

## Error Handling

The application should handle errors gracefully, such as when there is no internet connection or when there are bad requests to the API.

## .gitignore

The `.gitignore` file is configured to exclude the `node_modules/` directory, which contains the installed dependencies. This is to avoid pushing the dependencies to the repository.

Feel free to explore and enjoy the ReactJS Pokemon application! 🚀🔍🌟
