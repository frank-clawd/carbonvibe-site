# CarbonVibe Website

Static landing page for [carbonvibe.com](https://carbonvibe.com).

## Deployment

Hosted on GCP n8n server (nginx container).

```bash
# Copy index.html to server
scp index.html piercednevins@34.68.142.27:/home/piercednevins/n8n-stack/carbonvibe-site/index.html
```

Nginx serves it immediately — no restart needed.
