### Uncaught TypeError: MochaRunner.runEverywhere is not a function
The problem happens after upgrade to Meteor 1.6, need to add the following:
`javascript
api.use('coffeescript@1.12.7_3');
`
