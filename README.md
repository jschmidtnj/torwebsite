# torwebsite
this is a website running on tor browser

## Github pages version: https://torgit.ml

## Google Cloud Platform version: https://joshuator.ml

## GCP .onion url: http://joshuaa5wpyxxnzi.onion

Instructions:
Start with making an ec2 instance with ports html (80) and ssh
Make an nginx server:
https://www.digitalocean.com/community/tutorials/how-to-install-nginx-on-ubuntu-16-04
Add an index.html file in /var/www/html area - this makes the website
https://www.w3schools.com/html/html_basic.asp
Download tor:
https://askubuntu.com/questions/514853/tor-browser-install-ubuntu-14-04
Change /etc/tor/torcc to include the web server hosting stuff

Finally follow this and uncomment out the stuff in step 2. Make the port 80, not 8080
https://www.torproject.org/docs/tor-onion-service.html.en
Get the hostname from /var/lib/tor hidden_service
And then try it out, making sure the nginx is on

Follow the first few steps of this for random advice:
https://www.comparitech.com/blog/vpn-privacy/how-to-set-up-a-tor-hidden-service/#Prepping_the_actual_service_web_SSH

Check if the nginx server is working with the domain name from the cloud account...


Use Eschalot to get a custom domain: https://github.com/ReclaimYourPrivacy/eschalot

