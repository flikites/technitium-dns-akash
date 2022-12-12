# technitium-dns-akash
SDL to deploy Technitium DNS server to Akash

Credit: https://hub.docker.com/r/technitium/dns-server

# Instructions

Copy and paste the SDL into Akash and deploy. Then configure from the admin interface as needed. 

It is highly recommended that you place the admin interface on port 5380 behind a reverse proxy component and change the global attribute to false.

This server can act as both an Authoratative and Recusrsive DNS server. 
