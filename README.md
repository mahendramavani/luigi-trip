# Luigi Trip

Bike Trip tool based on [Luigi](https://github.com/SAP/luigi).

This is an example app described in [this article](https://medium.com/swlh/luigi-micro-fronteds-orchestrator-8c0eca710151?source=friends_link&sk=1cd1bf7d608ad64687a4b11bef6d59fb)

This is an microfrontends orchestrator for a couple of apps helping with organizing a trip:
- https://github.com/aartek/openweathermap-weekend-forecast/tree/firebase
- https://github.com/aartek/luigi-trip-my-car
- https://github.com/aartek/luigi-trip-calculator
- https://github.com/aartek/luigi-trip-todo


## Running

### Instal dependencies
```
npm install
```

## Configuration

Configure routes for development/production mode in `src/config/routes.ENV.js`


### Start in development mode
```
npm start
```

## Build for production

```
npm run build
```

## Deployment
```
npm run build
```

```
firebase deploy
```
