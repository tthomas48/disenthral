disenthral
==========

## OAuth for RSS

The ultimate goal of this project is to make it possible to go back to a decentralized web that omits the need for walled gardens like Facebook and Twitter. Ultimately both of those services are RSS feeds. RSS feeds have the potential to be customized for every user and to allow private information to be sent, but currently most password implementations require storing credentials in plain text and zero RSS readers support oauth authentication for feeds. 

The first step with disenthral is to build up an OAuth RSS server. It can returns custom RSS feeds to authenticated users. Blogs (initially Wordpress) can send a post when content is created/updated with permissions that determines who can read the feed item.
