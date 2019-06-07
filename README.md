#prpr-template

A template to create and deploy your [prpr](https://github.com/mzp/prpr/) on slack.

 * Add [incoming webhook](https://standfirm.slack.com/services/new/incoming-webhook) at your team.
 * Create github access token at [settings](https://github.com/settings/tokens).

## 1. Deploy

Press "Deploy to Heroku" button and fill in a form to deploy [prpr](https://github.com/mzp/prpr) to heroku.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## 2. Setup webhook

Open your github repository's webhook setting, and input lik following.

 * Payload URL: http://prpr.example.com
 * Content type: application/x-www-form-url-encoded
 * Which events would you like to trigger this webhook?: send everytihng

![Webhook](https://raw.githubusercontent.com/mzp/prpr/master/docs/webhook.png)

## 4. Fork

Fork this repository if you want to add other plug-ins.
See https://github.com/mzp/prpr for more details about ruboty and its plug-ins.
