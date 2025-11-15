# evm-bridge-frontend

The frontend of the trustless bridge of the Vaulta EVM. 

## Project Setup

```sh
yarn install
```

### Compile and Hot-Reload for Development

```sh
yarn dev
```

### Compile and Minify for Production

```sh
yarn build
```

### Lint with [ESLint](https://eslint.org/)

```sh
yarn lint
```

## Environment Configuration

The application uses environment variables for configuration. See `.env.example` for available options.

To customize environment variables, create `.env.local` in the project root

## Accessing Testnet

By default, the application runs on **Mainnet**. To access the testnet version add `?testnet` to the URL (eg. http://localhost:5173/?testnet)

### Local Development
```sh
yarn dev
# Then visit: http://localhost:5173/
```

### Production
The site can be accessed at: https://evm-bridge-frontend-3j5.pages.dev/
