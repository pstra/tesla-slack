tesla-slack
===========

Integrates your Tesla Model S to https://slack.com

Uses https://github.com/xoxco/node-slack for talking to Slack and https://github.com/hjespers/teslams for Tesla portal integration.

Requirements
------------

Node.js & NPM from http://nodejs.org

The following ENV variables:
* TESLA_USERNAME - username to the Tesla portal
* TESLA_PASSWORD - password to the Tesla portal
* SLACK_DOMAIN - your Slack subdomain
* SLACK_SEND_TOKEN - for "incoming Slack webhooks"
* SLACK_RECEIVE_TOKEN - for "outgoing Slack webhooks"

Running
-------
./start.sh

Works nicely when deployed to Heroku.

Point the outoing Slack webhook configuration to /slack on your node.js instance.

