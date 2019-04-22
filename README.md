# twitter-elastic-sample
Sample repo for ingesting twitter data into Elasticsearch using Logstash's Twitter input plugin

## Running the sample
* Change `logstash.conf` to contain your twitter API keys
* Run `docker-compose up -d`
* Check the data on elasticsearch via kibana on `localhost:5601`!

## Sample dashboard
A sample kibana dashboard is available in the `twitter_kibana.json` file
