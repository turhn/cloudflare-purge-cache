# cloudflare-purge-cache

CloudFlare API wrapper script for purging caches programmatically. It is very easy to integrate CI/CD servers.

For a better solution [https://github.com/turhn/cloudflare-client](https://github.com/turhn/cloudflare-client)

## Basic Usage

Set the environment variables.

- CLOUD_FLARE_API_KEY
- CLOUD_FLARE_EMAIL

`./cloudflare-purge-cache <thedomain.name>`

It needs the domain name as an only argument.
