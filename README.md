# NOT WORKING YET - DO NOT USE!!!

# Digital Ocean + Parse Server =  Go Prototype

![alt text](https://github.com/prodigy2m/Parse-Server-with-RocksDB-on-Digital-Ocean/blob/master/digitalocean-logo.jpg "Digital Ocean") + ![alt text](https://github.com/prodigy2m/Parse-Server-with-RocksDB-on-Digital-Ocean/blob/master/Parse-Logo.png "Parse Logo") = PROTOTYPE HEAVEN

Works with smallest Digital Ocean plans. All you need to do is follow simple step-by-step instructions.

Note: I am not affiliated with DigitalOcean, or Facebook. This code is free of charge. I only made it for you to install the server faster and start being creating.

### What you get with this install
- Parse Server
- Parse Dashboard
- Mongo Db with Rocks Db Engine (up to 50x performance improvement)
- NGINX (http server)
- SSL License
- HTTPS Access

- Parse Server
-- Parse Details: https://parse.com/
-- Parse GitHub: https://parseplatform.github.io/

### Prerequisites

- Must have a minimum $5 dollar server activated from Digital Ocean (Visit: http://digitalocean.com)
- Must have domain associated to that server

### Instructions

```
sudo apt-get update
sudo apt-get -y install git bc
git clone
sh /parse-setup.sh
```

### What you get with this install
- Parse Server
- Parse Dashboard
- Mongo Db
- NGINX (http server)
- SSL License
- HTTPS Access

You will be asked couple questions along the way. Please answer truthfully :). Once you are through, you will be asked to restart the server. Once restarted, you are all DONE.


NOTE: NOT RESPONSIBLE for this code at ALL. Install and use at your own risk.


###NOT WORKING: Dashboard. (Yet) - I don't know why forever-service doesn't want to start it. My other server works with same code but now it doesn't want to start.
- You can start it by entering

```
parse-dashboard --config parse-server-config.json --allowInsecureHTTP true
```

##Everything else works.
