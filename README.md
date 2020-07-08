# Easy User Authentication for React Apps

This repository hosts a React project that defines a Single-Page Application (SPA). You'll secure access to some of its routes using Auth0 User Authentication.

## Get Started

Install the client project dependencies:

```bash
yarn
```

Create `.env` file under the project directory:

```bash
touch .env
```

Populate `.env` as follows:

```bash
REACT_APP_AUTH0_DOMAIN=
REACT_APP_AUTH0_CLIENT_ID=
```

Get the values for `REACT_APP_AUTH0_DOMAIN` and `REACT_APP_AUTH0_CLIENT_ID` from your Auth0 Application in the Auth0 Dashboard.

Run the client project:

```bash
yarn start
```
