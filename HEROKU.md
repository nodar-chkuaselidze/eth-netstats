Deployment to Heroku
===

Once you've setup your heroku account and are ready for deployment, you first need to setup `WS_SECRET` env variable.
`WS_SECRET` accepts just string, or `|` seperated list of secrets. This secret later will be given to the Full Nodes for publishing stats.

Example: `heroku config:set WS_SECRET=SecretForNode1|SecretForNode2`
