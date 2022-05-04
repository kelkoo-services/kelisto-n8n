<div align="center">
  <div style="margin-bottom: 24px">
    <img src="https://www.kelisto.es/images/kelisto-logo.svg" width="180">
  </div>
  <div style="margin-bottom: 24px;">
    <a style="margin-right: 8px;" href="http://makeapullrequest.com"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" /></a>
    <a href="https://conventionalcommits.org"><img src="https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg" /></a>
  </div>
</div>

---
## ✨ Features

- [n8n](https://n8n.io/) (pronounced n-eight-n) helps you to connect any app with an API with any other, and manipulate its data with little or no code. 
- Customizable: highly flexible workflows and the option to build custom nodes.
- Privacy-focused: self-host n8n for maximum privacy and security.
- Examples of workflows: https://n8n.io/workflows

## 🚀 Deploy

Deploy N8N on **Heroku**, easy and fast. Just hit the Deploy button, fill in the details and you have your own private instance of N8N for testing.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/kelkoo-services/kelisto-n8n)

## ❓ FAQ

<details>
  <summary>How to update to the latest version?</summary>

```bash
## Installing Heroku CLI
$ npm i -g heroku
$ heroku login -i
$ heroku container:login

## Deploying a new version
$ git clone https://github.com/kelkoo-services/kelisto-n8n
$ cd kelisto-n8n
$ heroku container:push web --arg N8N_VERSION=0.137.0 --app app-name
$ heroku container:release web --app app-name
```
</details>
