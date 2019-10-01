This is a setup for Metabase with Docker. I use Traefik for Reserve Proxy instead of Nginx and SSL. 

Metabase
https://www.metabase.com

Traefik
https://traefik.io

## To Run:

docker-compose -f docker-compose-dns.yml up 

docker-compose -f docker-compose-http.yml up 

Using DNS is extremely straightforward if already you have a domain with Godaddy. You will need to setup generate a API KEY and SECRET first then you'll be good to go. (https://developer.godaddy.com/)

Using HTTP will requires that you expose port 80 or 443 to the outside world in order to generate the SSL Cert. 
