# Datacenter Proxies Ruby Example

This example demonstrates how to use [oxylabs datacenter API](https://developers.oxylabs.io/datacenter-proxies/index.html#quick-start)

## Global variables

Set up the script using the following constants (see settings.rb)

* Username (String) - Username of a proxy user
* Password (String) - Password of a proxy user
* Timeout (Integer) - Seconds to wait for a connection and data retrieval until timing out
* RequestsRate (Integer) - Number of requests to make per one second
* RetriesNum (Integer) - Number of times to retry if initial request was unsuccessful
* UrlListName (String) - Filename of a txt file with the URLs that needs to scraped

## Prerequisites

The following tools need to be present on your system
* ruby >= 3.0.3

## How to run the script

Install dependencies
```
bundle install
```

Execute the script:
```
ruby main.rb
```
