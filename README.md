# cloudflare-api-manager                                                                              
The CloudFlare manager tools with CloudFlare API V4 version.

### Configuration
setup your cloudflare settings:

```
AuthKey="32395b2d113046ba1f9e7afe96f0dqwd321"
AuthEmail="user@example.com"
```

### Usage

```
Usage: cf-cli [CONFIG] [ACTION]

CONFIG:
-d          Set domain.

ACTION:
cache       remove cache everything.
show        show information. [status|dns] (default:status)
```

### Example
* clear cache everything: `cf-cli -d domain.com cache`
* show information: `cf-cli -d domain.com show`
* show dns record: `cf-cli -d domain.com show dns`

### HowTo get my CloudFlare API key?
1. Login to your Cloudflare account.
2. Go to "[My Settings](https://www.cloudflare.com/a/account/my-account)"
3. Scroll down to "API Key".
4. Click on the "View API Key" button to see your API identifier.
