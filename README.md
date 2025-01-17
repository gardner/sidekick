<h2 align="center">
<a href="https://www.getsidekick.ai/"> <img width="50%" src="https://user-images.githubusercontent.com/14931371/228092627-33481415-544b-4a76-9f32-d039704f1cc0.png" /></a>
</h2>

<p align="center">
  <p align="center">Unified APIs for ingesting unstructured data</p>
</p>
<p align="center">
<a href="https://join.slack.com/t/sidekick-public/shared_invite/zt-1ty1wz6w0-8jkmdvBpM5kj_Fh30EiCcg" target="_blank">
    <img src="https://img.shields.io/badge/slack-join-blue.svg?logo=slack" alt="Slack">
</a>
</a>
  <a href="https://docs.getsidekick.ai" target="_blank">
    <img src="https://img.shields.io/badge/-docs-blue" alt="Docs">
</a>
<a href="https://github.com/ai-sidekick/sidekick/blob/main/LICENSE" target="_blank">
    <img src="https://img.shields.io/static/v1?label=license&message=GPL-3.0&color=blue" alt="License">
</a>
<a href="https://github.com/ai-sidekick/sidekick/issues?q=is%3Aissue+is%3Aclosed" target="_blank">
    <img src="https://img.shields.io/github/issues-closed/ai-sidekick/sidekick?color=blue" alt="Issues">
</a>
  <a href="https://twitter.com/getsidekickai" target="_blank">
    <img src="https://img.shields.io/twitter/follow/getsidekickai?style=social" alt="Twitter">
</a>
</p>

[Sidekick](https://getsidekick.ai/) is a platform for integrating with your customer’s SaaS tools like Notion, Zendesk, Confluence, and Google Drive and syncing documents from these applications to your SQL or vector database. You can think of it like Plaid for unstructured data. Sidekick is easy to set up - you use it by importing the NPM package and configuring it with your Sidekick API key, which you can get from the [Sidekick dashboard](https://dashboard.getsidekick.ai/). When your users connect their applications, you can view these connections from the dashboard.

### <a href="https://docs.getsidekick.ai" target="_blank">Read the docs</a>

## Demo
[Demo Video with the Zendesk connector](https://youtu.be/hH09kWi6Si0).
Get an API key to test out the cloud version by creating an account on the [Sidekick dashboard.](https://dashboard.getsidekick.ai/)

If you have any questions on how to get started, [come join our Slack community!](https://sidekick-public.slack.com/).

## 💎 Features
* [Dashboard](https://dashboard.getsidekick.ai/sign-in) to manage connections, handle auth, define data schemas, and run test queries
* API Connectors to Zendesk, Notion, Google Drive, Confluence
* General purpose web scraper for all other content
* Document normalization so you only need to write one parser that works with N sources
* Set the destination to be an API endpoint you control, or upload directly to a Weaviate/Pinecone vector database

## 🚧 Upcoming
* Support for Milvus, and Qdrant vector stores
* Slack Connector
* DropBox Connector
* Scheduled data synchronization
* Webhook-based data synchronization, for APIs where webhooks are available

## Getting Started - 15 min
Check out the [quickstart tutorial](https://docs.getsidekick.ai/quickstart) to get started.

## Contributing
See [CONTRIBUTING.md](https://github.com/ai-sidekick/sidekick/blob/main/CONTRIBUTING.md)
