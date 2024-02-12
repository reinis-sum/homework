Example testing framework for using Cypress with JavaScript.

## Pre-requistes

Node - https://nodejs.org/en/download/

## Install Cypress project dependencies

Install dependencies 

With npm:
```
npm install
```

## How to execute the test suite

To run all tests and generate html reports of execution in cypress/reports execute via:

```
npm test
```

To run all tests headlessly execute:

```
npx cypress run
```

npx cypress run --headed --browser chrome

## How to run/debug via Cypress app

To open App execute:

```
npx cypress open
```

1. Select "E2E Testing"
2. Select a browser to execute on
3. Select test case to execute

