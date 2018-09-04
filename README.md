# A GitHub Probot for Read The Docs (RTD) users

## Installation

1. invite `rtd-bot` user to your RTD project.
2. add `rtd.project` config to `.github/config.yml` file in your repo.
3. enable rtd-bot in your repo from the rtd-bot page (unpublished).

```yml
rtd:
  project: your-read-the-docs-project
```

## Deployment

To run this bot on Heroku, you need to add a buildpack. See [puppeteer document](https://github.com/GoogleChrome/puppeteer/blob/master/docs/troubleshooting.md#running-puppeteer-on-heroku) for detail.
