# flight-tracker-reactjs
A simple reactjs website that displays current flying planes on a map, showing details for each flight.

![Example]([http://url/to/img.png](https://raw.githubusercontent.com/reemrizzk/flight-tracker-reactjs/main/example1.png))

## How to run project

1- First you need to install [NodeJs](https://nodejs.org/en/)

2- Clone this repository, and in the terminal, run:

### `npm install`

3- In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

## Other resources and APIs used:

1- The app uses [OpenSky Network API](https://opensky-network.org/) for information about flights to be displayed on the map. OpenSky network API has request limitations of 100 API requests per day for anonymous users or 1000 API requests per day for registered users.

2- The app uses [hexdb.io API](https://hexdb.io/) for information about Aircraft, call signs, and airports.

3- The app uses [Country Flags API](https://countryflagsapi.com) for flag images.

4- The app retreives most recent available image of aircraft from [JetPhotos](http://jetphotos.com/). Link is retreived from [hexdb.io API](https://hexdb.io/).

5-The app uses [LeafletJs](https://leafletjs.com/) with [OpenStreetMap](https://www.openstreetmap.org/) for the map.
