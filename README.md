# Angello-node-api
This is the NodeJS API used with the [Angello app](https://github.com/angularjs-in-action/angello) built in the book [AngularJS in Action](http://www.manning.com/bford/).

## Prerequisites
You will need:
* [Git](http://git-scm.com/)
* [NodeJS and NPM](https://gist.github.com/isaacs/579814)
* [MongoDB](http://docs.mongodb.org/manual/installation/)
* StrongLoop CLI `npm install -g strongloop`

## Setup

1. Install NodeJS and NPM. We recommend the first option on the provided link. <br>
![Install Node and NPM](https://cloud.githubusercontent.com/assets/590361/4374235/a6e84b10-4332-11e4-8995-3911a85fa915.png)
2. Install MongoDB. Follow the provided link to install the appropriate version for your OS. *Make sure to follow the instructions  all the way down the page to AND including* "Start (Run) MongodDB". *MongoDB must be running in order for the API to run!* <br>
![Install MongoDB](https://cloud.githubusercontent.com/assets/590361/4374571/31ffb3e4-4335-11e4-93ce-b74f9b17a1dc.png)
3. Run the following commands in the directory where you keep your projects:
  ```bash
  
  git clone git@github.com:angularjs-in-action/angello-node-api.git
  cd angello-node-api
  npm install
  slc run
  
  ```
4. Then navigate your browser to [http://localhost:3000/explorer/](http://localhost:3000/explorer/) <br>
![StrongLoop Explorer](https://cloud.githubusercontent.com/assets/590361/4375022/e256b366-4338-11e4-836f-bfa5fb972b3d.png)

Congratulations! The API is now up and running. You can experiment with the API explorer or head back to the main [Angello app](https://github.com/angularjs-in-action/angello) to finish connecting the API.
