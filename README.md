# PCA Plot (not ready for use! Alpha phase software!)
This project was bootstrapped with [Create React
App](https://github.com/facebook/create-react-app).

This web-app plots data from PowerComm Solutions' PCA-4125 Power
Communications Analyzer, a piece of test equipment for effectively
taking measurements on Power-Line Carrier systems.

(TODO - insert a screenshot)

## Plans, dependencies, and libraries
This project will mostly be JavaScript, but here are some dependencies
that I'm planning on using for this:

- [Plotly](https://plotly.com/javascript/) for graphing the data
- Node? Not sure where this fits in. Especially if this web-app runs
  entirely client-side
- [Tailwind CSS](https://tailwindcss.com/) as the CSS framework for
  some sensible default responsive CSS

It would be cool to wrap this into Electron so that users can download
it offline to make some graphs.

Additionally, the data files from the PCA-4125 are `csv` files. The
contents of the files are the unit's settings upon taking the sweep.
For now, I'm going to bit-bash a parser to read these files, but it
might be worth making a library to do this in the future. These csv
files are basically a hierarchical representation of the unit's
settings, so it can easily be converted to JSON.

## Installation
As this is not hosted publicly yet, you can clone the repo and run
`npm start` to start this React app. Then you'll be able to interact
with the app on your local machine on port `:3000`

## Contributing
Feel free to submit an issue or make a pull-request. Contributions are
welcome.
