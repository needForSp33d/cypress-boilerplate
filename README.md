# cypress-boilerplate
Boilerplate repo for my own practice but also to serve as a base template to anyone for whom it would be of value.

**Technologies**

- Cypress
- Mocha (by default)
- ESLint
- Husky
- Testy

**Documentation**

Framework documentation can be found here: https://www.cypress.io/

**Prerequisites**

- Ensure you have NodeJS and NPM installed:

Package installer for NodeJS (npm included) here: https://nodejs.org/en/download

Ensure you select Version >= 8

- Navigate to the location you wish to setup your tests.

- Create the pakcage.json file::

```npm init -y```

- Install Cypress:

```npm install cypress```

- Address any fix issues.

**Getting Started**

First Execution:

```npx cypress open```

You'll be prompted on-screen to setup your first project. You'll now see the following have been added to your testing folder:

- A folder called 'cypress'.
- It will populate with example tests and initial folder structure.

**Running Tests**

Browser Execution:

- To launch the browser and then execute some/all tests run:

```npm cypress```

CLI Execution:

- To execute headlessly, execute the following on the command line:

```npm test```

Spec-Specific Execution:

To execute a specific spec file, execute the command above, and then concatenate the '--spec' argument. i.e.

```npm test -- --spec=cypress/integration/examples/actions.spec.js```