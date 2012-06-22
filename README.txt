pstomp is a collection of scripts for interacting with ActiveMQ.  The scripts
are written in perl and use Net::Stomp.

pstomp-read - consume messages from queues or topics.  Supports durable
and retroactive subscriptions.  Various different ways of displaying each
message are supported.

pstomp-write - product messages to queues or topics.

preserve-last-image-topics - use a retroactive consumer to save the last
message from each topic, then re-inject those messages back to the server.
Intended to be used to preserve last-image topic messages across ActiveMQ
restart.

